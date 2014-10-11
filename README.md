# feedly-hubot

* cronで2分に一回未読フィードを垂れ流し
* `hubot feed`でfeedlyから未読フィードを取ってきてhubotがしゃべるよ( ⁰⊖⁰)

## 準備

* feedly_access_token.txtという名前のファイルにfeedlyのアクセストークンを保存(r,wの権限が必要)

* 以下の環境変数を保存

```sh
# feedly
export FEEDLY_REFRESH_TOKEN=""
export FEEDLY_CLIENT_ID=""
export FEEDLY_CLIENT_SECRET=""

## 以下アダプターごとのoption
# hubot-shell
# export HUBOT_NAME="hubot"
# export HUBOT_ROOM_NAME="Shell"

# hubot-twitter-userstream
# export HUBOT_NAME="hubot"
# export HUBOT_ROOM_NAME="Twitter"
# export BITLY_ACCESS_TOKEN=""
# export HUBOT_TWITTER_KEY="" # 定義すると140字短縮モードになります
# export HUBOT_TWITTER_SECRET=""
# export HUBOT_TWITTER_TOKEN=""
# export HUBOT_TWITTER_TOKEN_SECRET=""

# slack
# export HUBOT_NAME="hubot"
# export HUBOT_ROOM_NAME="#general"
# expoert HUBOT_SLACK_TOKEN=""
# expoert HUBOT_SLACK_TEAM=""
# expoert HUBOT_SLACK_BOTNAME="$HUBOT_NAME"
```

* bin/hubot -a {adopter name}で受付開始
