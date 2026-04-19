---
name: repo-modernization
description: Modernize this repository by simplifying rules, skills, docs, and operating model. Use when updating the AI development base itself, especially when reducing duplicated guidance or replacing heavy workflows with lighter ones.
---

# Repo Modernization

## Purpose

この基盤リポジトリ自体を整理するときの最小手順です。

## Checkpoints

1. 同じ説明が `README`、`Docs`、`rules` に重複していないか確認する
2. 長い手順が rule に入っていないか確認する
3. 反復ワークフローだけを skill に寄せる
4. `Docs` が実装判断に必要な最小量になっているか確認する

## Decision Rules

- rule は短い恒久ガイドに限定する
- skill は繰り返し価値がある手順だけにする
- Docs は成果物だけを置く
- 一般論、古い運用、互換のためだけの説明は削るか隔離する

## Typical Targets

- `README.md`
- `Docs/README.md`
- `.cursor/rules/`
- `.cursor/skills/`
- `rules/`
