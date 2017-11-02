## Weekly-Github-Digest #9
> 2017/10/26 - 2017/11/01

#### Web - 網路本身高風險，請詳閱公開說明書
- [sindresorhus/merge-windows](https://github.com/sindresorhus/merge-windows)  Chrome extension - Merge windows into the active one
  
  > 不知道這樣的需求是否普遍，但就筆者目前的前端工作經驗上而言，通常的情境會是這樣：一台 Mac 配上一台顯示器，顯示器會拿來開 jira 開會各種相關 tickets，Chrome 分頁往往越開越多越爆炸，然後另個分頁可能又是不怎麼相關的 UI 討論和資料等等，當忙到一個段落時就會把各種分頁一一拉回到一個主頁面，人都有惰性，但惰性是美德，試試一鍵處理把煩人的分頁一次搞定吧。
  <p align="center">
    <a target="_blank" href="https://github.com/sindresorhus/merge-windows"><img alt="merge-windows" src="https://github.com/sindresorhus/merge-windows/raw/master/screenshot.png"></a>
  </p>
  
- [iamchucky/PttChrome](https://github.com/iamchucky/PttChrome)  A GNU/GPL telnet client for connecting to BBS site ptt.cc
  > 其實蠻慚愧的，自認資深鄉民的筆者竟然上禮拜才知道有著 PttChrome 這樣的網頁瀏覽工具可以使用 orz，不過大概是平常用手機滑習慣了，筆者開瀏覽器觀看後反而有種奇妙說不出的感覺。
  <p align="center">
    <a target="_blank" href="https://github.com/iamchucky/PttChrome"><img alt="PttChrome" src="https://cdn.free.com.tw/blog/wp-content/uploads/2014/07/PttChrome2014-07-01_1011.png"></a>
  </p>
---

#### Terminal - 已經是 iTerm 的形狀了呢
- [kevin940726/emoji-cz](https://github.com/kevin940726/emoji-cz)  ✨ A commitizen emoji adapter [文章解說](https://kaihao.info/posts/Write-your-commit-messages-in-the-right-way/)
  <p align="center">
    <a target="_blank" href="https://github.com/kevin940726/emoji-cz"><img alt="emoji-cz" src="https://i.imgur.com/JyFgERl.png"></a>
  </p>
  
  > 過去不習慣 command line 介面的開發者像是筆者在做 git 相關操作時會蠻多時間仰賴於一些 GUI 的工具，操作久了，多了點經驗也想多做點不同的嘗試，從 CLI 著手似乎是個不錯的選項，畢竟整個介面都黑黑的，很容易讓人誤以為是某某大師在發功，簡言之就是某種程度可以讓你在不熟悉 CLI 的同事面前裝逼一下的工具ＸＤ：

  大大前提，記得先行安裝[commitizen](https://github.com/commitizen/cz-cli)：
  ```shell
  $ npm install -g commitizen
  ```
  接著再去安裝今天的主角：
  ```shell
  $ npm install -g emoji-cz
  ```
  最後做個簡單的設定：
  ```shell
  $ echo '{ "path": "emoji-cz" }' > ~/.czrc
  ```  
  以前要上傳 commit 常常在想到底應該歸類在哪裡比較適合，現在有了 emoji-cz 這個方便的 emoji adapter，只要把原本的指令替換掉即可：
  原本的：
  ```shell
  $ git commit -am "fix typo"
  ```
  更新版：
  ```shell
  $ git cz
  ```
  按下之後便會自動跳出選項方便按上下鍵選擇類型，從此 commit 變得輕鬆無負擔！
  
---

#### Useful OSS - 好用的開源軟體

- [webslides/webslides](https://github.com/webslides/webslides)  Create HTML presentations in seconds

  > 記得去年剛退伍在找工作投履歷時，蠻幸運很快的收到其中一間公司的回覆，信中寫到第二次面試要做個簡單的簡報，介紹過去的經驗和寫過的專案，那時想了蠻久，本來想說低調保守一點用 PowerPoint 做一做，後來想到有個叫做 Reveal.js 的工具可以順便玩玩看，便有點反骨的直接做下去，收到的 feedback 還不錯，這次介紹的 webslides 目的同樣是做簡報，看了文件和一些基本的模板，整體而言會比 Reveal.js 操作上更加快速和易於上手，Reveal.js 推出其實也有段時間了，想換個工具或是嘗鮮的開發者們不妨花點時間玩玩看。
  <p align="center">
    <a target="_blank" href="https://github.com/webslides/webslides"><img alt="webslides" src="https://i.imgur.com/Gy2YPOi.png"></a>
  </p>
---

#### Developers - 開發者們

- [Lea Verou](https://github.com/leaverou)
  
  > 對前端還算熟悉的朋友在實做一些特效或是網頁動畫時，都會很習慣的用上 JavaScript 在邏輯實作上，畢竟開發速度較快相關套件支援也較多，蠻少人會想到也許透過單純的 Pure CSS 也能做到一樣的效果，Lea Verou 就是其中的 master 之一，同時也是 CSS 界中相當耀眼的存在，忘記是去年還是前年，前端社群相當多人推薦入坑的 CSS Secrets 一書就是出自她筆下的經典，Lea 會被這麼多人尊稱作女神還有個原因，工作多年之後儘管在業界已累積不小的名氣和聲量， Lea 後來還是願意選擇回到學校繼續進修，而且還是嚇死人的 MIT，詳情可見[這篇部落格文](http://lea.verou.me/2014/02/im-going-to-mit/)。

---

#### Technical Posts - 你都去哪看技術文啊城武

- [寫點科普，請給指教。](https://hellolynn.hpd.io/)  瞭解各產業領域的運行規則，保有思考與觀察力的敏銳。
  
  > 不僅限於軟體相關的技術知識分享，該部落格集錦了極為海量的類別以及不同層面，最一開始是被[一看就懂的 IC 產業結構與競爭關係
](https://hellolynn.hpd.io/2017/04/08/%E4%B8%80%E7%9C%8B%E5%B0%B1%E6%87%82%E7%9A%84-ic-%E7%94%A2%E6%A5%AD%E7%B5%90%E6%A7%8B%E8%88%87%E5%90%8D%E8%A9%9E/)這篇文章吸引進來，內容詳實以外也相當平易近人，後來進一步挖掘才發現程式開發相關的諸如 Node 和 Python 都有入門文，資料結構和演算法自然也有不少篇幅，真心大推。

---

#### You Need Some Music, And A Bottle of Dry Martini - 你一定要把氣氛搞得這麼銷魂嗎
- [DJ Okawari - Flower Dance](https://www.youtube.com/watch?v=AULG4MoYxQk)
  
  > 和 DJ Okawari 的第一次接觸是在大學室友的手機聽到的，當時印象中在公館附近的河濱公園排練火舞，這首 Flower Dance 正是編舞的配樂，聽得出來混了蠻多的音效進去的，開頭的對話也別具巧思。只能說大學時代真的很 87，做了很多現在無法想像的蠢事，有段不短的時間跟室友念完書就騎著鳥鳥的腳踏車，帶上兩根長長的火棍和兩個史詩級別的光棍，一路搖搖晃晃像在走鋼索的人拿平衡桿一般的騎到公園。講這麼多搞不好有人以為筆者也會跳火舞，筆者每次去都只是幫忙帶道具去而已，其實大部分時間都在一旁吃炸物配啤酒。呵呵。
  <p align="center"> 
    <a href="https://www.youtube.com/watch?v=AULG4MoYxQk">
      <img src="https://i.imgur.com/KWEyYyw.png" alt="Video Demo" />
    </a>
  </p>


---
> [關於作者](https://goo.gl/1pnqEk)

> [回到首頁](https://git.io/v5wk4)
