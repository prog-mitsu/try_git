# markdownテンプレート

記法ヘルプ

[文章作成やメモ書きにも便利、Markdown記法](http://kojika17.com/2013/01/starting-markdown.html)  
[Qiita - Markdown記法 チートシート](http://qiita.com/Qiita/items/c686397e4a0f4f11683d)

段落内で改行したい場合は  
行末にスペースを２つ入れます↑

# これはH1タグです
## これはH2タグです
### これはH3タグです
###### これはH6タグです
 **これは太字です**


+ 順序無しリスト１
 - 1-1
 - 1-2
+ 順序無しリスト2
+ 順序無しリスト3

↓罫線です
---

###引用
> 文頭に>を置くことで引用になります。
> 複数行にまたがる場合、改行のたびにこの記号を置く必要があります。
> 引用の上下にはリストと同じく空行がないと正しく表示されません
> 引用の中に別のMarkdownを使用することも可能です。

###画像埋め込み
![Qiita](http://qiita.com/favicon.png "Qiita")

###C++コード ハイライト
```cpp
print("hello\n");
```

###Pythonコード ハイライト
```Python
logging.info("hello")
```

###JavaScriptコード ハイライト
```JavaScript
console.log("hello");
```

###テーブル
| Left align | Right align | Center align 
            |:-----------|------------:|:------------:|
            | This       |        This |     This     
            | column     |      column |    column    |
            | will       |        will |     will     |
            | be         |          be |      be      |
            | left       |       right |    center    |
            | aligned    |     aligned |   aligned    |
            



