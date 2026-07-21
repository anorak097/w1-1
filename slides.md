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
    中文房間論證即是針對圖靈測試的質疑，當一個不懂中文人依靠文獻通過了中文對話的模仿遊戲，不懂中文的那人還是不懂。
    <br>
    換成電腦來說，即使電腦通過了圖靈測試，並不代表電腦擁有該方面的智慧，而有可能是外人寫好的邏輯、演算法足以使其運算出了最適合的回應。這代表其可能並不真正擁有處理該問題的「智慧」。
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