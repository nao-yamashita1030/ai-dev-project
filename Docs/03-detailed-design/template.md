# 詳細設計書

このディレクトリには、詳細設計の各項目を分割して管理します。

## ディレクトリ構造

```
03-detailed-design/
├── template.md              # このファイル（目次・概要）
├── 01-class-design.md      # クラス設計
├── 02-database-design.md   # データベース詳細設計
├── 03-process-flow.md      # 処理フロー
├── 04-business-logic.md    # ビジネスロジック設計
├── 05-security.md          # セキュリティ詳細設計
├── 06-error-handling.md    # エラーハンドリング詳細
├── 07-performance.md       # パフォーマンス詳細設計
├── 08-test-design.md       # テスト設計
├── api/                    # API詳細仕様
│   ├── README.md           # API一覧・目次
│   └── [api-name].md       # 各APIの詳細仕様
└── screens/                # 画面詳細設計
    ├── README.md           # 画面一覧・目次
    └── [screen-name].md    # 各画面の詳細設計
```

## 各ファイルの説明

### メインファイル

- **template.md** (このファイル): 詳細設計の目次と概要
- **01-class-design.md**: クラス設計
- **02-database-design.md**: データベース詳細設計
- **03-process-flow.md**: 処理フロー
- **04-business-logic.md**: ビジネスロジック設計
- **05-security.md**: セキュリティ詳細設計
- **06-error-handling.md**: エラーハンドリング詳細
- **07-performance.md**: パフォーマンス詳細設計
- **08-test-design.md**: テスト設計

### API詳細仕様（api/ ディレクトリ）

- **api/README.md**: API一覧と目次
- **api/[api-name].md**: 各APIの詳細仕様（例: `api/user-authentication.md`）

### 画面詳細設計（screens/ ディレクトリ）

- **screens/README.md**: 画面一覧と目次
- **screens/[screen-name].md**: 各画面の詳細設計（例: `screens/login.md`）

## 作成手順

1. 各テンプレートファイルを `draft/` ディレクトリにコピー
2. プロジェクトに合わせて内容を記入
3. APIや画面は専用ディレクトリ内に個別ファイルとして作成
4. 確定したら `fixed/` に移動
