# Discord通知用 GitHub Actions



このフォルダには、GitHub Actionsを使用してDiscordへ通知を送信するためのWorkflow（.yml）ファイルが入っています。



##### 初期設定



DiscordとGitHubの設定については、狂犬サーバー内の以下の資料を参照してください。



\\\\10.11.39.148\\Library\\Github通知関連\\DiscordにGithubの通知送信させるには.pptx



##### 通知内容の変更



各.ymlファイルを書き換えることで、Discordへ送信される通知内容を自由に変更できます。



##### ファイル一覧

・notify-discord-on-push.yml

　全ブランチへのPushを通知します。

・notify-discord-on-merge.yml

　マージが行われた際に通知します。

・notify-discord-on-branch-delete.yml

　リモートリポジトリ上のブランチが削除された際に通知します。

・notify-discord-on-branch-create.yml

　リモートリポジトリ上でブランチが作成され、最初のPushが行われた際に通知します。

