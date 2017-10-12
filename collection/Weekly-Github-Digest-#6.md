## Weekly-Github-Digest #6
> 2017/10/05 - 2017/10/11

#### Web - 網路本身高風險，請詳閱公開說明書
- [CodeTengu/jokekappa](https://github.com/CodeTengu/jokekappa)  A library for delivering one-line programming jokes
  
  > 如同簡介所說的，為軟體工程師提供了一則隨機笑話，可以很方便的在 terminal 直接開啟也可以選擇在 python 檔案中使用。靠北工程師的笑話近期都沒以前有笑點，大概是筆者慧根太差了。
  <p align="center">
    <a target="_blank" href="https://github.com/CodeTengu/jokekappa"><img alt="jokekappa" src="https://i.imgur.com/WcBjYdb.png"></a>
  </p>
  
- [egoist/evangelion-card](https://github.com/egoist/evangelion-card)  Generate Evangelion title card like a boss 😎
  > 動漫迷心目中的經典神作：新世紀福音戰士，現在也有開發者做出圖文產生器啦～整體核心不意外的是用 canvas 實作而成，使用者可以修改標題內文和字體字型，算是相當高度客製化。 
  <p align="center">
    <a target="_blank" href="https://github.com/egoist/evangelion-card"><img alt="evangelion-card" src="https://i.imgur.com/AHoH4FE.png"></a>
  </p>
---

#### Terminal - 已經是 iTerm 的形狀了呢
- [WeiChiaChang/regular-show](https://github.com/WeiChiaChang/regular-show)  🎮 Get random name of Regular Show
  <p align="center">
    <a target="_blank" href="https://github.com/WeiChiaChang/regular-show"><img alt="regular-show" src="https://i.imgur.com/WBuT5e3.jpg"></a>
  </p>
  
  > 毛遂自薦一下，國慶連假休息了整整四天整個放的很累，同時也覺得自己耍廢太久了便決定做點簡單好玩的 side project，想起前陣子結束的 Regular Show，除了劇情天馬行空腦洞大開很合筆者胃口以外，同時在筆者心中還有份格外獨特的意義，至於是什麼不是這期的重點，先來看看怎麼使用這個假名產生器吧：

  選擇全域安裝：
  ```shell
  $ npm i regular-show -g
  ```
  也可以選擇只在部分檔案中引用：
  ```shell
  $ npm i --save regular-show
  ```
  簡單的引入便會產生隨機的 Regular Show 人物名字：
  ```javascript
  var regularShow = require('regular-show');  // Conventional but classic way
  import regularShow from 'regular-show';     // Or much more modern ES6  way

  regularShow();
  // Mordecai
  
  regularShow.words;
  // ['Mordecai', 'Rigby', ...]
  ```
  
  某種程度算是和 Regular Show 這部卡通做個象徵性的紀念，不管從過去到現在依然是很棒的回憶。

---

#### Useful OSS - 好用的開源軟體

- [wulkano/kap](https://github.com/wulkano/kap)  An open-source screen recorder built with web technology

  > 必須說 Mac 自帶的 QuickTime Player 本身的功能已經極為強大，足以應付筆者平日會用到的大部分需求，但對於 Open Source 來說，如果有個同樣好用且開源的工具勢必能讓更多開發者對於內部實作一窺究竟，就像很多人平常辦公會使用的 Slack，對於一位有著足夠好奇心的工程師或多或少還是會去思考背後機制如何運作，所以社群也有熱心的開發者跳出來做了 [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat) ，能夠有幸待在軟體這產業真的是太棒了。
  <p align="center">
    <a target="_blank" href="https://github.com/wulkano/kap"><img alt="kap" src="https://i.imgur.com/a5xKS8L.png"></a>
  </p>
---

#### Developers - 開發者們

- [OA Wu](https://github.com/comdan66)  先寫別人會寫而不想寫的程式，以後才可以寫別人想寫而寫不出來的程式
  
  > 筆者非常敬佩的一位開發者，臉書相關社群亦或是批踢踢常常看到 OA Wu 大的身影，對於技術推廣與分享不遺餘力，技術涵蓋層面相當廣泛，包含網頁切版和一些工具自幹甚至都有質量兼具的直播影片提供，但讓筆者印象最為深刻的還是 [北港迎媽祖](https://www.ioa.tw/article/55-2016%20%E5%8C%97%E6%B8%AF%E8%BF%8E%E5%AA%BD%E7%A5%96.html) 這個專案，能夠為自己的家鄉付出心力做點事，把專業能力運用在當地文化做深刻結合，這也是筆者未來要努力的方向。

---

#### Technical Posts - 你都去哪看技術文啊城武

- [掘金](https://juejin.im/timeline)
  
  > 前次介紹了阮一峰，這次推薦的是掘金社群，他們在 Github 上的翻譯計劃目前看來運轉的還不錯，各類型的文章包含常見的前端後端等分類都有收錄，看得出有在用心經營。

---

#### You Need Some Music, And A Bottle of Dry Martini - 你一定要把氣氛搞得這麼銷魂嗎
- [Girls’ Generation - Into The New World](https://www.youtube.com/watch?v=0k2Zzkw_-0I)
  
  > 雖然沒怎麼聽韓文歌，但當初會喜歡少女時代大概是因為這首歌和 Genie 吧，也是少數幾個全部名字都叫得出來的女團，前幾天徐玄，Tiffany 和秀英合約期滿而離團無疑又是枚震撼彈，不曉得當中有無其他原因，但三人目前看來都有明確的道路要走，過去的九人團隊現在僅剩五人支撐，感嘆之餘也在思考著下個接棒的女團會不會是 Twice。
  <p align="center"> 
    <a href="https://www.youtube.com/watch?v=0k2Zzkw_-0I">
      <img src="https://i.imgur.com/v4rTuBX.jpg" alt="Video Demo" />
    </a>
  </p>


---
> [關於作者](https://goo.gl/1pnqEk)

> [回到首頁](https://git.io/v5wk4)
