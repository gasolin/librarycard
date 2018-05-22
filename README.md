# librarycard
台北市立圖書館 圖書證/條碼 產生器

## 使用方式

1. 連到 [https://gasolin.github.io/librarycard?id=圖書證號](https://gasolin.github.io/librarycard?id=圖書證號) (參考你手中的圖書證，把網址列中`?id=`後的`圖書證號`改成你真的圖書證號，通常是身份證號後再加2位序號)。

2. 將此網址設為書籤，以便之後再次使用。

3. 如果你覺得這樣很方便，請將以上網址和使用方式分享給你的朋友。

4. 本工具完全開源，且不會紀錄使用者資訊。歡迎前往 https://github.com/gasolin/librarycard 專案查看。


## 條碼刷不出來要怎麼辦？

掃描條碼成功率和手機的黑白對比度有關，使用易反光的螢幕保護貼也會降低掃描成功率。


1. 確定已關閉手機上的`濾藍光`功能
2. 將螢幕亮度調到最高


## 緣起

陸陸續續換了三張借書證，研究了一下發現 [jsBarcode](http://lindell.me/JsBarcode/) 可用來產生圖書證所用的Code39 Barcode，就順手寫了這工具。
