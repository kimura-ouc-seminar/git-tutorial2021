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
0. googleドライブ上で、新しくGASプロジェクトを立てる
0. コードをコピペ
0. Slackのアプリを作成し、incoming webhookのURLをコピペ
0. githubのリポジトリでプロジェクトを作成し、そのURLをコピペ
0. デプロイしてURLをコピー
0. リポジトリのSettingから、webhookを作り、`Let me select individual events.`の`project card`にチェックを入れる
0. `Pushes`のチェックは外してよい
0. Payload URLに↑でコピーしたGASのURLをペースト