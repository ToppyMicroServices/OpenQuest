# Development status / 開発状況

**OpenQuest by Toppy · Research Preview · Updated 2026-11-07**

Implemented means code exists in the prototype. Demo or isolated checks use sample data or substitute services. Live checks use a real account and apply only to the specific scenario described. None of these labels implies general availability.

「実装済み」は試作版に処理があることを示します。「デモ・隔離テスト」はサンプルデータや代替サービスによる確認です。「実推論」は実アカウントによる限定的な確認であり、製品全体の品質保証とは区別しています。

| Area / 項目 | Evidence and limit / 確認と限界 |
|---|---|
| Visual scope / 表示方式 | Overhead 2D maps and party-follow camera. Leader-perspective 3D rendering is not available in this preview. 俯瞰2Dと隊への追従カメラ。リーダー視点の3D表示は未提供。 |
| Town, conversation, result navigation / 街・会話・成果 | Implemented; sample-data browser checks recorded. Two static-renderer demo screenshots captured on 2026-11-07; no backend/live AI used in capture. 実装・サンプル確認記録あり。今回の撮影は静的デモ表示2枚で、実接続の再検証ではない。 |
| Sequential party / 役割順の協働 | Historical live check on 2026-10-15: four roles completed a short calculation task. No tool execution or external messages were tested. 過去の短い計算課題のみ。ツール実行・外部送信は対象外。 |
| Project stages, parallel workers, pause and resume / 工程・並列・相談再開 | Implemented; isolated fixtures exercised the workflow. Real-account quality, quota behavior, and tool choices need more evaluation. 実アカウントでの品質・利用枠・ツール選択は継続検証。 |
| Development to GitHub PR / 開発からPR | Full real-AI-to-real-GitHub path not verified. 実AIから実GitHubへ至る全経路は未検証。 |
| History and persistence / 履歴・保存 | Local storage and explicit history import implemented. Complete backup/restore and cross-device continuity remain validation work. ローカル保存と履歴取り込みは実装済み。全体の復元・端末移行は引き続き確認。 |
| macOS variants / macOS版 | Electron and Tauri implementations exist; a 2026-11-01 Tauri build and isolated checks are recorded. No general-distribution claim. 過去のビルド・隔離試験記録あり。一般配布の品質確認とは区別。 |
| Restored development environment / 復元環境 | 27 selected local checks and browser startup passed. No new real-account inference was performed in that recovery check. 全テストの再実行ではなく、選定27件とブラウザ起動の確認。 |
| Cloud sync, hosted multiuser service / クラウド同期・複数ユーザー | Not implemented / 未実装。 |
| Recurring or app-closed scheduling / 繰り返し・停止中の予約 | Not implemented / 未実装。 |

The concept film communicates the intended experience. Its automatic task generation and arranged world map are not evidence of a completed live integration. See [MEDIA.md](MEDIA.md).

45秒動画は構想を伝えるコンセプト映像です。自動タスク生成や街の配置の演出を、実接続の検証結果として扱わないでください。

The prototype runs locally for one person. Normal conversation and project-development stages have different execution scopes; do not interpret this preview as a claim that the entire application is read-only.

試作版は個人向けのローカルアプリです。通常会話とプロジェクトの開発工程では実行範囲が異なるため、アプリ全体が読み取り専用であるとの説明はしていません。
