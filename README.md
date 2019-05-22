# Markdown Test

# #標題
# h1
## h2
### h3
#### h4
##### h5
###### h6

Alt-h1 (下面帶1-n個"=",等於# h1)
=
Alt-h2 (下面帶1-n個"-",等於# h2)
--

# #強調
*斜體*, _斜體_  
**粗體**  
~~刪除線~~  

# #清單
1. 第一項  (兩個空格等於換行)
2. 第二項  
4. 第三項  (數字可以不用照順序)  
* 無序次清單 (* ) 
- 無序次清單 (- )
+ 無序次清單 (+ )
    1. 排序次清單  

# #連結設定
[這是一個行內連結](https://www.google.com "google") ("google"->滑鼠移到連結上會顯示的字)  
https://www.google.com

# #圖片
行內格式：
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo 標題文字範例一")  

參考連結格式：
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo 標題文字範例二"  

# #程式代碼與語法高亮標示
 `code` 
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
在開頭的"```"後面加上語言,像: ```javascript
```

```Java 
String s = "Java syntax highlighting";
System.out.println(s);
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

# #表格
冒號（Colons）是用來對齊的（擺左齊左、擺右齊右，都擺就置中）。  
| :擺左等於靠左  | :兩邊都擺等於置中 | :擺右等於靠右  |  沒有:等於靠左 | 
| :------------- |:-----------------:| --------------:|  ------------- |  
| 靠左           | 置中              | 靠右           | 靠左           |
| col 2 is       | centered          |   $12          |                | 
| zebra stripes  | are neat          |    $1          |                |

最外圍的豎線（|）不是絕對需要，在原始文檔中你可以不要太在意美觀。  
你也可以在表格內使用行內格式。
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
 
 # #引言
> 引言（Blockquotes）常常出現在電子郵件中，表示摘錄來信原句並回覆。  
> 這一行是引言的一部分。

Quote break.

> 這是一段非常長的引言區塊，只要在句首使用了正確的符號與空格，你可以持續不間斷的撰寫，整段文字都還是會被包含在引言區塊中。當然你依舊可以在引言區塊中 *使用* **Markdown** 的行內格式標記語法。

# #行內HTML
因為 Markdown 本來就預設要轉換成 HTML 網頁格式，所以你當然可以直接寫入正確的 HTML 代碼，看起來都蠻正常的。（是的，電子書就是一種經過打包的 HTML 網頁組合，很像一個獨立的微型網站。）

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

# #水平分隔線
三個或三個以上的符號，必須在獨立的一行，前後不能有其他文字。

---
短橫線（Hyphens）

***

半形星號（Asterisks）

___

下底線（Underscores）

# #空行分隔段落
習慣或熟悉 Markdown 如何進行分段是很重要的，基本上空行代表前後的文字都會是段落（在 HTML 中以 <p> 與 </p> 包裹起來）。

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

# #youtube影片
雖然你無法直接置入 Youtube 影片，但可以採用圖片連結的模式：  
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

你也可以直接在 Markdown 這樣寫，但會失去尺寸與邊線的設定：  
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)


- [ ] test
- [X] test