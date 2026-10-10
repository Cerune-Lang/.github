# Cerune

**観測可能な計算を探求する、実験的なプログラミング言語とそのエコシステム。**

日本語 | [English](https://github.com/Cerune-Lang/.github/blob/main/profile/README.en.md)

Ceruneは、静的型付けを備えた実験的なプログラミング言語です。

ソースコードがどのように解釈され、中間表現へ変換され、実行可能なコードになるのか。その過程を観察し、比較し、理解できることを大切にしています。

言語本体だけでなく、開発ツール、数値計算ライブラリ、実験的なアプリケーションも少しずつ育てています。

## はじめに

| プロジェクト | 概要 |
| --- | --- |
| **[Cerune](https://github.com/Cerune-Lang/Cerune)** | 言語本体・コンパイラ・実行基盤。 |
| **[Tint*](https://github.com/Cerune-Lang/Tint-St)** | 中間表現やコード生成過程、実行経路を観測するビジュアル環境。 |
| **[Cerune Language Support](https://github.com/Cerune-Lang/Cerune-vscode)** | `.ceru`ファイルのシンタックスハイライトなどを提供するVS Code拡張。 |

## ライブラリ

- **[Quantelia](https://github.com/Cerune-Lang/Quantelia)** — Cerune向けの汎用数値計算ライブラリ。計算結果だけでなく、数値的な挙動や演算の規則も理解できることを目指します。
- **[Nerune](https://github.com/Cerune-Lang/Nerune)** — Cerune向けの実験的な機械学習ライブラリ。Tensor計算やニューラルネットワーク、学習処理などを探求しています。

## 実験プロジェクト

- **[Cisa](https://github.com/Cerune-Lang/Cisa)** — Ceruneで実装する小さな仮想CPU。実際に言語を使いながら、言語設計や実行機能を検証しています。

## 大切にしていること

**観測可能性・再現性・理解可能性。**

コンパイルや実行をブラックボックスとして扱うのではなく、その途中で何が起こっているのかを追跡できることを目指しています。

複数の中間表現や実行経路を比較し、生成されたコードと元のソースコードの関係を理解することも、その取り組みの一部です。

このエコシステムは現在も開発中です。言語仕様、API、実装は実験と検証を通じて変わっていく可能性があります。
