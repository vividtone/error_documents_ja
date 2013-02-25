# error_documents_ja

HTTPの主要なステータスコード用のエラーページです。Apache標準のものよりも見やすくわかりやすい画面で、エラーの説明が日本語で記述されています。

[HTML5 Boilerplate](http://html5boilerplate.com/) 付属の 404.html をもとに作成しました。


## 設定例(Apache)

```
ErrorDocument 401 /error_documents_ja/401.html
ErrorDocument 403 /error_documents_ja/403.html
ErrorDocument 404 /error_documents_ja/404.html
ErrorDocument 500 /error_documents_ja/500.html
ErrorDocument 502 /error_documents_ja/502.html
ErrorDocument 503 /error_documents_ja/503.html
ErrorDocument 504 /error_documents_ja/504.html
```
