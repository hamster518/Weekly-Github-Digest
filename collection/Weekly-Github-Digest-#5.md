## Weekly-Github-Digest #5
> 2017/09/28 - 2017/10/04

#### Web - 網路本身高風險，請詳閱公開說明書
- [jenkoian/hacktoberfest-checker](https://github.com/jenkoian/hacktoberfest-checker)  🎃 Check how you're doing in hacktoberfest
  
  > 每年十月的年度盛事，也就是 Github 官方會舉辦一個活動，為了鼓勵大家多多參與開源社群，只要在該月發出至少四個 Pull Request，你就能夠拿到他們提供的衣服和貼紙，也許發 PR 對新手會較為陌生，對於第一次參與的開發者 Github 上也有諸多相當平易近人的專案像是 [first-contributions](https://github.com/Roshanjossey/first-contributions) ，整體而言算是讓開源圈更加蓬勃發展一個很棒的作法。
  <p align="center">
    <a target="_blank" href="https://github.com/jenkoian/hacktoberfest-checker"><img alt="hacktoberfest-checker" src="https://i.imgur.com/lopLZTi.png"></a>
  </p>
  
- [MattyAyOh/Mortality](https://github.com/MattyAyOh/Mortality)  Published Chrome Extension, replaces new tab with your age in milliseconds
  > 18 歲以前完全不覺得自己在虛度時光，總想快點長大快點脫離升學制度的窠臼，早日進入大學好像這樣做就能成為真正可靠有擔當的大人，但現實是殘酷的啊，畢了業之後才驚覺之後的日子很可能就是不斷重複上班工作下班休息的無限輪迴直到老死，這個 Chrome Extension 功能其實蠻簡單的，但它能夠讓你體認到剩下的時間還有多少，如果你正在耍廢亦或是漫無目的的活著，或許這方法會讓你驚醒去做真正重要的事情。 
  <p align="center">
    <a target="_blank" href="https://github.com/MattyAyOh/Mortality"><img alt="mortality" src="https://i.imgur.com/RYs9Jtr.png"></a>
  </p>
---

#### Terminal - 已經是 iTerm 的形狀了呢
- [Paradoxis/Gordon](https://github.com/Paradoxis/Gordon)  Ever wanted to get yelled at by Chef Ramsay whenever you inevitably fuck up your script or make a typo on the command line? Well now you can !
  <p align="center">
    <a target="_blank" href="https://github.com/Paradoxis/Gordon"><img alt="Gordon" src="https://i.imgur.com/DPl80Zs.jpg"></a>
  </p>
  
  > 忘記是在逛 Reddit 還是 Hackernews 上看到的，概念充滿了惡搞成分且非常有趣，主體功能就是當你打出根本不存在的指令或是打錯字時，地獄主廚 Gordon Ramsay 就會跳出來對你碎念著幾句垃圾話，筆者實際測試之後意外的療癒啊，詳細教學如下：

  因為需要 mp3 音檔所以先把整包專案下載下來：
  ```shell
  $ git clone https://github.com/Paradoxis/Gordon.git
  ```
  接著要在 `~/.bash_profile` 中做設定，根據目錄相對位置引入：
  ```bash
  . ~/Desktop/ttest/Gordon/gordon.sh
  ```
  如果跟筆者一樣是使用 zsh 的話要在 `~/.zshrc` 這樣設定：
  ```bash
  precmd() { eval "$PROMPT_COMMAND" }  # make zsh behavior just be like bash
  . ~/Desktop/ttest/Gordon/gordon.sh
  ```
  切換到目錄相對位置，最後把 `insults` 內的所有音檔放到 `~/.gordon` 裡去：
  ```shell
  cp -a insults ~/.gordon
  ```
  
  筆者在做 bash 設定時因為對 shell 相關不甚熟悉所以卡蠻久的，後來請教了大神同事才順利解決，相關解法是在[這裡找到的](https://superuser.com/questions/735660/whats-the-zsh-equivalent-of-bashs-prompt-command)。
  
  現在你可以快樂的浸淫在 Gordon 的講幹話時間了～(⊙ᗜ⊙) ～

---

#### Useful OSS - 好用的開源軟體

- [audreyt/moedict-webkit](https://github.com/audreyt/moedict-webkit)  萌典網站

  > 專案主要開發者為臺灣相當有名的技術人唐鳳，萌典其實出來也有段時間了，距離首次發布到目前為止也有將近六年的時間了，網站本質其實就是一個線上字典，部分歧異字可能不見得有被收錄進去，但從操作介面和功能面上來看相當實用，頁面上看到的解釋和每個字都是可以被點擊查詢的，包含成語，諺語和逐字筆畫順序，非常豐富。
  <p align="center">
    <a target="_blank" href="https://github.com/audreyt/moedict-webkit"><img alt="moedict-webkit" src="https://i.imgur.com/iKU9ds3.png"></a>
  </p>
---

#### Developers - 開發者們

- [TJ Holowaychuk](https://github.com/tj)
  
  > 接觸 JavaScript 圈子這麼久了，不知道 tj 這號大神人物也絕對用過他曾開發過的各種工具和框架，實作 command line tool 你會用到 [command.js](https://github.com/tj/commander.js)，寫單元測試你會使用到 [should.js](https://github.com/tj/should.js) 斷言 library，除此之外 tj 的多產程度是極為驚人的，一個 JavaScript 的套件推出五往往都是百顆 stars 起跳，質量兼具的開發者不多見，每次看他 commits 數明明沒有很多但東西就是好用的不得了，感受到和十倍工程師強大的差距啊...

---

#### Technical Posts - 你都去哪看技術文啊城武

- [CodeTengu Weekly](https://weekly.codetengu.com/)  適合所有患有資訊焦慮症、氣血循環不順以及性受挫的軟體工程師們
  
  > 碼天狗是許多開發者自發性組織的週刊，編者群包含了多位業界有名的技術人，導讀簡介和摘要推薦對於文章閱讀都有相當程度的幫助，他們最近也達到了出刊一百期的里程碑，期待他們持續推出各種有趣的內容和知識。

---

#### You Need Some Music, And A Bottle of Dry Martini - 你一定要把氣氛搞得這麼銷魂嗎
- [Sayuri - Odd Eye](https://www.youtube.com/watch?v=J2sK7UI5HYY)
  
  > 對筆者而言很少有歌手或是樂團能夠在聽到的第一時間就徹底愛上的，酸欠少女散發的音樂魅力的確有股奇妙的魔法充斥其中，可以去找找看出道前她在各地車站表演的音樂影片，唱現場的爆發力十足，作品定位曲風明確歌詞內容不矯情。很難想像她只有 21 歲。
  <p align="center"> 
    <a href="https://www.youtube.com/watch?v=J2sK7UI5HYY">
      <img src="https://i.imgur.com/OoZrtgJ.png" alt="Video Demo" />
    </a>
  </p>


---
> [關於作者](https://goo.gl/1pnqEk)

> [回到首頁](https://git.io/v5wk4)
