
<style>
    .container-data {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(295px, 1fr));
        grid-template-rows: repeat(auto-fit, minmax(180px, 1fr));
        grid-gap: 10px;
    }

    .box {
        min-width: 290px;
        max-width: 350px;
        height: 265px;
        border: 1px solid black;
        margin: 2px;
        width: 100%;
    }

    .box h2 {
        padding: 10px;
        padding-top: 34px;
        margin-top: 0 !important;
        width: 100%;
    }

    .box a:link, .box a:visited {
        color: #ffffff;
    }

    .box ul {
        margin: 5px;
    }
    
    .atUpperPriceLine h2 {
        border-top: 5px solid yellow !important;
        padding-top: 29px !important;
    }

    .atLowerPriceLine h2 {
        border-bottom: 5px solid yellow !important;
        margin-bottom: 11px !important;
    }

    .gray {
        background-color: #a2a2a2;
        border: 5px solid #353535;
    }

    .gray h2 {
        background-color: #525252;
        border-bottom: 1px solid black;
        color: #ffffff;
    }

    .red {
        background-color: #faaaaa;
        border: 5px solid #6e0000;
    }

    .red h2 {
        background-color: #b80000;
        border-bottom: 1px solid black;
        color: #ffffff;
    }

    .green {
        background-color: #92d98f;
        border: 5px solid #015e01;
    }

    .green h2 {
        background-color: #004225;
        border-bottom: 1px solid black;
        color: #ffffff;
    }

    .my-data {
        margin-right: auto !important;
        margin-left: auto !important;
        align-content: center;
        width: 100% !important;
        max-width: 1200px !important;
        display: block !important;
    }
    
    .header {
      display: grid;
      align-items: center;
      justify-items: center;
      row-gap: 1rem;
      grid-template-columns: 1fr;
      margin: 16px;
    }
</style>
    
<h1 class="header"> Current Live Indicators</h1>

<div style="display:none;">
<h3 class="header">Happy 5:</h3>
<h1 class="header"><span style="color: #b91c1c;">-2.09 %</span></h1>
</div>

<div class="my-data px-3 my-5 markdown-body">
    <div class="container-data">
    <div class="box gray" onclick="location.href='{% link navigation/blocked.md %}';">
        <h2 id="aapl"><a href="{% link navigation/blocked.md %}">AAPL</a></h2>
        <ul>
            <li>DAY: <b><span style="color: #b91c1c;">Short</span></b> at 189.79 as of close <br>Nov 27 2023</li>
            <li>DELTA: <b><span style="color: #b91c1c;">-10.13 (-5.34%)</span></b> as of close<br>Mar 01 2024</li>
            <!--<li>WEEK: <b><span style="color: #167816;">Long</span></b> at 134.76 as of close <br>Jan 13 2023</li>-->
        </ul>
    </div>
    <div class="box gray atUpperPriceLine" onclick="location.href='{% link navigation/blocked.md %}';">
        <h2 id="amzn"><a href="{% link navigation/blocked.md %}">AMZN</a></h2>
        <ul>
            <li>DAY: <b><span style="color: #b91c1c;">Short</span></b> at 155.20 as of close <br>Jan 31 2024</li>
            <li>DELTA: <b><span style="color: #167816;">23.02 (14.83%)</span></b> as of close<br>Mar 01 2024</li>
            <!--<li>WEEK: <b><span style="color: #167816;">Long</span></b> at 98.12 as of close <br>Jan 13 2023</li>-->
        </ul>
    </div>
    <div class="box gray" onclick="location.href='{% link navigation/blocked.md %}';">
        <h2 id="msft"><a href="{% link navigation/blocked.md %}">MSFT</a></h2>
        <ul>
            <li>DAY: <b><span style="color: #b91c1c;">Short</span></b> at 403.78 as of close <br>Feb 01 2024</li>
            <li>DELTA: <b><span style="color: #167816;">11.72 (2.90%)</span></b> as of close<br>Mar 01 2024</li>
            <!--<li>WEEK: <b><span style="color: #167816;">Long</span></b> at 241.22 as of close <br>Nov 18 2022</li>-->
        </ul>
    </div>
    <div class="box gray atLowerPriceLine" onclick="location.href='{% link TSLA.md %}';">
        <h2 id="tsla"><a href="{% link TSLA.md %}">TSLA <span style="color:#0369a1;">&bigstar;</span></a></h2>
        <ul>
            <li>DAY: <b><span style="color: #167816;">Long</span></b> at 191.59 as of close <br>Jan 30 2024</li>
            <li>DELTA: <b><span style="color: #167816;">11.05 (5.77%)</span></b> as of close<br>Mar 01 2024</li>
            <!--<li>WEEK: <b><span style="color: #167816;">Long</span></b> at 177.90 as of close <br>Jan 27 2023</li>-->
        </ul>
    </div>
    <div class="box gray" onclick="location.href='{% link navigation/blocked.md %}';">
        <h2 id="spy"><a href="{% link navigation/blocked.md %}">SPY</a></h2>
        <ul>
            <li>DAY: <b><span style="color: #b91c1c;">Short</span></b> at 494.08 as of close <br>Feb 13 2024</li>
            <li>DELTA: <b><span style="color: #167816;">18.77 (3.80%)</span></b> as of close<br>Mar 01 2024</li>
            <!--<li>WEEK: <b><span style="color: #167816;">Long</span></b> at 374.29 as of close <br>Oct 21 2022</li>-->
        </ul>
    </div>
    <div class="box gray" onclick="location.href='{% link NEXT.md %}';">
        <h2 id="UNK"><a href="{% link NEXT.md %}">Pick a Ticker</a></h2>
        <ul>
            <li> Financial Professionals can request  HappyLabz Technologies software for any Stock or ETF.</li>
        </ul>
    </div>
</div></div>