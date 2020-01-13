## 目錄  

- [標題](#headers)  
- [重點](#emphasis)  
- [列表](#lists)  
- [連結](#links)  
- [圖片](#images)  
- [編碼與語法](#code)  

<a name="headers"/>

> ### 標題 (Headers)

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

> ### 列表


```
1. 第一個有序列表項目
2. 第二個有序列表項目
⋅⋅⋅* 無序子列表 
1. 實際數字不重要，只要它是一個數字
⋅⋅⋅1. 有序子列表
4. 與其他項目

⋅⋅⋅要在列表項目下加入段落，只要縮進就好了。注意前面的空白行，以及前置的空白（至少要一個空白，不過我們在這裡會使用三個空白以剛好對齊原始的文字）。

⋅⋅⋅要使文字段行而不會成為新的段落，你只需要在後面加上兩個空白。⋅⋅
⋅⋅⋅注意這行已經分開了，不過還是在同樣的段落中。
⋅⋅⋅（如果不要求後面的兩個空格，就為伴了典型的 GFM 斷行格式。）

* 無序列表可以使用星號
- 或減號
+ 或加號
```

1. 第一個有序列表項目
2. 第二個有序列表項目
   * 無序子列表 
1. 實際數字不重要，只要它是一個數字
   1. 有序子列表
4. 與其他項目

   要在列表項目下加入段落，只要縮進就好了。注意前面的空白行，以及前置的空白（至少要一個空白，不過我們在這裡會使用三個空白以剛好對齊原始的文字）。

   要使文字段行而不會成為新的段落，你只需要在後面加上兩個空白。  
   注意這行已經分開了，不過還是在同樣的段落中。
   （如果不要求後面的兩個空格，就為伴了典型的 GFM 斷行格式。）

* 無序列表可以使用星號
- 或減號
+ 或加號

<a name="links"/>

> ### 連結 (Links)

有兩個方法可以建立連結

```no-highlight
[這是一個行內樣式的連結](https://www.google.com)

[這是一個加上標題的行內樣式連結](https://www.google.com "Google 的首頁")

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

[這是一個加上標題的行內樣式連結](https://www.google.com "Google 的首頁")

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

```
我最愛的鋼鐵人（把游標指向 Logo 可以看到標題文字）

行內樣式：
![alt 文字](https://複製網址圖便位置連結 "我最愛的鋼鐵人")

引用樣式: 
![alt 文字][logo]

[logo]: https://複製網址圖便位置連結 "Logo 標題文字 2"
```

這是我們的 Logo（把游標指向 Logo 可以看到標題文字）

行內樣式：
![alt 文字](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcThUlMA4VChlN0BsR8hWEjyaJel2iI9JSsAye4JJxY-tSDMNeIJ4g&s "Logo 標題文字 1")

引用樣式: 
![alt 文字][logo]

[logo]: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSyvDV8N0V3if9qw0o8669AoAo8JGTbLCzjaD34UzkKIO6byGJfkQ&s "Logo 標題文字 2"

<a name="code"/>

> ### 程式碼與語法 (Code & Syntax)

程式碼區塊是 Markdown 規格的一部分，不過語法高亮不是。無論如何，許多渲染器──如 Github 和 *Markdown Here* ──支援語法高亮。每個渲染器支援的程式語言，以及程式語言的名字寫法都不一樣。*Markdown Here* 支援幾十種語言（以及不一定是真的程式語言，像 diffs 與 HTTP headers）的語法高亮；要看完整的列表，以及語言的名稱，請見 [highlight.js 的示範頁](http://softwaremaniacs.org/media/soft/highlight/test.html)。


```no-highlight
行內的 `程式碼` 用 `反引號` 包圍起來。
Inline `code` has `back-ticks around` it.
```

行內的 `程式碼` 用 `反引號` 包圍起來。

程式碼區塊可以用只有三個反引號<code>```</code>的一行圍起來，或是以四個空格縮排。我建議用三個反引號的方式圍起來 ── 這比較簡單，而且只有這個方式支援語法高亮。

<pre lang="no-highlight"><code>```javascript
var s = "JavaScript 語法高亮";
alert(s);
```
 
```python
s = "Python 語法高亮"
print s
```
 
```
沒有指定程式語言，所以沒有語法高亮。
不過，我們可以放進一個 <b>標籤</b>。
```
</code></pre>



```javascript
var s = "JavaScript 語法高亮";
alert(s);
```

```python
s = "Python 語法高亮"
print s
```

```
