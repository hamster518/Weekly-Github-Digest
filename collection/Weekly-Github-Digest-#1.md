## Weekly-Github-Digest #1
> 2017/08/31 - 2017/09/06

#### Web - 網路本身高風險，請詳閱公開說明書
- [bemusic/bemuse](https://github.com/bemusic/bemuse)  ⬤▗▚▚▚ Web-based online rhythm action game. Based on HTML5 technologies, React, Redux and Pixi.js.
  > 應該蠻多人去過電子遊樂場玩過類似像 BEAT 的機台，沒什麼節奏感的人像筆者一下子就 GG。該專案是使用 React 搭配 Pixi.js 技術開發的網頁版節奏遊戲，各種設定和配置都做的相當到位，包含鍵盤模式，預設歌單和自訂清單，還提供手把手教學，下班後就別寫 code 了，玩一波之後再來研究它的原始碼吧～
  <p align="center">
    <a target="_blank" href="https://github.com/bemusic/bemuse"><img alt="bemuse" src="https://i.imgur.com/Vfd9mTI.png"></a>
  </p>
- [tholman/elevator.js](https://github.com/tholman/elevator.js)  Finally, a "back to top" button that behaves like a real elevator.
  > 雖然是兩年多前的專案了，但沒差啊！就是因為可以把 old school 的 Go Top 玩出新花樣才讓 Web 顯得有趣而吸引人啊。
  <p align="center">
    <a target="_blank" href="https://github.com/tholman/elevator.js"><img alt="elevatorjs" src="https://i.imgur.com/VGSsqjZ.png"></a>
  </p>
---

#### Terminal - 已經是 iTerm 的形狀了呢
- [warner/magic-wormhole](https://github.com/warner/magic-wormhole)  get things from one computer to another, safely
  > 前幾天和同事拿一個設計師給的 Sketch 檔，原本想說用 AirDrop 直接丟最方便，結果卻變成我找到他他找不到我，東西丟不過來想罷工啊，既然 AirDrop 在鬧脾氣就乾脆在 Github 上找找有無替代方案，然後就很神奇的找到這個連名字都很神奇的蟲洞。

  已經習慣 Mac 的開發者大可以直接使用 homebrew 安裝：
  ```shell
  $ brew install magic-wormhole
  ```
  安裝完成之後就是重頭戲了，今天 Alice 要傳送 README.md 給 Bob，Alice 先這樣打：

  ```shell
  $ wormhole send README.md
  ```
  蟲洞會自動產生一組隨機的金鑰，交給 Bob 吧！接著 Bob 需要以下的指令：
  ```shell
  $ wormhole receive
  ```
  就這樣整個很 Geek Style 的搞定了，不過該作法的大前提是雙方都必須先行安裝蟲洞。

---

#### Useful OSS - 好用的開源軟體

- [hackmdio/hackmd](https://github.com/hackmdio/hackmd)  Realtime collaborative markdown notes on all platforms.
  > 臺灣人開發的 Markdown Editor，除了提供即時協作，還支援了學術圖表製作以及實用的投影簡報模式，到後來連[五線譜](https://hackmd.io/features#abc)都可以撰寫，太多讓人眼睛一亮的 features 讓每次的使用都是種享受。
  <p align="center">
    <a target="_blank" href="https://github.com/hackmdio/hackmd"><img alt="hackmd" src="https://i.imgur.com/hLDaibK.png">       </a>
  </p>
---

#### Developers - 開發者們

- [Tim Holman](https://github.com/tholman)  Tinkerer, tuner & tamperer. Conference comedic relief.
  > 在 Codepen 工作的其中一位核心開發者，他的開源作品都相當有梗，本期介紹的 elevator 就出自於這位玩家。

---

#### Technical Posts - 你都去哪看技術文啊城武

- [cssmagic/blog](https://github.com/cssmagic/blog/issues)  CSS魔法 - 博客
  > 多數的文章主題較為偏向 CSS 和前端建構工具，但也有[不少](https://github.com/cssmagic/blog/issues/23)值得一看的翻譯文。

---

#### You Need Some Music, And A Bottle of Dry Martini - 你一定要把氣氛搞得這麼銷魂嗎
- [Aimer - Hoshi no Kieta Yoru ni ~ Live](https://www.youtube.com/watch?v=-gllAwK15rQ)
  > 靈魂歌姬 Aimer 去年有來臺灣表演，當時還在軍中的筆者趁著短暫的休假請朋友去全家搶早鳥票，畢竟沒手機用也不知道有沒有搶到，想說週末放假等好消息。超爽的該週還全連么八。結果上車一開手機訊息就發現朋友搶票晚了五分鐘去，然後就沒了。
  <p align="center"> 
    <a href="https://www.youtube.com/watch?v=-gllAwK15rQ">
      <img src="https://i.imgur.com/E6Y1rf0.png" alt="Video Demo" />
    </a>
  </p>


---
> [關於作者](https://goo.gl/1pnqEk)

> [回到首頁](https://git.io/v5wk4)
