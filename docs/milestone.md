# 「ec-ddd-php-sample」 の完成までのマイルストーン一覧

| No.        | マイルストーン名              | 説明                                                                            | ブランチ例                       |
|------------| --------------------- | ----------------------------------------------------------------------------- | --------------------------- |
| 1          | カテゴリ機能追加              | `categories` テーブルのマイグレーション＆シーダー作成、Domain／Infrastructure のカテゴリファイル追加           | `feat/categories`           |
| 2          | カテゴリ CRUD API         | Category の一覧・詳細・作成・更新・削除を行う Controller／Request／Encoder／Repository 実装          | `feat/category-crud`        |
| 3          | Product（Book）エンティティ拡張 | `Product` エンティティに `categoryId` を追加し、ValueObject／RepositoryInterface／Model を更新 | `feat/product-category`     |
| 4          | Product CRUD API      | Product の一覧・詳細・作成・更新・削除を行うエンドポイント実装                                           | `feat/product-crud`         |
| 5          | カート & 注文基盤            | Cart／Order ドメインロジックの実装、Repository／Controller 雛形追加                             | `feat/cart-order-structure` |
| 6          | 購入フロー & 在庫管理          | 注文確定時の在庫減算ロジックとイベント発行（OrderCreated, ProductStockUpdated）／メール送信                | `feat/checkout-stock`       |
| 7          | バリデーション・エラーハンドリング     | Request バリデーションルール追加と例外ハンドリング整備                                               | `feat/validation`           |
| 8          | ユニットテスト & Feature テスト | Domain／Repository／Controller のテストケース実装                                        | `test/add-tests`            |
| 9          | ドキュメント & README 完成    | 各機能の使い方・API 仕様・セットアップ手順を README へ反映                                           | `docs/update-readme`        |
| 10<br>(予定) | CI/CD & デプロイ設定        | GitHub Actions でマイグレーション・シーディング・テスト・デプロイ自動化                                   | `ci-cd/setup`               |
