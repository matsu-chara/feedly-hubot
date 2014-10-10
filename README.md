# feedlyBot
`hubot feed`でfeedlyから未読フィードを取ってきてhubotがしゃべるよ( ⁰⊖⁰)

## 準備
1. feedly_access_token.txtという名前のファイルにfeedlyのアクセストークンを保存(r,wの権限が必要)
1. 以下の環境変数を保存

```sh
# hubot
export HUBOT_NAME=""

# feedly
export FEEDLY_REFRESH_TOKEN=""
export FEEDLY_CLIENT_ID=""
export FEEDLY_CLIENT_SECRET=""

## 以下アダプターごとのoption

# hubot-twitter
# export HUBOT_TWITTER_KEY="" # 定義すると140字短縮モードになります
# export HUBOT_TWITTER_SECRET=""
# export HUBOT_TWITTER_TOKEN=""
# export HUBOT_TWITTER_TOKEN_SECRET=""

# bitly(twitter用)
# export BITLY_ACCESS_TOKEN=""

# slack
# expoert HUBOT_SLACK_TOKEN=""
# expoert HUBOT_SLACK_TEAM=""
# expoert HUBOT_SLACK_BOTNAME="$HUBOT_NAME"
```
