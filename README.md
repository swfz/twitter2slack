# twitter2slack

AWS lambda managed by apex

twitter to slack functions

## project.json

set `role` to ARN

## update submodule

```
git submodule init
git submodule update
```

### functions/timeline
- set config/default.json

## deploy

```
apex --profile hoge --region ap-northeast-1 deploy
```

## execute

```
apex --profile hoge --region ap-northeast-1 invoke < event.json
```

## show logs

```
apex --profile hoge --region ap-northeast-1 logs -f
```
