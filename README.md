# galary
網頁說明:
    進入主頁面後，會有所有圖片的預覽圖，滑鼠一道圖片上，會加上邊框，之後下方有三首背景音樂，可自由選擇撥放，預設是不會自己撥放，因為個人覺得進入網頁後突然撥放音樂，會讓我心情很不愉快，所以以個人經驗，背景音樂是預設不會自動撥放的，而若撥放了音樂，音樂是設定為循環撥放，在頁面最下方，有”點此進入輪播頁面”，點擊會進入下一個輪播的頁面。
    在輪播頁面中，上方會有小圖，可知道圖片的順序，下方有一大圖，點擊大圖會自動下載圖片，在大圖下方有按鈕，案”開始輪播”，會把圖片自動輪播，而按下後開始輪播的按鈕會消失，此時按下”停止輪播”，會停止輪播的效果，並且開始輪播的按鈕會再次顯現，按下”下一張”或是”上一張”，圖片會依照按下的按鈕改變，同樣的下方有三首背景音樂可供選擇撥放。

使用的CSS技術說明:
Margin:用於更改內距及外距，排版時使用。
font-weight: bold; 將字體改成粗體(bold=700px)。
background-size: cover; 將背景圖片完全覆蓋整個區域。
text-shadow 調整字體的陰影以及陰影的顏色(我是設為黑色)。 
利用hover，更改按鈕顏色以及圖片。
text-align: center 用於置中。
使用的html技術說明:
<button>: 用於按鈕
<a>: 設定圖片以及download屬性用以下載圖片。
<img>設定圖片。

使用的Javascript技術:
1.
輪播:將圖片放進陣列中，之後用setInterval("sequentialImg()",2000)，將圖片依時間改變，達成輪播的效果。
 2.
停止輪播，利用clearInterval()來達成停止輪播。
3.其他使用的如: getElementById()、innerHTML。
