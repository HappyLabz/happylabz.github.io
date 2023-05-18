
<style>
    .container-data {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            grid-template-rows: repeat(auto-fit, minmax(180px, 1fr));
            grid-gap: 10px;
        }

        .box {
            min-width: 250px;
            max-width: 350px;
            height: 230px;
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
</style>
    
## Current Live Indicators

<div class="my-data px-3 my-5 markdown-body">
    <div class="container-data">
    <div class="box gray" onclick="location.href='{% link navigation/blocked.md %}';">
        <h2 id="aapl"><a href="{% link navigation/blocked.md %}">AAPL</a></h2>
        <ul>
            <li>LAST: <b><span style="color: #b91c1c;">Short</span></b> May 16 2023 15:00 PST</li>
            <li>DELTA: <b><span style="color: #167816;">0.62 (0.36%)</span></b> as of close<br>May 18 2023</li>
        </ul>
    </div>
    <div class="box gray" onclick="location.href='{% link navigation/blocked.md %}';">
        <h2 id="amzn"><a href="{% link navigation/blocked.md %}">AMZN</a></h2>
        <ul>
            <li>LAST: <b><span style="color: #167816;">Long</span></b> Mar 14 2023 15:00 PST</li>
            <li>DELTA: <b><span style="color: #167816;">20.62 (21.73%)</span></b> as of close<br>May 18 2023</li>
        </ul>
    </div>
    <div class="box gray" onclick="location.href='{% link navigation/blocked.md %}';">
        <h2 id="msft"><a href="{% link navigation/blocked.md %}">MSFT</a></h2>
        <ul>
            <li>LAST: <b><span style="color: #167816;">Long</span></b> Mar 03 2023 15:00 PST</li>
            <li>DELTA: <b><span style="color: #167816;">58.71 (23.00%)</span></b> as of close<br>May 18 2023</li>
        </ul>
    </div>
    <div class="box gray" onclick="location.href='{% link TSLA.md %}';">
        <h2 id="tsla"><a href="{% link TSLA.md %}">TSLA <span style="color:#0369a1;">&bigstar;</span></a></h2>
        <ul>
            <li>LAST: <b><span style="color: #b91c1c;">Short</span></b> Feb 16 2023 15:00 PST</li>
            <li>DELTA: <b><span style="color: #b91c1c;">-28.18 (-13.95%)</span></b> as of close<br>May 18 2023</li>
        </ul>
    </div>
    <div class="box gray" onclick="location.href='{% link navigation/blocked.md %}';">
        <h2 id="spy"><a href="{% link navigation/blocked.md %}">SPY</a></h2>
        <ul>
            <li>LAST: <b><span style="color: #167816;">Long</span></b> Mar 14 2023 15:00 PST</li>
            <li>DELTA: <b><span style="color: #167816;">23.50 (6.00%)</span></b> as of close<br>May 18 2023</li>
        </ul>
    </div>
    <div class="box gray" onclick="location.href='{% link NEXT.md %}';">
        <h2 id="UNK"><a href="{% link NEXT.md %}">Pick a Ticker</a></h2>
        <ul>
            <li> Financial Professionals can request  HappyLabz Technologies software for any Stock or ETF.</li>
        </ul>
    </div>
</div></div>