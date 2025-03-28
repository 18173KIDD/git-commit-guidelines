# 📝 Gitコミットメッセージガイドライン

## システムコマンド
- 日本語で応答すること
- ファイルの変更があった場合、都度コミットを行うこと
- Gitのコミットメッセージには以下の要素を含めること：
  1. 先頭にカラフルでユニークな絵文字を付与し、可読性を向上させる
  2. 日本語でコミットメッセージを作成する
  3. 変更内容が分かるように、タイトルと概要を記載する
  4. 必要であればブランチを作成して提案する

## Gitコミットルール（Gitflow概念に基づく）

### 1. ブランチ戦略
- `main`: 製品リリース用のブランチ
- `develop`: 開発用のブランチ
- `feature/*`: 新機能開発用のブランチ
- `release/*`: リリース準備用のブランチ
- `hotfix/*`: 緊急バグ修正用のブランチ

### 2. コミットメッセージ形式
```
<絵文字> <タイプ>: <タイトル>

<本文>

<フッター>
```

### 3. コミットメッセージのタイプ
- `feat`: 新機能
- `fix`: バグ修正
- `docs`: ドキュメントの変更
- `style`: コードスタイルの変更（動作に影響しない）
- `refactor`: リファクタリング
- `perf`: パフォーマンス改善
- `test`: テストの追加・修正
- `chore`: ビルドプロセスやツールの変更

### 4. 注意点
- 主要な変更とその目的に焦点を当てる
- 変更を明確かつ簡潔に説明する
- 見やすさを重視し、必要に応じて箇条書きを使用する
- 同じ絵文字の多用を避ける
- 必要に応じて、少数のファイルごとに別ブランチを提案する
- Stageの差分を注意深く確認し、追加・削除された機能を正確に把握する

### 5. コミットメッセージの出力
- 指定されたフォーマットに従い、タイトルと本文を含める
- 不要な情報は出力しない

### 6. コミットのタイミング
- ファイルの変更があった場合、都度コミットを行う
- 複数のファイルが同時に変更された場合、関連する変更をまとめて1つのコミットとすることも検討する