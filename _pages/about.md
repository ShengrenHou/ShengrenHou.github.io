---
permalink: /
title: "Welcome to Hou Shengren's website"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  #tabs {
    margin-bottom: 20px;
  }
  #tabs button {
    padding: 10px 20px;
    margin-right: 10px;
    cursor: pointer;
    background-color: #007acc;
    color: white;
    border: none;
    border-radius: 4px;
  }
  #tabs button:hover {
    background-color: #005f99;
  }
  .tabcontent {
    display: none;
  }
  .tabcontent.active {
    display: block;
  }
</style>

<div id="tabs">
  <button onclick="openTab('english')">English</button>
  <button onclick="openTab('chinese')">中文</button>
</div>

<div id="english" class="tabcontent active">


I am Hou Shengren, an power market expert. I know almost everything about the power system and power market across EU, USA, Japan and China. My bachelor, master and PhD are all related to the power system and power market. I am a short-term power trader and reshearcher in the Netherlands. My focus is on short-term power derivatives, day-ahead and intraday trading, and physical transmission right auctions.

My career goal is to continue refining my expertise in short-term power trading while building and leading a high-performance team or Company. I aim to leverage both fundamental and quantitative strategies to achieve stable profits and create a successful trading company.

In college, I really enjoyed playing League of Legends and was quite good at it. However, now I only watch match videos and no longer play the game. Currently, in my free time, I enjoy reading history books, participating in non-profit activities, and staying fit.



</div>

<div id="chinese" class="tabcontent">


我是侯胜任，电力系统和电力市场专家。我了解欧洲、美国、日本和中国的电力系统和电力市场。我的本科、硕士和博士学位都与电力系统和电力市场相关。我目前在荷兰担任短期电力交易员和研究员，专注于短期电力衍生品、日前和日内交易，以及物理传输权拍卖。

我的职业目标是继续在短期电力交易方面精进，并带领一个高效的团队或公司，利用基本面和量化策略来实现稳定的盈利，打造一个成功的交易公司。

在大学期间，我特别喜欢玩《英雄联盟》，而且打得很好。不过现在，我只看看比赛视频，不再玩游戏了。目前，我空余时间喜欢读历史书、参与非营利组织的活动以及健身。


</div>

<script>
function openTab(tabName) {
  var i;
  var x = document.getElementsByClassName("tabcontent");
  for (i = 0; i < x.length; i++) {
    x[i].classList.remove("active");
  }
  document.getElementById(tabName).classList.add("active");
}
</script>
