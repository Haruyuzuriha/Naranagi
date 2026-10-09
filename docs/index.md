---

## icon: lucide/book-open

# PDF Viewer(仮称)

PDF上に自由に描画・書き込みができ、読書中に同一ウィンドウ内でノートを取れる、語学学習者向けのオールインワン読書・学習環境。

## Documentation

### Requirements

* [要件定義書](要件定義書.md)
* [トレーサビリティ](トレーサビリティ.md)

### System Design

* [システム方式設計書](システム設計/システム方式設計書.md)

## Project Overview

| 項目       | 内容                                 |
| -------- | ---------------------------------- |
| プロジェクト   | PDF Viewer(仮称)                     |
| Version  | v0.4(要件定義) / v0.1(方式設計・ドラフト)       |
| Language | Java                                |
| Runtime  | JRE(PC専用デスクトップアプリケーション)           |
| Build    | 未定                                  |
| Database | SQLite(本ごとファイル + 横断共有ファイルのハイブリッド構成) |

## Core Principles

1. 複数ウィンドウの行き来をなくし、同一画面内で読書とノート作成を完結させる
2. 早さより正しさを優先し、「バイブコーディング」を避ける
3. 注釈・ノート・AIルックアップ・個人辞書は個別機能の寄せ集めにせず、一つの基盤モデルを共有して連携動作させる

## Current Status

| 項目             | 状態             |
| -------------- | -------------- |
| Requirements   | 🟢 Defined     |
| Architecture   | 🟡 In progress |
| Implementation | ⚪ Not started  |
| Testing        | ⚪ Not started  |
| Release        | ⚪ Not started  |
