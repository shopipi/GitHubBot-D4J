# GitHub+ BOT for Discord
- 💬 コミットメッセージと更新があったファイル名を表示します。
- 🤐 プライベートレポジトリ対応。

![GitHubPlus_Screenshot.png](https://raw.githubusercontent.com/shopipi/GitHubPlus/main/GitHubPlus_Screenshot.png)

## 使い方
- Webhookを設定
- [Discord4J](https://www.javadoc.io/doc/com.discord4j/Discord4J/2.10.1/index.html)を使用
- [`sendChannelId`](https://github.com/shopipi/GitHubPlus/blob/main/src/com.github.shopipi.githubplus/Main.java#L17)でチャンネルIDを指定 ([Main.java](https://github.com/shopipi/GitHubPlus/blob/main/src/com.github.shopipi.githubplus/Main.java))
- [`GitHubAPI`](https://github.com/shopipi/GitHubPlus/blob/main/src/com.github.shopipi.githubplus/GitHubMessageListener.java#L68)でパーソナルアクセストークン、Owner名、repo名、branch名を指定 ([GitHubMessageListener.java](https://github.com/shopipi/GitHubPlus/blob/main/src/com.github.shopipi.githubplus/GitHubMessageListener.java))
- Webhookを設定したサーバーとBOTのログを出すサーバーの両方にBOTを入れる
