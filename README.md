# へごへごへごちん (ブックマークレット版)

これは「[へごへごへごちん](http://www.terabo.net/hegochin/)」のブックマークレットです。
任意のページをへごることができます。

## 使い方

ブラウザでブックマークを作成し、以下のスクリプトをURLに設定してください。
名前は何でも大丈夫です。

```
javascript:(function(){var h=function(s){var r='',d1='がぎぐげござじずぜぞだぢづでどばびぶべぼガギグゲゴザジズゼゾダヂヅデドバビブベボ',d2='かきくけこさしすせそたちつてとはひふへほカキクケコサシスセソタチツテトハヒフヘホ';for(var i=0,l=s.length;i<l;i++){var c=s.substr(i,1);if(c.match(/[がぎぐげござじずぜどだぢづでどばびぶべぼガギグゲゴザジズゼゾダヂヅデドバビブベボ]/)){var idx=d1.indexOf(c);if(idx!=-1)c=d2[idx];}r+=c;if(c.match(/[ぁ-んァ-ン]/))r+='゛';}return r;};document.body.innerHTML=h(document.body.innerHTML);})()
```

![設定画面](https://raw.githubusercontent.com/kotarot/hegochin-bookmarklet/master/assets/setting.png)

こんな感じ。

## 実行例

あとで記述.
