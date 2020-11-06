hexschool1030

## 第三週 - 響應式網頁設計 

> ### RWD 網頁不能出現 x 軸
> ### 先看權重，再看先後

這週二加碼穎旻助教的直播，又打通了一些平常會犯錯的概念，收穫很多，也學會了一些前兩周Adobe XD觀看圖稿的技巧，看老師在講解作業時都感覺很沒問題，但自己在寫作業的時候就整個GG了，雖然都有一直在複習之前影片，但自己寫RWD時還是一直在跑版，code也超級無敵亂七八糟，結果發現自己寫錯斷點992寫到768去，一整個大亂套！邊上班邊直播切版班真心滿累的，自從開課以來，就沒有一天睡飽過，收穫很滿！總之，RWD大魔王還沒打敗，各位一起加油了！


### 本週訓練菜單

* 1.1 做當週關卡作業，吸收當週教授觀念
* 1.3 將本週教授內容寫成[部落格](https://)，以加深程式觀念
* 1.4 自主學習新語法，並寫成筆記 [ jQuery 基礎教學筆記 ](https://codepen.io/viccjiang/pen/wvWxwNd)

~~* 3.1 透過 keybr.com 練習英打，荒廢了好幾天，下周要堅持下去 ! 預計每天都要練習10min~~
* 3.2 刻意練習 emmet 與常見英文命名鍵位 [emmet](https://docs.emmet.io/cheat-sheet/) 


### RWD 觀念釐清 開版相關問題 
* 不會有 1920px 這個尺寸，模擬滿版
* 開版常見尺寸 1000、**1200** 、**1280** 、1440
* UTF-8 防止中文亂碼

### RWD 響應式網頁 環境建立起手式

* viewport 設定 (no.1) 
[no1 範例](https://codepen.io/viccjiang/pen/MWeGGJJ)

``` html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

* CSS media Queries 語法 (no.2)
[no2 範例](https://codepen.io/viccjiang/pen/YzWLLNR)




### 權重覆蓋遊戲

*  HTML 標籤：1 分
* class 選擇器：10 分
* ID 選擇器：100 分
* inline style：1000 分
* !important：10000 分
* 觀念補充 [ 30個你必須記住的CSS選擇器 ](https://code.tutsplus.com/zh-hant/tutorials/the-30-css-selectors-you-must-memorize--net-16048)、[ class 選擇器](https://hackmd.io/5jdU3riiThifRktN9NJSKA?view)

### 寬度與單位配置

* max-width：運用在 圖片與 HTML 標籤上(no.3) [no3 範例](https://codepen.io/viccjiang/pen/rNLvvGz) 
    * width 固定會寫死寬度，會出現X軸
    * max-width，隨螢幕自適應延伸，不會出現X軸
* % 單位的運用 (no.4)、box-sizing 講解 [no4 範例](https://codepen.io/viccjiang/pen/rNLvvGz)
    ```css 
    img{
    max-width:100%;
    height:auto;
    }
    ```
    
    ```css
    *,*:before,*:after{
          box-sizing: border-box
    }
    ```
* max-width 與 % 的運用 (no.5) [no5 範例](https://codepen.io/viccjiang/pen/rNLvvdY)
    * 以父層尺寸當基準，子層設定 %



### 排版細節

* 三欄式33.333%、兩欄式48%、單欄式100%
* 三欄排版 (no.6) [no6 範例](https://codepen.io/viccjiang/pen/LYZmmdg)
* 三欄圖文排版 (no.7) [no7 範例](https://codepen.io/viccjiang/pen/Pozeeeo)
* 完整版型設計(no.8) [no8 範例](https://codepen.io/viccjiang/pen/jOrxxxV)

### RWD 做法
* 改變軸線 row / column 滿版推擠
* 改變寬度 % 較大版型適用
* 不是所有元素都要呈現 可用 `display : none` 
* 手機版可以換圖片 ex : background:url(...1) -> background:url(...2)


### 新手適用的斷點
* pc > pad > mobile
    * 電腦 1200px 三欄式
    * 平板 992px 兩欄式 992~768使用者體驗
    * 手機 767px 單欄式 平板以下都可以吃到樣式 

### 業界常見斷點
* 1200px、992px、768px、375px

### 斷點規劃+大網站設計範例

* PC - 1200px
* iPad - **768px**
* iPad以下 - **767px**
* iPhone 6 Plus - **414px (視專案族群)**
* iPhone 6 - **375px (視專案族群)**
* iPhone 5、SE - **320px**

### 本週小節
* 老師建議 先做section->rwd->section->rwd 區塊區塊的做
* 新手可先做FAQ、部落格
* 先練習 pc、992px、767px


### 第三週主線任務

* [第三週 - 眼鏡形象網站](https://viccjiang.github.io/weblayout_1030_hw03/)
* [code review](https://github.com/viccjiang/weblayout_1030_hw03)






