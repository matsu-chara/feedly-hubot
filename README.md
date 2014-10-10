# feedlyBot
`hubot feed`でfeedlyから未読フィードを取ってきてhubotがしゃべるよ( ⁰⊖⁰)

## 準備
1. feedly_access_token.txtという名前のファイルにfeedlyのアクセストークンを保存(r,wの権限が必要)
1. [scripts/feedly_cmd.coffee中のisTwitter](https://github.com/matsu-chara/feedlyBot/blob/master/scripts/feedly_cmd.coffee#L152)をtwitterを使うかどうかに合わせて変更
1. 以下の環境変数を保存

```sh
# hubot
export HUBOT_NAME=""

# feedly
export FEEDLY_REFRESH_TOKEN=""
export FEEDLY_CLIENT_ID=""
export FEEDLY_CLIENT_SECRET=""

## 以下option

# bitly (twitter用)
export BITLY_ACCESS_TOKEN=""

# twitter
export HUBOT_TWITTER_KEY=""
export HUBOT_TWITTER_SECRET=""
export HUBOT_TWITTER_TOKEN=""
export HUBOT_TWITTER_TOKEN_SECRET=""

# slack
expoert HUBOT_SLACK_TOKEN=""
expoert HUBOT_SLACK_TEAM=""
expoert HUBOT_SLACK_BOTNAME="$HUBOT_NAME"
```
