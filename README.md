# BrowseNowRIP

偉大なるに敬意を。

## What is this?

これは[BrowseNow](https://github.com/kamaboko123/BrowseNow)のブックマークレットオンリー実装です。  
[Twitter公式のシェア用URL](https://twitter.com/intent/tweet)に依存しています。  
サーバなどは不要です。  

## How to use

1. 以下のリンクをブラウザのブックマークバーにドラッグ・アンド・ドロップして、ブックマークとして登録します。  
<a href='javascript: (function (e) { window.open("https://twitter.com/intent/tweet?" + "hashtags=BrowseNowRIP&text=" + e(document.title) + "(" + e(location.href) + ")", null, "width=520,height=500"); })(encodeURIComponent);'>BrowseNowRIP</a>

2. 共有したいページでブックマークをクリックすると、Twitterの投稿フォームに遷移してつぶやくことができます。  
ブラウザでTwitterにログインしていない場合は、遷移先の右上からログインしてください。

*ドラッグ・アンド・ドロップでブックマーク登録できないブラウザの場合
以下をブックマークバーに登録してください。

``` js
javascript: (function (e) { window.open("https://twitter.com/intent/tweet?" + "hashtags=BrowseNowR.I.P&text=" + e(document.title) + "(" + e(location.href) + ")", null, "width=520,height=500"); })(encodeURIComponent);
```

## FAQ

- 推奨ブラウザは？  
最新版のGoogle Chromeです。その他の環境では動作確認していません。

- ソースコードは？


``` js
javascript: (function (e) { window.open("https://twitter.com/intent/tweet?" + "hashtags=BrowseNowR.I.P&text=" + e(document.title) + "(" + e(location.href) + ")", null, "width=520,height=500"); })(encodeURIComponent);
```


Contactの連絡先に質問をください。

## Contact

不具合やお問い合わせは以下にお願いいたします。

- Twitter:いらにか([@happy_packt](https://twitter.com/happy_packet))
- Github Issue：[iranika/BrowseNowRIP](https://github.com/iranika/BrowseNowRIP/issues)
