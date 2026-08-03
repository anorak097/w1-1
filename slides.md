---
theme: neversink
title: \#1 Overview
class: text-center
transition: slide-left
comark: true
slide_info: false
neversink_slug: 'AI 概論與實作體驗 #1 AI 概論'
---

<h1 style="font-size: 2.5rem; font-weight: bold;">AI 概論與實作體驗</h1>
<h1 style="font-size: 5rem; margin-top: 0px; font-weight: bold;">#1 AI 概論</h1>

---
transition: slide-left
layout: top-title
color: dark
---
::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold;  display: flex; justify-content: space-between;">
   <span>什麼是 AI?</span><span style="font-size: 2rem; color: gray;">先來看幾個例子</span>
</h1>

::content::
<div style="margin-bottom: 10px;">
    <h2 style="font-size: 2.5rem;">Bombe? <span v-click=1><akar-icons:cross color="red"/></span></h2>
    <h2>被稱為人工智慧之父的<span style="background:#FFE45E; color:black;">艾倫·圖靈 (Alan Turing)</span> 用來破譯德軍<span style="background:#FFE45E; color:black;">恩尼格碼密碼機 (Enigma)</span> 的機器</h2>
</div>
<div style="margin-bottom: 10px;" v-click=2>
    <h2 style="font-size: 2.5rem;">Deep Blue? <span v-click=3><akar-icons:circle color="green"/></span></h2>
    <h2><span style="background:#FFE45E; color:black;">IBM</span> 開發的<span style="background:#FFE45E; color:black;">西洋棋電腦</span>，曾在 1997 年擊敗世界冠軍加里·卡斯帕羅夫</h2>
</div>
<div style="margin-bottom: 10px;" v-click=4>
    <h2 style="font-size: 2.5rem;">Line/Discord 聊天機器人? <span v-click=5><akar-icons:circle color="green"/></span></h2>
    <h2>e.g. <span style="background:#FFE45E; color:black;">疾管家</span> LINE 聊天機器人</h2>
</div>
<div style="margin-bottom: 10px;" v-click=6>
    <h2 style="font-size: 2.5rem;">ChatGPT? <span v-click=7><akar-icons:circle color="green" /></span></h2>
    <h2>由 <span style="background:#FFE45E; color:black;">OpenAI</span> 開發的<span style="background:#FFE45E; color:black;">大型語言模型 (LLM)</span>，能夠進行<span style="background:#FFE45E; color:black;">自然語言處理 (NLP) 和生成 (NLG)</span></h2>
</div>

---
transition: slide-left
layout: side-title
side: left
color: dark
titlewidth: is-4
align: rm-lm
---
::title::
<h1 style="font-size: 2.5rem; line-height: 1.2; margin-bottom: 24px; padding-bottom: 10px; font-weight: bold;">
    人工智慧 (Artificial Intelligence<br>, AI) <br>是什麼?
</h1>

::content::
<h2 style="font-size: 2.5rem; line-height: 1.2;">一種技術，能使電腦，自主做出過往需依靠人類智慧才能做出的判斷</h2>
<br>
<Admonition title="Note" width="calc(100% - 40px)" v-click=1  icon="pixel:notebook" color=cyan-light>
    <h2 style="font-size: 2rem;">電腦自行做出像人類的判斷</h2>
</Admonition>
<Admonition title="Think" width="calc(100% - 40px)" v-click=2  icon="pixel:face-thinking" color=amber-light>
    <h2 style="font-size: 2rem;">如何做到?</h2>
</Admonition>

<AdmonitionType type="tip" width="auto" v-click=3 style="margin-left: 40px;">
    <h2 style="font-size: 2rem;">透過訓練、學習等方式製作出來的模型推論</h2>
</AdmonitionType>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>AI?</span><span style="font-size: 2rem; color: gray;">回頭看前面的例子</span>
</h1>

::content::
<div style="margin-bottom: 10px;">
    <h2 style="font-size: 2.5rem;">Bombe? <span ><akar-icons:cross color="red"/></span></h2>
    <h2>被稱為人工智慧之父的<span style="background:#FFE45E; color:black;">艾倫·圖靈 (Alan Turing)</span> 用來破譯德軍<span style="background:#FFE45E; color:black;">恩尼格碼密碼機 (Enigma)</span> 的機器</h2>
</div>

<div style="margin-bottom: 10px;">
    <div style="width: 100%; display: flex; column-gap: 50px; align-items: center-top;">
        <div style="flex: 3;">
            <h2 style="font-size: 2.5rem;">WHY?</h2>
            <h2>運作模式是在理解恩尼格碼結構與運作模式後，利用機器快速運算出所有可能性，可理解成計算機。</h2>
            延伸閱讀 恩尼格碼的機械設計與運作原理：
            <ul style="margin: 0; padding-left: 20px; line-height: 1;">
                <li style="line-height: 1 !important;">
                    <a href="https://www.youtube.com/watch?v=V4V2bpZlqx8" target="_blank" style="color: #0056b3; text-decoration: none; font-weight: 500;">
                        Flaw in the Enigma Code - Numberphile
                    </a>
                </li>
                <li style="line-height: 1 !important;">
                    <a href="https://www.youtube.com/watch?v=kj_7Jc1mS9k" target="_blank" style="color: #0056b3; text-decoration: none; font-weight: 500;">
                        Tackling Enigma (Turing's Enigma Problem Part 2) - Computerphile
                    </a>
                </li>
                <li style="line-height: 1 !important;">
                    <a href="https://www.youtube.com/watch?v=kE3Xb-XH8NU&t=819" target="_blank" style="color: #0056b3; text-decoration: none; font-weight: 500;">
                        【不止遊戲】二戰德軍號稱「謎」的密碼機，究竟是如何使用的？
                    </a>
                </li>
            </ul>
        </div>
        <div style="flex: 3; text-align: center;">
            布萊切利莊園的 Bombe 模型
            <a title="en.wikipedia上的使用者Messybeast, CC BY-SA 3.0 &lt;http://creativecommons.org/licenses/by-sa/3.0/&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:TuringBombeBletchleyPark.jpg"><img width="90%" alt="Mockup of a bombe machine at Bletchley Park." src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/TuringBombeBletchleyPark.jpg/330px-TuringBombeBletchleyPark.jpg"></a>
        </div>
    </div>
</div>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>AI 的發展過程</span>
</h1>

::content::
<div class="relative w-full h-[460px]">
    <div v-click.hide="1" class="absolute inset-0">
        <AITimeLine :activeIndex="1" />
    </div>
    <div v-click="1" class="absolute inset-0">
        <AITimeLine :activeIndex="2" />
    </div>
</div>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>模仿遊戲與圖靈測試 (Ⅰ)</span><span style="font-size: 2rem; color: gray;">人工智慧最初的評估行為標準</span>
</h1>

::content::
<div style="margin-bottom: 10px;">
    <div style="width: 100%; display: flex; align-items: center-top;">
        <div style="flex: 3;">
            <h2 style="line-height: 1.2;">
                圖靈在利用 Bombe 協助盟軍獲得勝利後，持續於電腦領域研究，並於 1950 年，發表了一篇名為<span style="background:#FFE45E; color:black;">《Computing Machinery and Intelligence》(計算機器與智慧)</span> 的論文，提出了「<span style="background:#FFE45E; color:black;">模仿遊戲 (Imitation Game)</span>」的概念。
            </h2>
            <br>
            <h2 style="font-size: 2.5rem; line-height: 1.5;">模仿遊戲 </h2>
            <h2 style="line-height: 1.2;">
                男性 A 及女性 B，與審問者 C 進行書面的溝通，A 需要使 C 做出錯誤的判斷，而 C 必須在互不相見的情況下，以書面訊息與兩者進行相同的提問，並從回覆中，正確判斷 A 與 B 的性別。 
            </h2>
        </div>
        <div style="flex: 1; text-align: center;">
            模仿遊戲進行方式圖解
            <a href="https://commons.wikimedia.org/wiki/File:The_Imitation_Game.svg#/media/File:The_Imitation_Game.svg"><img style="background-color: #FFFFFF; width:auto; height: auto;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/The_Imitation_Game.svg/1280px-The_Imitation_Game.svg.png" alt="File:The Imitation Game.svg"></a><br>By <a href="//commons.wikimedia.org/wiki/User:Hferee" title="User:Hferee">Hugo Férée</a> - <span class="int-own-work" lang="en">Own work</span>, <a href="https://creativecommons.org/licenses/by-sa/3.0" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=17059778">Link</a>
        </div>
    </div>
</div>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>模仿遊戲與圖靈測試 (Ⅱ)</span><span style="font-size: 2rem; color: gray;">後人的解釋</span>
</h1>

::content::
<div style="margin-bottom: 10px;">
    <div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
        <div style="width: 75%; padding-right: 20px; box-sizing: border-box;">
            <h2 style="line-height: 1.2; margin-top: 0;">模仿遊戲後續延伸出的概念被後人稱為<span style="background:#FFE45E; color:black;">圖靈測試</span>， A 由電腦取代，B 則只限人類，C 一樣需要以書面訊息進行提問，並判斷 A 與 B 誰是電腦，誰是人類，若<span style="background:#FFE45E; color:black;"> C 判斷錯誤率超過 30% 則 A 通過圖靈測試</span>。</h2>
            <h2 style="line-height: 1.2;">
                圖靈測試被認為是<span style="background:#FFE45E; color:black;">人工智慧最初的評估行為標準</span>。 
            </h2>
            <div v-click=1 style="display: flex; flex-direction: column; margin-top: 15px;">
                <p style="width: 80%; margin: 0 auto 10px auto; text-align: left; box-sizing: border-box;">延伸閱讀 電影《模仿遊戲》(The Imitation Game, 2014) 預告：</p>
                <div style="width: 100%; max-width: 560px; aspect-ratio: 16 / 9; display: flex; justify-content: center; margin: 0 auto;">
                    <iframe style="width: 75%; height: 75%;" src="https://www.youtube.com/embed/spkUZQt_4pI?si=35gLPq1GhqTwy4yi" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                </div>
            </div>
        </div>
        <div style="width: 25%; display: flex; flex-direction: column; align-items: center; text-align: center; box-sizing: border-box;">
            <div style="margin-bottom: 5px;">圖靈測試進行方式圖解</div>
            <a href="https://commons.wikimedia.org/wiki/File:Turing_Test_Version_3.svg#/media/File:Turing_Test_Version_3.svg" style="display: block; width: 100%;">
                <img style="background-color: #FFFFFF; width: 100%; height: auto;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b9/Turing_Test_Version_3.svg/1280px-Turing_Test_Version_3.svg.png" alt="Turing Test Version 3.svg">
            </a><br>
            <span style="font-size: 12px; color: #666; margin-top: 5px;">
                By Hugo Férée - Own work, <a href="https://creativecommons.org/licenses/by-sa/3.0">CC BY-SA 3.0</a>
            </span>
        </div>
    </div>
</div>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>AI 的發展過程</span>
</h1>

::content::
<AITimeLine :activeIndex="3" />

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>達特茅斯會議</span><span style="font-size: 2rem; color: gray;">人工智慧的起源</span>
</h1>

::content::
<div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
    <div style="width: 66%; padding-right: 20px; box-sizing: border-box;">
        <h2>
            達特茅斯夏季人工智慧研究計劃 (Dartmouth Summer Research Project on Artificial Intelligence)，<span style="background:#FFE45E; color:black;">約翰·麥卡錫 (John McCarthy)</span> 等人，正式提出「人工智慧」(Artificial Intelligence, AI) 的概念，並定義<span style="background:#FFE45E; color:black;">人工智慧為「電腦系統執行通常與人類智慧相關任務的能力」</span>。
        </h2>
        <br>
        <Admonition title="Note" width="100%" v-click=1  icon="pixel:notebook" color=cyan-light>
            <h2 style="font-size: 2rem;">經常被忽略的人工智慧之父</h2>
        </Admonition>
    </div>
    <div style="width: 33%; align-items: center; text-align: center; box-sizing: border-box;">
        約翰·麥卡錫<br>(John McCarthy, 1927－2011)<br>
        <a href="https://commons.wikimedia.org/wiki/File:John_McCarthy_Stanford.jpg#/media/File:John_McCarthy_Stanford.jpg">
            <img style="width: 100%; height: auto; max-width: 300px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/49/John_McCarthy_Stanford.jpg/1280px-John_McCarthy_Stanford.jpg" alt="File:John McCarthy Stanford.jpg">
        </a>
        <span style="font-size: 12px; color: #666;">
            By <a rel="nofollow" class="external text" href="https://www.flickr.com/photos/null0/">"null0"</a>, <a href="https://creativecommons.org/licenses/by-sa/2.0">CC BY-SA 2.0</a>
        </span>
    </div>
</div>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>AI 的發展過程</span>
</h1>

::content::
<AITimeLine :activeIndex="5" />

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>AI 發展過程中遇到的質疑</span><span style="font-size: 2rem; color: gray;">中文房間論證 (Ⅰ)</span>
</h1>

::content::
<div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
    <div style="width: 66%; padding-right: 20px; display: flex; flex-direction: column; align-items: center; box-sizing: border-box;">
        <h2 style="width: 100%; text-align: left; margin-bottom: 10px;">
            1980 年，哲學家<span style="background:#FFE45E; color:black;">約翰·希爾勒 (John Searle)</span> 提出<span style="background:#FFE45E; color:black;">「中文房間論證」(Chinese Room Argument)</span>，認為人工智慧只能模擬人類的語言理解能力，並不能真正理解語言的意義。
        </h2>
        <a href="https://www.youtube.com/watch?v=oaOG1xOk7XY&t=107s" target="_blank" style="display: block; width: 75%; text-align: center;">
            <img src="https://preview.redd.it/fun-fact-the-chinese-room-is-a-famous-artificial-v0-hqrg8ha6bw6g1.png?width=1365&format=png&auto=webp&s=11f120b955fd1936622d8bac5a195d27ca87e190" style="width: 100%; height: auto; margin-top: 10px; margin-bottom: 10px;">
        </a>
        <span style="font-size: 12px; color: #666; text-align: center;">
            THE AMAZING DIGITAL CIRCUS - Ep 7: Beach Episode <a href="https://www.youtube.com/watch?v=oaOG1xOk7XY&t=107s" target="_blank">Link</a>
        </span>
    </div>
    <div style="width: 34%; display: flex; flex-direction: column; align-items: center; text-align: center; box-sizing: border-box;">
        <div>約翰·希爾勒</div>
        <div style="margin-bottom: 10px;">(John Searle, 1932 － 2025)</div>
        <a href="https://commons.wikimedia.org/wiki/File:John_searle2.jpg#/media/File:John_searle2.jpg" style="display: block; width: 80%; max-width: 300px;">
            <img style="width: 100%; height: auto;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/John_searle2.jpg/1280px-John_searle2.jpg" alt="File:John searle2.jpg">
        </a>
        <span style="font-size: 12px; color: #666; margin-top: 5px;">
            By Matthew Breindel - CC BY-SA 3.0, <a href="https://commons.wikimedia.org/w/index.php?curid=1974017" target="_blank">Link</a>
        </span>
    </div>
</div>

<!--
中文房間實驗描述的是房間中有一名不懂中文的外國人與一堆能讓外國人理解中文的文獻，當門外的人使用寫了中文的紙條與外國人溝通時，外國人使用了文獻，依照中文的形狀從文獻中找出對應的回應，以紙條傳回中文回應。
那麼，門外的人能知道裡面的外國人其實不懂中文嗎?
-->

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>AI 發展過程中遇到的質疑</span><span style="font-size: 2rem; color: gray;">中文房間論證 (Ⅱ)</span>
</h1>

::content::
<h2>
    中文房間論證即是<span style="background:#FFE45E; color:black;">針對圖靈測試的質疑</span>，當一個不懂中文人依靠文獻通過了中文對話的模仿遊戲，不懂中文的那人還是不懂。
    <br>
    換成電腦來說，即使電腦通過了圖靈測試，可能也不代表電腦擁有該方面的智慧，而有是外人寫好的<span style="background:#FFE45E; color:black;">邏輯、演算法</span>足以使其推算出了最適合的回應。這代表其可能並不真正擁有處理該問題的「智慧」。
</h2>
<br>
<Admonition title="Note" width="100%" v-click="1" icon="pixel:notebook" color=cyan-light>
    <h2 style="font-size: 2rem;">Intelligence</h2>
    <h2 style="font-size: 2rem;">智慧</h2>
    <h2>the ability to learn, understand, and make judgments or have opinions that are based on reason. —— Cambridge Dictionary</h2>
    <h2>學習、理解，並能有依據的進行判斷或選擇的能力</h2>
</Admonition>


---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>專家系統</span><span style="font-size: 2rem; color: gray;">AI 崛起的關鍵</span>
</h1>

::content::
<div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
    <h2 style="width: 50%; padding-right: 20px; box-sizing: border-box;">電腦要進行一件事進行判斷，需要一套針對該事的演算法，而<span style="background:#FFE45E; color:black;">各領域專家針對各事項擬定出的專屬演算法</span>就是專家系統，但是，專家系統有著<span style="background:#FFE45E; color:black;">需要專人新增知識以及系統更新</span>的問題。</h2>
    <a data-flickr-embed="true" href="https://www.flickr.com/photos/dullhunk/7214525854" title="Engineering flowchart 🔨 Does it Move? Should it? #WD40 vs. Duct Tape (original artist unknown)" style="display: flex; justify-content: left; align-items: center; height: 100%; width: 50%;">
        <img src="https://live.staticflickr.com/8160/7214525854_733237dd83_z.jpg" alt="Engineering flowchart 🔨 Does it Move? Should it? #WD40 vs. Duct Tape (original artist unknown)" style="height: auto; width: auto; object-fit: contain; display: block;" />
    </a>
</div>

---
transition: slide-left
layout: top-title
color: dark
routeAlias: ML
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>機器學習與深度學習</span><span style="font-size: 2rem; color: gray;">AI 崛起的關鍵</span>
</h1>

::content::
<h2>機器學習的出現解決了專家系統的缺點，<span style="background:#FFE45E; color:black;">給予機器處理過的資料進行學習</span>。<span v-click="2">後續又衍生出了<span style="background:#FFE45E; color:black;">模仿人類大腦運作模式</span>以讓機器<span style="background:#FFE45E; color:black;">自行處理資料並學習</span>的深度學習。</span></h2>
<Admonition title="Note" width="100%" icon="pixel:notebook" color=cyan-light>
    <h2 style="font-size: 2rem;">人工智慧 <span style="font-size: 1.5rem;">在機器中模擬或複製人類智慧。</span></h2>
    <Admonition title="Note" width="auto" style="margin-left: 50px;" v-click="1" icon="pixel:notebook" color=blue-light>
        <h2 style="font-size: 2rem;">機器學習 (Machine Learning)</h2>
        <h2>讓機器從資料中學習，準確執行特定工作。</h2>
        <Admonition title="Note" width="auto" style="margin-left: 50px;" v-click="2" icon="pixel:notebook" color=indigo-light>
            <h2 style="font-size: 2rem;">深度學習 (Deep Learning)</h2>
            <h2>自動從資料中學習特徵，藉此提高準確度並處理更複雜的模式 </h2>
        </Admonition>
    </Admonition>
</Admonition>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>AI 的發展過程</span>
</h1>

::content::
<AITimeLine :activeIndex="6" />

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>Deep Blue</span><span style="font-size: 2rem; color: gray;">創舉抑或是設局的廣告</span>
</h1>

::content::
<div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
    <div style="width: 66%; padding-right: 20px; box-sizing: border-box;">
        <h2>
            Deep Blue 是 <span style="background:#FFE45E; color:black;">IBM 打造的西洋棋電腦</span>，於 1997 年擊敗世界冠軍加里·卡斯帕羅夫 (Гарри Каспаров)，這是<span style="background:#FFE45E; color:black;">人工智慧發展史上重要的里程碑</span>，然而，Deep Blue 的勝利也引起了許多爭議與質疑。
        </h2>
        <br>
        <h2>
            實際上卡斯帕羅夫在 1996 年勝過 Deep Blue，並在 1997 年的比賽中，<span style="background:#FFE45E; color:black;">Deep Blue 的程式被重新設計與調整</span>，這使得卡斯帕羅夫認為 Deep Blue 的勝利是因為 IBM 的策略與調整，而非 Deep Blue 真正的能力。
        </h2>
    </div>
    <div style="width: 33%; display: flex; flex-direction: column; align-items: center; text-align: center; box-sizing: border-box;">
        深藍機組之一
        <p>
            <a href="https://commons.wikimedia.org/wiki/File:Deep_Blue.jpg#/media/File:Deep_Blue.jpg">
                <img src="https://upload.wikimedia.org/wikipedia/commons/b/be/Deep_Blue.jpg" alt="Deep Blue.jpg" style="display: block; width: 75%; max-width: 300px; margin: 0 auto;">
            </a>
            by <a rel="nofollow" class="external text" href="https://www.flickr.com/photos/jamesthephotographer/">James the photographer</a><br>
            <a href="https://creativecommons.org/licenses/by/2.0" title="Creative Commons Attribution 2.0">CC BY 2.0</a>, 
            <a href="https://commons.wikimedia.org/w/index.php?curid=3511068">Link</a>
        </p>
    </div>
</div>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>AI 的發展過程</span>
</h1>

::content::
<AITimeLine :activeIndex="8" />

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>聊天機器人</span><span style="font-size: 2rem; color: gray;">規則式 AI 的例子</span>
</h1>

::content::
<div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
    <h2>
        隨著通訊軟體演進，多數商家與機關會選擇引入<span style="background:#FFE45E; color:black;">聊天機器人</span>處理部分過往需要客服人員依靠電話或是線上回覆的問題。
        <br>
        以 LINE 聊天機器人為例，會設定所謂的<span style="background:#FFE45E; color:black;">罐頭回覆</span>，使用者透過點擊互動選項會送出<span style="background:#FFE45E; color:black;">特定訊息</span>，聊天機器人會回應<span style="background:#FFE45E; color:black;">已經設定好的回覆訊息</span>，這也是一種 AI。
        <br>
        <br>
        <Admonition title="Note" width="auto" style="margin-left: 50px; margin-right: 50px;" v-click="1" icon="pixel:notebook" color=cyan-light>
            <h2 style="font-size: 2rem;">規則式 AI (Rule-based AI)</h2>
            <h2>if (特定條件) then (特定訊息)</h2>
        </Admonition>
    </h2>
    <img src='./1BvpeZOSWyiJdX-kr-2X-33JF5_d2sRIahGS9eO7KXwk.gif' width=25%>
</div>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>ChatGPT</span><span style="font-size: 2rem; color: gray;">LLM 使 AI 普及化</span>
</h1>

::content::
<div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
    <div style="width: 66%; padding-right: 20px; box-sizing: border-box;">
        <h2>
            2022 年 Open AI 正式推出了使用 <span style="background:#FFE45E; color:black;">GPT-3(Generative Pre-trained Transformer 3)</span> 的 ChatGPT 正式將 AI 帶入一般用戶視野，後續多家公司也陸續推出自家的 AI。
            <br>
            背後的推手便是<span style="background:#FFE45E; color:black;">大型語言模型 (Large Language Model, LLM)</span> 的出現。大型語言模型中最重要的技術：<span style="background:#FFE45E; color:black;">自然語言處理 (Natural Language Processing, NLP)</span>，也就是 AI 能讀懂口語化指令的關鍵，現今也被廣泛用在許多 AI 應用中。
        </h2>
    </div>
    <div class="bg-gray-50/20 rounded-lg p-4" style="width: 33%; box-sizing: border-box;">
        <a href="https://chatgpt.com/" target="_blank" class="flex justify-center pb-2.5 w-full">
            <logos-openai class="text-5xl"/>
        </a>
        <a href="https://claude.ai/" target="_blank" class="flex justify-center pb-2.5 w-full">
            <logos-claude class="text-5xl"/>
        </a>
        <a href="https://gemini.google.com/" target="_blank" class="flex justify-center pb-2.5 w-full">
            <logos-google-gemini class="text-5xl"/>
        </a>
        <a href="https://github.com/copilot" target="_blank" class="flex justify-center pb-2.5 w-full">
            <logos-github-copilot class="text-5xl"/>
        </a>
        <a href="https://grok.com/" target="_blank" class="flex justify-center pb-2.5 w-full">
            <logos-grok class="text-5xl"/>
        </a>
    </div>
</div>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>被 LLM 帶動的生成式 AI</span><span style="font-size: 2rem; color: gray;">以繪圖 AI 為例</span>
</h1>

::content::
<div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
    <div style="width: 66%; padding-right: 20px; box-sizing: border-box;">
        <h2>
            2021 年，GPT-3 發布的隔年，OpenAI 發布了能<span style="background:#FFE45E; color:black;">將文字敘述轉成影像的 DALL·E</span>，這是第一個能將文字敘述轉成影像的 AI，後續也有許多公司推出自家的繪圖 AI。
            <br>
            如 <a href="https://colab.research.google.com/github/alembics/disco-diffusion/blob/main/Disco_Diffusion.ipynb" target="_blank">Disco Diffusion</a>、<a href="https://stablediffusionweb.com/zh-tw" target="_blank">Stable Diffusion</a>、<a href="https://www.midjourney.com/" target="_blank">Midjourney</a>、<a href="https://firefly.adobe.com/" target="_blank">Adobe Firefly</a>、<a href="https://runwayml.com/" target="_blank">Runway</a>、<a href="https://blogs.nvidia.com.tw/blog/ai-decoded-gan-canvas-app/" target="_blank">NVIDIA Canvas</a> 等等，現在這些繪圖 AI 也被廣泛應用在製作文宣等用途。
            <br>
            <!-- 不過也有部分爭議，如 AI 訓練過程中使用的圖片可能是有版權的，或是 AI 生成的圖片是否為自己的作品，這些都是目前社會上對於繪圖 AI 的爭議。 -->
            <br>
            <div v-click="1">
                延伸閱讀  AI 繪圖爭議事件：
                <ul style="margin: 0; padding-left: 20px; line-height: 0.5 !important;">
                    <li style="line-height: 1 !important;">
                        吳淡如電腦繪圖事件
                    </li>
                    <li style="line-height: 0.5 !important;">
                        復興商工 AI 作品得獎爭議
                    </li>
                </ul>
            </div>
        </h2>
    </div>
    <div style="width: 33%; box-sizing: border-box; text-align: center;">
        <div style="width: 100%; height: 350px; overflow: hidden; border-radius: 8px;">
            <img src="./TimeToDisco(0)_0.png" 
                 style="width: 100%; height: 100%; object-fit: cover; object-position: center 30%; display: block;" 
                 alt="Disco Diffusion 示範圖"/>
        </div>
        2022/5/23 由 Disco Diffusion 生成<br>prompt: "cyberpunk city at night"
    </div>
</div>

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>延伸閱讀：生成式 AI</span><span style="font-size: 2rem; color: gray;">COMPUTEX 2023</span>
</h1>

::content::
<v-switch>
    <template #0>
        <div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
            <div style="width: 75%; padding-right: 20px; box-sizing: border-box; text-align: center;">
                <iframe width="640" height="360" src="https://www.youtube.com/embed/i-wpzS9ZsCs?si=tp5EUX5stWUY-bl-&amp;start=2455" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                NVIDIA Keynote at COMPUTEX 2023
            </div>
            <h2 style="width: 25%; padding-right: 20px; box-sizing: border-box;">
                <span style="background:#FFE45E; color:black;">電腦運算能力提升</span>使得 ChatGPT 崛起，
                大型語言模型的發展，特別是<span style="background:#FFE45E; color:black;">Transformer 架構</span> (GPT 的 T) 的出現，使得生成式 AI 的應用更加廣泛。
            </h2>
        </div>
    </template>
    <template #1>
        <div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
            <div style="width: 75%; padding-right: 20px; box-sizing: border-box; text-align: center;">
                <iframe width="640" height="360" src="https://www.youtube.com/embed/i-wpzS9ZsCs?si=Ou2WStDUEP2DiDLf&amp;start=2575&amp;enablejsapi=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                NVIDIA Keynote at COMPUTEX 2023
            </div>
            <h2 style="width: 25%; padding-right: 20px; box-sizing: border-box;">
                有 Transformer 架構的<span style="background:#FFE45E; color:black;">自然語言處理能力</span>，能夠讓 AI 有更多學習資源與產出類型，甚至是多模態的輸入在現今已經可行。
            </h2>
        </div>
    </template>
    <template #2>
        <div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
            <div style="width: 75%; padding-right: 20px; box-sizing: border-box; text-align: center;">
                <iframe width="640" height="360" src="https://www.youtube.com/embed/i-wpzS9ZsCs?si=aqjxwnZoAQJgLc1w&amp;start=2762" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                NVIDIA Keynote at COMPUTEX 2023
            </div>
            <h2 style="width: 25%; padding-right: 20px; box-sizing: border-box;">
                依照提示詞生成旋律並跟著歌唱的範例。
            </h2>
        </div>
    </template>
</v-switch>



<!-- ---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>聊天機器人 2.0</span>
</h1>

::content::
(講木子米?)

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>生成式 AI 與生活</span>
</h1>

::content::
(各領域(繪圖 音樂 程式)應用) -->

---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>本學期內容</span>
</h1>

::content::
<div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
    <div style="width: 50%; padding-right: 20px; box-sizing: border-box;">
        <h2>結合機器學習與基礎硬體，介紹並打造小型邊緣人工智慧 (Edge AI) 專案。</h2>
        <h2 v-click="1">使用 Teachable Machine 製作簡單的影像辨識模型，於電腦運行並透過序列埠控制 Arduino。
        <br>
        所需使用到的工具：<br>
        Web Cam、
        電腦(有python環境)、
        Arduino
        <br>
        使用到的軟體：<br>
        Arduino IDE
        </h2>
    </div>
    <div style="width: 50%; padding-right: 20px; box-sizing: border-box; text-align: center;">
        <h1>DEMO 影片製作中</h1>
        <!-- 辨識物品 七段顯示價格 -->
    </div>
</div>



<!-- ---
transition: slide-left
layout: top-title
color: dark
---

::title::
<h1 style="font-size: 3rem; padding-top: 10px; padding-bottom: 10px; font-weight: bold; display: flex; justify-content: space-between;">
   <span>工業 4.0</span><span style="font-size: 2rem; color: gray;">第四次工業革命</span>
</h1>

::content::
<div style="width: 100%; display: flex; align-items: flex-start; box-sizing: border-box;">
    <Admonition title="Note" width="25%" icon="pixel:notebook" color=indigo-light>
        <h2 style="font-size: 2rem;">
            第一次<br>工業革命
        </h2>
        <h2 style="font-size: 1.5rem;">機械化</h2>
    </Admonition>
    <Admonition title="Note" width="25%" icon="pixel:notebook" color=indigo-light>
        <h2 style="font-size: 2rem;">
            第二次<br>工業革命
        </h2>
        <h2 style="font-size: 1.5rem;">電氣化</h2>
    </Admonition>
    <Admonition title="Note" width="25%" icon="pixel:notebook" color=indigo-light>
        <h2 style="font-size: 2rem;">
            第三次<br>工業革命
        </h2>
        <h2 style="font-size: 1.5rem;">資訊化</h2>
    </Admonition>
    <Admonition title="Note" width="25%" icon="pixel:notebook" color=indigo-light>
        <h2 style="font-size: 2rem;">
            第四次<br>工業革命
        </h2>
        <h2 style="font-size: 1.5rem;">虛實整合</h2>
    </Admonition>
</div>
<h2 style="font-size: 2rem;">
    第四次工業革命
</h2>
<h2 style="font-size: 1.5rem;">
    物聯網 (IoT)、人工智慧 (AI)、大數據 (Big Data)、雲端運算 (Cloud Computing)
</h2> -->