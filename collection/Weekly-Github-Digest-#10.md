## Weekly-Github-Digest #10
> 2017/11/02 - 2017/11/08

#### Web - 網路本身高風險，請詳閱公開說明書
- [nothing-private](https://github.com/gautamkrishnar/nothing-private)  Using private browsing or icongito, Do you think you are safe?. 😄 👿 This will prove you, you're wrong
  
  > 開瀏覽器分頁對大多數人來說是再平常不過的事情了，相關的歷史記錄有的人會定時清理，怕留下把柄被別人知道，尤其是 porn 等 NSFW 的瀏覽記錄，基於隱私性層面，打開無痕視窗瀏覽似乎變成看片的首選，但所謂的 incognito mode 真的夠隱匿嗎？ Chrome 在背後替你偷偷做了什麼事情你真的清楚嗎？ 沒有絕對安全的系統，同樣也沒有絕對隱匿的瀏覽器 (including Tor)。
  <p align="center">
    <a target="_blank" href="https://github.com/gautamkrishnar/nothing-private"><img alt="nothing-private" src="https://camo.githubusercontent.com/773a3f5358099e62bc8c7d8e6030377874b3a44c/68747470733a2f2f7072697661746562726f7773696e676d797468732e636f6d2f696d616765732f696d2d612d666c6f7765722d646f672e6a7067"></a>
  </p>
  
- [iRaul/awesome-portfolios](https://github.com/iRaul/awesome-portfolios)  🎨 A curated list of Awesome Creative Portfolios
  > 滿山滿谷的 portfolios，收集了非常大量的作品集網站，而網站本身也製作的相當華麗，色調使用上極為鮮豔奪目，搜尋，Go Top 等功能運作上也十分到位，靈感困頓時不妨多逛逛多刺激一下。
  <p align="center">
    <a target="_blank" href="https://github.com/iRaul/awesome-portfolios"><img alt="awesome-portfolios" src="https://i.imgur.com/R5zxn0X.png"></a>
  </p>
---

#### Terminal - 已經是 iTerm 的形狀了呢
- [xxhomey19/nba-go](https://github.com/xxhomey19/nba-go)  🏀 💻 The finest NBA CLI
  <p align="center">
    <a target="_blank" href="https://github.com/xxhomey19/nba-go"><img alt="nba-go" src="https://user-images.githubusercontent.com/12113222/32413609-ea673d3e-c24f-11e7-935b-0a2a86be0ee2.png"></a>
  </p>
  
  > CLI 相關的應用除了帶點 hacker 的氣息以外，最吸引人的無非是其快捷性，易用性以及介面夠低調，尤其是當你還在上班的時候心血來潮想看到勇士隊和馬刺隊的實況比分，大辣辣的直接開啟網頁未免過於張揚，這一週介紹的 CLI 工具 nba-go 正是因為這項需求應運而生：

  簡單的全域安裝：
  ```shell
  $ npm install -g nba-go
  ```
  好了，沒了，步驟就這麼簡單，接著可以開始試試功能，觀看特定日期的球賽一覽表：
  ```shell
  $ nba-go game -d 2017/11/02
  ```
  <p align="center">
    <a target="_blank" href="https://github.com/xxhomey19/nba-go"><img alt="nba-go" src="https://user-images.githubusercontent.com/12113222/32413795-0e7d75c2-c254-11e7-8a77-eeabed3c11f2.gif"></a>
  </p>
  
  也可以查看特定球員的相關數據資料：
  ```shell
  $ nba-go player Curry -i
  ```  
  <p align="center">
    <a target="_blank" href="https://github.com/xxhomey19/nba-go"><img alt="nba-go" src="https://user-images.githubusercontent.com/12113222/32416941-7cfc49e6-c28c-11e7-8a79-15601a44554e.gif"></a>
  </p>
  
  最屌的殺手鐧功能就屬 live scores 這項了：
  
  <p align="center">
    <a target="_blank" href="https://github.com/xxhomey19/nba-go"><img alt="nba-go" src="https://user-images.githubusercontent.com/12113222/32420915-3ca6b34a-c2cd-11e7-904d-bf41cc4b93f7.gif"></a>
  </p>
  
  撰寫該工具的作者也有專文簡單介紹了背後開發的 [心路歷程](https://medium.com/@xxhomey19/github-%E5%A6%82%E4%BD%95%E7%B6%93%E7%87%9F-side-project-%E6%8B%BF%E5%88%B0-1k-%E9%A1%86%E6%98%9F%E6%98%9F-974b8d170436)，不妨多花點時間看看吧～
  
---

#### Useful OSS - 好用的開源軟體

- [Cafe Nomad：咖啡廳遊牧民族](https://cafenomad.tw/)  出沒在不同咖啡廳，找地方工作、看書、喝咖啡的人們。

  > 這幾年國內出現了不少所謂的 Digital Nomad，也就是數位遊牧民族，憑藉著自身的一技之長，自由的在任何地點任何國家做著 remote 性質的工作，其實國外類似的風氣已經有好一陣子了。這份清單整理出各種不同的咖啡廳，不論是想找地方工作、看書、或是喝咖啡都是個很棒的參考工具。
  <p align="center">
    <a target="_blank" href="https://cafenomad.tw/"><img alt="cafenomad" src="https://i.imgur.com/TjKxZTU.png"></a>
  </p>
---

#### Developers - 開發者們

- [mqyqingfeng](https://github.com/mqyqingfeng)
  
  > mqyqingfeng 是位來自中國的開發者，在掘金上的 po 文相當活躍，內容質量兼具，常常會有一系列研究原理且相當深入的專題文章，JavaScript 的運作模式相信很多人包含筆者在內都還是停留在一知半解的程度，情境往往是這樣，工作上的專案需求分配下來了，敲敲打打拼拼湊湊也的確弄出了個能動的東西，但心中不免質疑自己是真的懂還是只是一個擅長工具的匠人。最近和之前實習的同事聊天，某種程度好像被點醒一些事實，如果永遠抱持著這樣得過且過的心態，總是淺嘗輒止，不去思考原理實作，那一年之後你還是那個只會用別人工具的人，而你忘了其實自己也是有能力可以打造工具的。

---

#### Technical Posts - 你都去哪看技術文啊城武

- [oxxostudio](http://www.oxxostudio.tw/)
  
  > 做前端應用往往是 CSS 和 JavaScript 一併使用，更不用說現在流行的前端框架更能協助你用 JavaScript 去撰寫 CSS 的語法糖，很少有人會去做關於 Pure CSS 的探討和運作機制，這個部落格的作者撰寫了非常大量的分享文，可以看到一些有趣的特效，一點進去看發現竟然可以完全只用 CSS 實作出來，讚嘆之餘也可以複習或是培養自己對於排版和美感上的掌握程度。

---

#### You Need Some Music, And A Bottle of Dry Martini - 你一定要把氣氛搞得這麼銷魂嗎
- [Toe - Two Moons](https://www.youtube.com/watch?v=lACSvDOLhLU)
  
  > 已經是第二回在 Weekly-Github-Digest 推薦 Toe 這樂團的歌曲了，無奈這陣子光是公司的事情忙到快翻過去，除了處理一大堆雜事和鳥事，內心也開始多了不少懷疑的聲音，不曉得自己當初選擇回南部工作的決定是否正確，心煩意亂之時不太想聽到人聲，寧願雙耳只有穩重的 beats 和鼓聲充斥其中。
  <p align="center"> 
    <a href="https://www.youtube.com/watch?v=lACSvDOLhLU">
      <img src="https://i.imgur.com/ZJtow5G.jpg" alt="Video Demo" />
    </a>
  </p>


---
> [關於作者](https://goo.gl/1pnqEk)

> [回到首頁](https://git.io/v5wk4)
