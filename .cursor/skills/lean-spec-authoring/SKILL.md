---
name: lean-spec-authoring
description: Create short implementation-ready specs focused on decisions, constraints, acceptance criteria, and only necessary flows. Use when drafting or refining Brief, Spec, Build, or Verify docs in this repository.
---

# Lean Spec Authoring

## When to Use

- `Docs/01-brief` から `Docs/04-verify` の文書を作るとき
- 仕様書を短くしたいとき
- 長いテンプレートを削って核心だけ残したいとき

## Default Output

標準で残すのは次の3点です。

- 意思決定
- 制約
- 受け入れ条件

必要な案件だけ、次を追加します。

- 主要フロー
- 例外

## Rules

- 一般論や背景説明を膨らませない
- 実装判断に効かない見出しは作らない
- 1ファイルを短く保つ
- 同じ説明を複数ファイルに繰り返さない

## Phase Guide

### Brief
- 目的
- 対象
- やること
- やらないこと

### Spec
- 意思決定
- 制約
- 受け入れ条件

### Build
- 実装メモ
- 判断ログ
- 未解決事項

### Verify
- 確認項目
- 結果
- 残課題
- 出荷判断
