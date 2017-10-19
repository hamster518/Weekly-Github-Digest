## Weekly-Github-Digest #7
> 2017/10/12 - 2017/10/18

#### Web - 網路本身高風險，請詳閱公開說明書
- [StylishThemes/GitHub-Dark](https://github.com/StylishThemes/GitHub-Dark)  :octocat: Dark GitHub style
  
  >  做正職工程師不過也快一年，有時明明身體還很有活力，可是眼睛卻痠痛到一個爆炸，可能是久盯螢幕導致眼壓過高，除了在 Mac 上安裝了 f.lux，每天最常瀏覽的 Github 也該適時做點調整了。這項專案把樣式做成了 Chrome Extension，當然也有 Firefox，Safari 和 Opera 這些主流瀏覽器的可供選項，裝上之後會發現色調以深色為主，少掉了不少白黃光的刺激雙眼真的會舒服許多。
  <p align="center">
    <a target="_blank" href="https://github.com/StylishThemes/GitHub-Dark"><img alt="GitHub-Dark" src="https://camo.githubusercontent.com/8cece453b69848fb71c2d1ae5054971d63f70111/68747470733a2f2f7261776769742e636f6d2f5374796c6973685468656d65732f6c6f676f732f6d61737465722f6769746875622e6461726b2f6769746875626461726b2d6d696e692e737667"></a>
  </p>
  
- [borismus/keysocket](https://github.com/borismus/keysocket)  Global keyboard bindings to control your Chrome-based music player
  > 該 repo 的作者雖然很明確的提示並表明不再主動維護此項專案，但還是私心推薦一下，畢竟在做影片切換時非常有用，像是筆者會設定 hot keys 在上一首，下一首和暫停播放鍵，就像切換 iterm 時有快速熱鍵一樣，習慣之後就回不去了。 
  <p align="center">
    <a target="_blank" href="https://github.com/borismus/keysocket"><img alt="keysocket" src="https://i.imgur.com/gGRbWbD.png"></a>
  </p>
---

#### Terminal - 已經是 iTerm 的形狀了呢
- [LazoCoder/Pokemon-Terminal](https://github.com/LazoCoder/Pokemon-Terminal)  Pokemon terminal themes.
  <p align="center">
    <a target="_blank" href="https://github.com/LazoCoder/Pokemon-Terminal"><img alt="pokemon-terminal" src="https://github.com/LazoCoder/Pokemon-Terminal/raw/master/Samples/pikachu.png"></a>
  </p>
  
  > 比起過去十幾年前千篇一律的終端機樣式，今日的開發者有了更多的選擇， 像是 iterm 的高度客製化就滿足了不少工程師的個人品味，這次推薦的是 pokemon 愛好者所撰寫的外掛，非常容易安裝，可以選擇 python 或是 node 方式，此處教學採用後者：

  選擇全域安裝：
  ```shell
  $ npm install --global pokemon-terminal
  ```
  就是這麼簡單，接著試試看在 terminal 打：
  ```shell
  $ pokemon -h
  ```
  展示了 help 相關的選項，然後看到了 `pokemon all` 這個用法：
  ```shell
  $ pokemon all
  ```
  一拖拉庫的神奇寶貝背景都提供了！試試看固拉多吧！
  ```shell
  $ pokemon groudon
  ```
  最後乾脆在每次開啟 iterm 時自動跑這段指令吧～
  <p align="center">
    <a target="_blank" href="https://github.com/LazoCoder/Pokemon-Terminal"><img alt="pokemon-terminal" src="https://github.com/LazoCoder/Pokemon-Terminal/raw/master/Samples/saving.png"></a>
  </p>
  有種成為神奇寶貝大師莫名的興奮感啊！
---

#### Useful OSS - 好用的開源軟體

- [sindresorhus/caprine](https://github.com/sindresorhus/caprine)  Elegant Facebook Messenger desktop app

  > 之前介紹過可以把幾乎任何網站轉成桌面 app 的 [nativefier](https://github.com/jiahaog/nativefier)，這次看到的也是類似的應用，直接幫你把 Facebook Messenger 打包到好，就像是原生的一樣，不過有亮點可能還是在於提供不少客製化的設定，像是 always on top，Keyboard shortcuts 以及新訊息進來的 notifications 等等。
  <p align="center">
    <a target="_blank" href="https://github.com/sindresorhus/caprine"><img alt="caprine" src="https://i.imgur.com/jPkXEXf.png"></a>
  </p>
---

#### Developers - 開發者們

- [Nicky Case](https://github.com/ncase)
  
  > 大多數工程師平日觸及的可能限於工作相關的資訊或是某某新潮技術，如果能夠充分發揮自身能力藉此讓更多人注視更為重要的公眾議題，筆者認為那更接近理想中的價值觀，Nicky Case 就是這樣的一位開發者，作品性質極為廣泛，從之前唐鳳參與翻譯的 [trust](https://github.com/ncase/trust) 到關注同性戀的開源專案 [coming-out-simulator-2014](https://github.com/ncase/coming-out-simulator-2014)，台灣最近也有團隊製作 [出櫃那件小事](https://comingout.simpleinfo.cc/) 顯示出在這個面向上的努力。作品細節處理上可見到不少巧思，值得推薦。

---

#### Technical Posts - 你都去哪看技術文啊城武

- [tutorialzine](https://tutorialzine.com/)  We are a community of talented developers who learn together.
  
  > 不知道算不算是較為小眾的技術文部落格，除了會定期整理一篇關於 JavaScript trending 的框架或是工具，還提供了許多有趣的瀏覽器新功能簡單實作，像是這篇 [Converting from Speech to Text](https://tutorialzine.com/2017/08/converting-from-speech-to-text-with-javascript) 就是把 Speech Recognition API 做了一個輕巧的應用，安利一下，筆者也基於此篇教學改寫成一個叫做 [happy-halloween](https://github.com/WeiChiaChang/happy-halloween) 的萬聖節小外掛，透過說出 "happy halloween" 這個關鍵字就能觸發彩蛋。

---

#### You Need Some Music, And A Bottle of Dry Martini - 你一定要把氣氛搞得這麼銷魂嗎
- [capsule - Sugarless GiRL](https://www.youtube.com/watch?v=x6UurRhIgD0)
  
  > 有在聽日本 EDM 相關的團體，應該對 Perfume 或是卡莉怪妞的曲風都不陌生，隨然自己沒有真正跳下去玩過音樂，不過聽了他們的歌這麼久，不免對樂曲的製作者感到好奇，好奇心驅使之下找了些資料意外的發現，背後的製作人竟然是同一人，[中田康貴](https://www.gooume-jp.com/works/223/zh_TW)。不僅於此，他還自組了一個團體叫做 capsule，歌曲走同樣的風格路線聽起來卻格外有其個人味道。編曲旋律是讓 EDM 洗腦的關鍵，就像這首 Sugarless GiRL 筆者已經 loop 了快四十遍。
  <p align="center"> 
    <a href="https://www.youtube.com/watch?v=x6UurRhIgD0">
      <img src="https://i.imgur.com/6FUcr4E.png" alt="Video Demo" />
    </a>
  </p>


---
> [關於作者](https://goo.gl/1pnqEk)

> [回到首頁](https://git.io/v5wk4)
