# Markdown 小教室
以下是 Markdown 的 Cheat Sheet(小抄)，
你可以點擊 __目錄__ 快速到達該內容區塊。

你也可以直接參考《Markdown Here Cheatsheet》，[這裡](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)有一篇英文版教學，學習更多 Markdown 的工具。

## 目錄  

- [標題 Headers](#headers)  
- [重點 Emphasis](#emphasis)  
- [列表 Lists](#lists)  
- [連結 Links](#links)  
- [圖片 Images](#images)  
- [編碼與語法 Code & Syntax](#code) 
- [水平線 Horizon](#hr)

<a name="headers"/>

> ### 標題 (Headers)
_______

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6



<a name="emphasis"/>


> ### 重點 (Emphasis)
_____

```
斜體：在兩邊加上 *星號* 或是 _下劃線_ 。

粗體：在兩邊加上 **兩個星號** 或是 __兩個下劃線__ 。

結合兩者： **星號與 _下劃線_** 結合重點。

刪除線：兩個波浪符號 ~~刪除這個~~
```

斜體：在兩邊加上 *星號* 或是 _下劃線_ 。

粗體：在兩邊加上 **兩個星號** 或是 __兩個下劃線__ 。

結合兩者： **星號與 _下劃線_** 結合重點。

刪除線：兩個波浪符號 ~~刪除這個~~



<a name="lists"/>


> ### 列表 (Lists)
_____

```
1. 第一個有序列表項目
2. 第二個有序列表項目
⋅⋅⋅* 無序子列表會以。符號作為分段
1. 實際數字(1.)不重要，還是會依照同層序列計算(1,2,3,4..)
⋅⋅⋅1.有序子列表會以i符號作為分段
4. 與其他項目

⋅⋅·在列表項目下加入段落，只要縮進就好了。
···注意前面的空白行，以及前置的空白（至少要一個“空白”，不過我們在這裡會使用三個空白以剛好對齊原始的文字）。

⋅⋅⋅要使文字段行而不會成為新的段落，你只需要在後面加上兩個空白。
⋅⋅⋅注意這行已經分開了，不過還是在同樣的段落中。

* 無序列表可以使用 "星號＊"
- 也可以使用 "減號-"
+ 或者是使用 "加號+"
```

1. 第一個有序列表項目
2. 第二個有序列表項目
   * 無序子列表會以 。 符號作為分段
1. 實際數字(1.)不重要，還是會依照同層序列計算(1,2,3,4..)
   1. 有序子列表會以 i 符號作為分段
4. 其他項目(此處的 ··· 表示空格)

   在列表項目下加入段落，只要縮進就好了。
   
   注意前面的空白行，以及前置的空白（至少要一個“空白”，不過我們在這裡會使用三個空白以剛好對齊原始的文字）。

   要使文字段行而不會成為新的段落，你只需要在後面加上兩個空白。
   注意這行已經分開了，不過還是在同樣的段落中。

* 無序列表可以使用 "星號＊"
- 也可以使用 "減號-"
+ 或者是使用 "加號+"

<a name="links"/>


> ### 連結 (Links)
_____

有**兩個方法**可以建立連結

- []()
- []()[1]

```
[這是一個行內樣式的連結](https://www.google.com)

[這是一個加上標題的行內樣式連結](https://www.google.com "Google.com")

[這是一個引用樣式的連結][任意不區分大小寫的文字]

[以相對的文件路徑引用其他文件](../blob/master/LICENSE)

[可以用數字來宣告一個引用樣式的連結][1]

或讓他空白並使用[連結文字本身]。

網址，或是尖括號中的網址會自動轉換成連結。
http://www.example.com 或 <http://www.example.com> 甚至有時候 example.com 也可以（只是舉例，Github上無效）。

引用連結可以在一些文字後面。

[任意不區分大小寫的文字]: https://www.mozilla.org
[1]: http://slashdot.org
[連結文字本身]: http://www.reddit.com
```

[這是一個行內樣式的連結](https://www.google.com)

[這是一個加上標題的行內樣式連結](https://www.google.com "Google.com")

[這是一個引用樣式的連結][任意不區分大小寫的文字]

[以相對的文件路徑引用其他文件](../blob/master/LICENSE)

[可以用數字來宣告一個引用樣式的連結][1]

或讓他空白並使用[連結文字本身]。

網址，或是尖括號中的網址會自動轉換成連結。
http://www.example.com 或 <http://www.example.com> 甚至有時候 example.com 也可以（只是舉例，Github上無效）。

引用連結可以在一些文字後面。

[任意不區分大小寫的文字]: https://www.mozilla.org
[1]: http://slashdot.org
[連結文字本身]: http://www.reddit.com

<a name="images"/>


> ### 圖片 (Image)
_____

```
行內樣式：
![alt 文字](https://i.imgur.com/rt7LJbv.png "游標停留在圖片2秒鐘")

引用樣式: 
![alt 文字][logo]

[logo]: https://i.imgur.com/2tJnUrJ.png "游標停留在圖片2秒鐘"
```

行內樣式：

![alt 文字](https://i.imgur.com/rt7LJbv.png "我是鋼鐵人")

引用樣式: 

![alt 文字][logo]

[logo]: https://i.imgur.com/2tJnUrJ.png "我是蜘蛛人"

<a name="code"/>


> ### 程式碼與語法 (Code & Syntax)
_____

程式碼區塊是 Markdown 規格的一部分，不過 語法highlight 不是。
無論如何，許多色彩生成器如 Github 和 *Markdown Here* ──支援 語法 highlight。
每個色彩生成器支援的程式語言，以及程式語言的名字寫法都不一樣。
*Markdown Here* 支援幾十種語言（以及不一定是真的程式語言，像 diffs 與 HTTP headers）的語法highlight；
要看完整的列表，以及語言的名稱，請見 [highlight.js 的示範頁](http://softwaremaniacs.org/media/soft/highlight/test.html)。


```
行內的 `程式碼` 用 `反引號` 包圍起來。
Inline `code` has `back-ticks around` it.
```

行內的 `程式碼` 用 `反引號` 包圍起來。

程式碼區塊可以用只有三個反引號<code>```</code>的一行圍起來，或是以四個空格縮排。
我建議用三個反引號的方式圍起來 ── 這比較簡單，而且只有這個方式支援語法highlight。

<pre lang="no-highlight"><code>```javascript
var s = "JavaScript Highlight Syntax";
alert(s);
```
 
```python
Language = "Python Highlight Syntax"
print(Language)
```
 
```
沒有指定程式語言，所以沒有語法。
不過，我們可以放進一個 <b>標籤</b>。
```
</code></pre>


```javascript
var s = "JavaScript Highlight Syntax";
alert(s);
```

```python
Language = "Python Highlight Syntax"
print(Language)
```

```
沒有指定程式語言，所以沒有語法。
不過，我們可以放進一個 <b>標籤</b>。
```


<a name="hr"/>

> ## 水平線 (Horizontal)
_____

```
三個或更多 以下符號

連結號

---

星號

***

底線

___
```

三個或更多 以下符號

連結號

---

星號

***

底線

___
