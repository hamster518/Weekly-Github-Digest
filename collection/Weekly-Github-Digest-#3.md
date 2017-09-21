## Weekly-Github-Digest #3
> 2017/09/14 - 2017/09/20

#### Web - 網路本身高風險，請詳閱公開說明書
- [phalt/swapi](https://github.com/phalt/swapi)  The Star Wars API 
  
  > 開源世界最為有趣的一點，大概就是你想得到的東西幾乎在上面都可以找到，就連星際大戰的相關 API 都有熱情的開發者主動製作並維護，雖然作者自謙是個 API Engineer(在 about 頁面自述的)，不過可以把自己的興趣做成讓更多人使用的工具基本上就是美事一件。
  <p align="center">
    <a target="_blank" href="https://github.com/phalt/swapi"><img alt="swapi" src="https://i.imgur.com/nO3ycK3.png"></a>
  </p>
  
- [kbrsh/moon](https://github.com/kbrsh/moon)  🌙 ⚡️ A minimal, blazing fast UI library
  > Rails 可以說是把 MVC 架構發揚光大的核心關鍵，後續不少框架的哲學諸如 Laravel 等都有不少顯而易見的借鑑之意，只是不曉得不過幾年以後前端就開啟了另外一片戰場，百家爭鳴各大廠牌林立，今天有了 React，之後又出了個 Vue，隨後開始了無止境的效能追逐，這款 Moon 基本上使用的方式和提供的 API 和 Vue 有 87% 像，在作者的[Medium 一文中](https://hackernoon.com/introducing-moon-1d44a99635f0)有提到為何想做這個項目，簡言之就是看到 React 界有 Preact，所以也想為 Vue 社群做一個輕量版的 Moon，所以說不要因為看到 A 框架長得很像 B 就說 A 是在抄襲，批評是不會帶來任何的長進和砥礪，真正要觀察的是開發者設計的本意及用心所在和為社群帶來的整體效益。 
  <p align="center">
    <a target="_blank" href="https://github.com/kbrsh/moon"><img alt="moon" src="https://i.imgur.com/t6iK8UA.png"></a>
  </p>
---

#### Terminal - 已經是 iTerm 的形狀了呢
- [sindresorhus/lock-cli](https://github.com/sindresorhus/lock-cli)  Lock your system from the command-line
  
  > 不少辦公室都會訂下一些規定，像是離開座位時要記得把電腦鎖上，否則不巧碰上商業間諜把公司機密外洩那後果真的不堪設想，所以至少在視線所及範圍之內，我們似乎還是可以做點簡易的防護措施吧！這個工具可以讓你從 command line 進入密碼鎖定模式，教學如下：

  這邊示範的是用 npm 體系進行全域安裝的方式：
  ```shell
  $ npm i -g lock-cli
  ```
  就這麼簡單的好了，接著當你離開座位前記得在 iterm2 這樣打：

  ```shell
  $ lock
  ```
  如果有用 alfred 的人會更推薦搭配這套[alfred-lock](https://github.com/sindresorhus/alfred-lock) 使用：
  ```shell
  $ npm i -g alfred-lock
  ```
  使用熱鍵叫出 alfred 接著打 lock 關鍵字後筆電就被當初設定的密碼鎖住啦，同事再也不會趁你不在時亂用帳號偷發文(咦)。
  
  下次有人問你有沒有 Geek Style 就把這系列給對方看就好了ㄏㄏ。

---

#### Useful OSS - 好用的開源軟體

- [jiahaog/nativefier](https://github.com/jiahaog/nativefier)  Make any web page a desktop application

  > 用 Web 寫桌面應用程式已經不稀奇了，在 NW 和 Electron 推出之後以往 Web 難以做到的事情似乎都迎刃而解了，雖然有了這樣的解法，但有沒有在更為簡單的作法呢？像是把別人家的應用程式也打包起來。這時你想起了那著名的[阿特伍德定律](https://blog.codinghorror.com/the-principle-of-least-power/):「任何可以用 JavaScript 來寫的應用，最終都將用 JavaScript 來寫」，這套 nativefier 很神奇地真的做到這件事了！ 再一次把 JS 的極限推得更遠了。
  <p align="center">
    <a target="_blank" href="https://github.com/jiahaog/nativefier"><img alt="nativefier" src="https://raw.githubusercontent.com/jiahaog/nativefier/master/screenshots/walkthrough.gif"></a>
  </p>
---

#### Developers - 開發者們

- [Evan You](https://github.com/yyx990803)
  
  > 既然這期都提到了 Vue，介紹作者也是相當合情合理的啊，今日前端有這麼多好用的工具讓使用者可以視不同情況進行選擇， Vue 社群絕對功不可沒。可能很難想像這樣厲害的開發者竟然不是 CS 本科出身的，等於說所有的工程技巧和框架思維都是透過自學從無到有，或許有人覺得開發者本身資質就天賦異稟，有人甚至在知乎問了[一道這樣的問題](https://www.zhihu.com/question/53539039)，到底該如何做才能成為 Evan You 這樣的開發者呢，有在經營社群果然不同凡響，本尊真的跳出來直接回應，交流往往是打破誤解的第一步。別人或許聰明但別人一樣很努力啊，每個人都有試圖想達成的目標，不因為自己不是那樣的身份就輕易放棄，瓶頸的地方就去找相關方法做突破，這點比起任何雞湯文都對非本科開發者起到更實際有效的激勵。

---

#### Technical Posts - 你都去哪看技術文啊城武

- [iT邦幫忙 鐵人賽](http://ithelp.ithome.com.tw/tags/articles/2017%E9%90%B5%E4%BA%BA%E8%B3%BD)
  
  > 由 iThome 舉辦的年度盛事，會分成各大組別進行不同主題的技術文章分享及撰寫，30 天代表參賽者要進行為期一個月左右的連續不間斷寫作，主題只要切題即可題目可以自訂，不少台灣知名的技術人都會在此平台整理過去一年累積的新技能和知識點，也因此能在這裡看到許多高質量同時兼具水準的好文章，筆者私心非常推薦。

---

#### You Need Some Music, And A Bottle of Dry Martini - 你一定要把氣氛搞得這麼銷魂嗎
- [Spangle call Lilli line "nano - TK kaleidoscope Remix"](https://www.youtube.com/watch?v=0zUE1E3e7Mg)
  
  > 對筆者來說原版通常都是最好聽的版本，但這首卻是 remix 版本大勝，曲風帶點搖滾迷幻，到了間奏和副歌階段吉他的不停刷弦讓整體意境混沌了起來。
  <p align="center"> 
    <a href="https://www.youtube.com/watch?v=0zUE1E3e7Mg">
      <img src="https://i.imgur.com/pi66ueL.png" alt="Video Demo" />
    </a>
  </p>


---
> [關於作者](https://goo.gl/1pnqEk)

> [回到首頁](https://git.io/v5wk4)
