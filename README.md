README.md

聲明html文件的格式，感嘆號表示是最新的版本，目前是5
<!DOCTYPE html>

網站的主體
<html></html>

主體的頭，描述網頁的資訊
<head></head>

主體的身體，網頁的內容
<body></body>

標題，Safari瀏覽器的選項卡上會顯示
<title></title>

註解
快捷鍵：CMD + /

Meta標籤，給Google搜索、Facebook決定縮圖等等用的
<head>
    <meta name=”description” content=”略⋯⋯”>
    <meta name=”keywords” content=”略⋯⋯”>
</head>

跳脫字元：例如空格、商標符號、版權符號

css的選擇器：
1.元素選擇器，如 h1 p div
2.ID選擇器，用 # 號，如 #a
3.class選擇器，用 . 如 .b
id在每個頁面中是唯一的，但是class是可以重複的

一次修改多個元素的模式：逗號 ,

只選擇容器中的元素，容器外的不受影響
1.後代選擇器 不使用符號 選擇器 選擇器中的元素
2.子選擇器 使用符號 >
3.鄰居選擇器 使用符號 +

屬性選擇器
例如 span[class]

第一子元素與最後一個子元素，例如：
article p:first-child {

}
article p:last-child {

}

CSS的選擇器的優先級（鼠標懸停時可看到優先級數組，作用範圍越小，越優先）
1.有選擇器權重圖可參考，id選擇器權重最高
2.同權重後者優先；
3.important最高，儘量不要用

偽類，改變元素在特定情況下的行為，例如：鼠標懸停在鏈接上時變為藍色、懸停在列表上時變灰色
a:hover {
    color: blue;
}

偽元素，例如：給列表中的項目添加特定的emoji