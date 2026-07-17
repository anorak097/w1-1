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
    <div style="width: 100%; display: flex; align-items: center-top;">
        <div style="flex: 3;">
            <h2 style="font-size: 2.5rem;">WHY?</h2>
            <h2>運作模式是在理解恩尼格碼結構與運作模式後，利用機器快速運算出所有可能性</h2>
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
   模仿遊戲與圖靈測試
</h1>

::content::
https://en.wikipedia.org/wiki/Turing_test#Versions