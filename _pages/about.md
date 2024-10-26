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


I am Hou Shengren, currently a PhD candidate at TU Delft, specializing in short-term power market trading and research. My focus is on short-term power derivatives, day-ahead and intraday trading, and physical transmission right auctions. My goal is to optimize trading strategies to achieve high profitability in dynamic markets.

My career goal is to continue refining my expertise in short-term power trading while building and leading a high-performance team or Company. I aim to leverage both fundamental and quantitative strategies to achieve stable profits and create a successful trading company.


</div>

<div id="chinese" class="tabcontent">


我是侯胜任，是代尔夫特理工大学的博士生，专注于短期电力市场交易和研究。我的研究方向包括短期电力衍生品、日前和日内交易，以及物理传输权拍卖。我的目标是通过优化交易策略，在动态市场中实现高盈利。

我的职业目标是继续在短期电力交易方面精进，并带领一个高效的团队或公司，利用基本面和量化策略来实现稳定的盈利目标，打造一个成功的交易团队。

我的研究和工作经验涵盖了短期电力交易、算法开发以及电力市场的动态分析，希望通过持续的研究和实践，推动电力市场的高效运行与创新发展。

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
