# git&GitHub勉強会2021
## やること
- GitHubでリポジトリを作る
- クローン
- 共同編集者（コラボレーター）の招待
- コミット&プッシュ
- フェッチ&プル
- github pagesについて
- ブランチ切る
- プルリク
- マージ
- チーム作成
- issue
- Project

## やらないこと
- ローカルでリポジトリ作ってGitHubにアップ
- GitHub Actions
- Fork
- 細かいこと（コミットの取り消しとか、.gitignoreとか、ステージングとか）

# notify-project.gasの使い方
1. googleドライブ上で、新しくGASプロジェクトを立てる
1. コードをコピペ
1. Slackのアプリを作成し、incoming webhookのURLをコピペ
1. githubのリポジトリでプロジェクトを作成し、そのURLをコピペ
1. デプロイしてURLをコピー
1. リポジトリのSettingから、webhookを作り、`Let me select individual events.`の`project card`にチェックを入れる
1. `Pushes`のチェックは外してよい
1. Payload URLに↑でコピーしたGASのURLをペースト
