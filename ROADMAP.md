# Roadmap / 今後の開発

**OpenQuest by Toppy · Research Preview · Updated 2026-11-07**

These are development priorities, not release-date commitments. この順序は開発上の優先順位です。公開日を約束するものではありません。

| Stage / 段階 | Work / 内容 | Exit evidence / 確認すること |
|---|---|---|
| 1. Make the prototype understandable / 体験を伝える | Consistent OpenQuest identity, concept film, current status, authentic demo screenshots | A first-time visitor can tell what the product is for and distinguish a concept from an implemented workflow. 初見で用途と実装範囲が分かる。 |
| 2. Repeatable local demo / 再現できるデモ | Start on a clean supported Mac with sample data | Startup, map navigation, returning to results, and restart behavior are repeatable. 初期状態から起動・操作・再起動できる。 |
| 3. End-to-end live workflow / 実アカウントでの一連操作 | Connect, start a small task, retain its result, restart, and resume | Record the account/runtime versions, boundaries, completion, failures, and quota behavior without publishing credentials. 接続から保存・再開まで確認し、失敗時の挙動も記録する。 |
| 4. Data continuity / データを引き継ぐ | Explain storage locations; validate export, backup, restore, and migration | Recover a test workspace on a clean environment with clear success/failure feedback. 別の環境で試験用データを復元できる。 |
| 5. Distribution readiness / 配布に向けた確認 | Installation, updates, permissions, and native-app reliability | A documented supported-environment and release process exists. 配布物と対応環境、更新手順を検証する。 |

Real AI development through to a real GitHub pull request needs its own controlled validation before it is presented as a reliable feature. Hosted multiuser access, cloud synchronization, and work scheduled while the app is closed require additional design and are not part of the current preview.

実AIによる開発から実GitHubへのPR作成は、専用の管理された検証を行ってから機能として紹介します。公開ホスト型サービス、クラウド同期、アプリ停止中の予約実行は追加設計が必要で、現在のプレビューには含まれません。
