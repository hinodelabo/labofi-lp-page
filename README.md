# labofi-lp-page

このページはgithub-page用のリポジトリです。

以下のURLにアクセスしたときに表示するページを定義しています。:

https://labofi.com

```
[Client]
↓ HTTPS
[Route 53]
↓
[ALB (HTTPS:443)]
↓ HTTP (9000)
[EC2 t4g.micro (nginx in Docker)]
↓
[GitHub Pages (proxy_pass)]
```
