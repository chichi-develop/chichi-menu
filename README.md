# chichi-menu

## DNSの設定

```
# マニュアル
www.example.com.              3592    IN      CNAME   YOUR-USERNAME.github.io.
```

```
# 追加レコード
www3.chichi.co.jp.            3592    IN      CNAME   CNAME chichi-develop.github.io.
```

## GitHubの設定

- Settings => GitHub Pages => Custom domain : www3.chichi.co.jp
- Settings => GitHub Pages => Custom domain => Enforce HTTPS : True

## URL

- https://chichi-develop.github.io/chichi-menu/
- https://www3.chichi.co.jp/chichi-menu/

## 参考ページ
- http://dotnsf.blog.jp/archives/1070857656.html
