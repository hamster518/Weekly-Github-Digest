## Weekly-Github-Digest #8
> 2017/10/19 - 2017/10/25

#### Web - 網路本身高風險，請詳閱公開說明書
- [dtinth/atom-aesthetic-ui](https://github.com/dtinth/atom-aesthetic-ui)  Ａｎ　ＡＥＳＴＨＥＴＩＣ　ＵＩ　tｈｅｍｅ　ｆｏｒ　Ａｔｏｍ．
  
  > 不久前好像才推薦過調整 Github 背景色以保護眼睛的 plugin，這次來個腦洞大開。這套特別針對 Atom 編輯器的外掛一裝上立馬讓你回到復古風滿出來的 Windows 美好年代，整個主題和樣式一次到位，不管是分頁標籤或是按鈕甚至是那條經典的藍色帶狀漸層都有水準之上的完美呈現，既復刻又大方，短期內很難找到更為出色的作品了。是說 project 名稱叫 aesthetic 是為了營造某種衝突美感嗎ＸＤ
  <p align="center">
    <a target="_blank" href="https://github.com/dtinth/atom-aesthetic-ui"><img alt="atom-aesthetic-ui" src="https://camo.githubusercontent.com/729adbef4e35abd35e5a2ba894c35d3dbc35467b/687474703a2f2f692e696d6775722e636f6d2f3435354132696d2e706e67"></a>
  </p>
  
- [andrew/first-pr](https://github.com/andrew/first-pr)  :octocat: What was the first pull request you sent on GitHub? 
  > 這幾天為了響應 Hacktoberfest 活動所寫的 awesome-singer-official-portal 意外收到了爆炸多的 pull request，真的是解到手軟，不過這機會因為本身很難得所以過程倒是也相當享受，然後也開始回想過去的自己是怎麼發出第一個 PR 的呢？有 Git 在就等於有著一台可以穿越時空的時光機，first-pr 這個工具將帶你回顧人生發 PR 的初體驗。原本以為自己的更久以前呢，結果竟然也才一年半之前＠＠
  <p align="center">
    <a target="_blank" href="https://github.com/andrew/first-pr"><img alt="first-pr" src="https://i.imgur.com/VX7HLZs.png"></a>
  </p>
---

#### Terminal - 已經是 iTerm 的形狀了呢
- [SamVerschueren/dev-time-cli](https://github.com/SamVerschueren/dev-time-cli)  Get the current local time of a GitHub user
  <p align="center">
    <a target="_blank" href="https://github.com/SamVerschueren/dev-time-cli"><img alt="dev-time-cli" src="https://github.com/SamVerschueren/dev-time-cli/raw/master/screenshot.gif"></a>
  </p>
  
  > 大部分開發者應該或多或少都有對別人專案感到興趣而進一步發送 Pull Request 的經驗吧，送過去的時候總期待著趕快被 merge，短的可能幾分鐘就有回應了，但由於是開源專案，很可能等了又等還是沒有消息，這次介紹的工具某種程度可以幫助你 check 一下該專案的開發者時區，然後你就可以進一步推測對方是否在睡覺ＸＤ：

  選擇全域安裝：
  ```shell
  $ npm install --global dev-time-cli
  ```
  幾秒不到就ＯＫ真的是簡單到不行，指令也相當好記，試著在 terminal 打：
  ```shell
  $ dev-time --help
  ```
  秀出了 help 相關的資訊和選項，馬上來試試大神睡了沒：
  ```shell
  $ dev-time tj
  05:59 - 24 Oct. 2017
  ```
  嗯...這麼早到底起床了沒有呢？？
  你也可以同時查看兩位以上的開發者：
  ```shell
  $ dev-time tj weichiachang -v
  tj
  08:03 - 24 Oct. 2017 - UTC-7
  weichiachang
  23:03 - 24 Oct. 2017 - UTC+8
  ```
  跟大神的時區差了好幾個小時啊，這時突然想到同事不久前的幹話：
  
  "當你在睡覺時，美國人還在努力工作啊！"
  
  嗯，你真的是他媽的幹話王耶。
  
---

#### Useful OSS - 好用的開源軟體

- [itmeo/webgradients](https://github.com/itmeo/webgradients)  A curated collection of splendid gradients made in CSS3, .sketch and .PSD formats

  > 前端工程就像是一座橋樑，介於後端和設計之間，也同時負責著兩者之間的協調與溝通，對於美感或是色彩也必須有著相對突出的感受和敏銳度。這個開源好工具除了可以幫助你在漸層色上的選擇以外，也能夠培養對顏色的感覺，畢竟每種色碼都有各自適合的情境和用途，在對的場景使用對的色調才能使產品特別亮眼。很棒的是，這份指南也很大方的同時提供了 PSD 和 Sketch 兩種檔案，於設計師也是一大福音。
  <p align="center">
    <a target="_blank" href="https://github.com/itmeo/webgradients"><img alt="webgradients" src="https://i.imgur.com/Q8MNGcL.png"></a>
  </p>
---

#### Developers - 開發者們

- [jserv](https://github.com/jserv)
  
  > 在台灣談到作業系統領域的大師，提到 jserv 的名號絕對沒有人不曉得，筆者因為不是讀 CS 本科出身，一直到某次無意間在 Youtube 觀看 COSCUP 過去分享的影片才發覺這如同神一般的存在，但最為印象深刻的就屬[黑暗中飛翔的程式碼](https://www.youtube.com/watch?v=olo1vmMgExM)這段演講，既然大家都在不間斷的努力，那筆者自己也沒特別厲害又憑什麼停下腳步？之後再工作面臨低潮時都會不時提醒自己回過頭來充電。

---

#### Technical Posts - 你都去哪看技術文啊城武

- [Codrops](https://tympanus.net/codrops/)  Useful resources and inspiration for creative minds
  
  > 就像其中一個 Tab 的標題一樣，Codrops 就像是一個大型的 Playground，提供了非常豐富的資源，深度教學 tutorial 加上定期的 Collective 集錦，取向幾乎都是前端相關的素材，在這裡閒逛幾乎每次瀏覽都可以挖到寶，此外 CSS Reference 這份類似 Cheatsheet 的文件也相當實用，圖文並茂的互動式引導就算是新手也能很快掌握到該屬性的使用要領。不過 Playground 和 Blueprint 的類型還是有所差異，前者整理了實驗性質較為濃厚的嘗試，後者的重點在於 component 等元件的展示，學習時可以多去留意一下。

---

#### You Need Some Music, And A Bottle of Dry Martini - 你一定要把氣氛搞得這麼銷魂嗎
- [WEDNESDAY CAMPANELLA - Medusa](https://www.youtube.com/watch?v=V5fO-WXd9W8)
  
  > 前幾個禮拜特地花了特休的扣打，搭了四個小時的車北上，再次拜訪了前年聽 Sakanction 演唱會的 Legacy Taipei，不過這回朝聖的是 Wednesday Campanella，如果喜歡 EDM 那種有點ㄎㄧㄤ帶點迷幻的 rhyme，KOM_I 獨特的表演風格你絕對會立馬愛上。其實會場空間不能算是特別大，沒有劃位整場都是站位，筆者很幸運的擠到了前兩排的搖滾區，也不意外的被左右兩旁不認識的歌迷撞來撞去，但最讓人感到驚豔的不僅於此，場地中央設置了可移動式的簡易舞台，中場還有充氣大球直接互動，從台上到台下就算是站最後排的觀眾一樣可以近距離觀賞到演出。如果說 Sakanction 的表演內容是一生必聽且完全值回票價的現場演場會之一，那 Wednesday Campanella 呈現給你的將會是天馬行空且前所未聞的感官體驗。
  <p align="center"> 
    <a href="https://www.youtube.com/watch?v=V5fO-WXd9W8">
      <img src="https://i.imgur.com/Ge42lZY.png" alt="Video Demo" />
    </a>
  </p>


---
> [關於作者](https://goo.gl/1pnqEk)

> [回到首頁](https://git.io/v5wk4)
