# WebViewSample

# WebViewのドキュメント
https://developer.android.com/guide/webapps?hl=ja


# 実装手順
1. マニフェストにTCPIPを使うことを宣言 [マニフェスト](https://github.com/chiaki1990/WebViewSample/blob/master/app/src/main/AndroidManifest.xml)
1. レイアウトファイルにWebViewを配置 [レイアウトファイル](https://github.com/chiaki1990/WebViewSample/blob/master/app/src/main/java/com/sample/webviewsample/WebViewActivity.kt)
1. ActivityでWebView.loadUrl()を実行 [アクティビティ](https://github.com/chiaki1990/WebViewSample/blob/master/app/src/main/java/com/sample/webviewsample/WebViewActivity.kt)


### 補足
1. WebViewはデフォルトでjavascriptが作動しない。作動させるには**webView.settings.javaScriptEnabled = true**を使う。
1. WebView内のリンクをクリックするとデフォルトでブラウザアプリが起動する。リンククリック後もWebViewを継続する場合には設定が必要。
