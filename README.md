# event-reports
カンファレンスや勉強会のレポートまとめ

## gitbook

brew :beer: で入れても良い。  
Dockerでの立ち上げは下記。

```
docker run -v "$PWD:/gitbook" -p 4000:4000 billryan/gitbook gitbook init
docker run --rm -v "$PWD:/gitbook" -p 4000:4000 billryan/gitbook gitbook serve
```