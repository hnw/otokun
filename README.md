# LINE Bot with GAE/Go

https://github.com/k2wanko/appengine-line-bot をベースにしています

## Setup

Get LINE ChannelSecret and AccessToken

https://developers.line.me/messaging-api/getting-started

rename file `line.env.template` to `line.env`

write ChannelSecret and AccessToken to line.env

## Deploy

```
$ goapp deploy -application <projectID> -version <version name>
```

