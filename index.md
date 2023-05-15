
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
            margin-left: -1% !important;
            max-width: 1200px !important;
            display: block !important;
        }
</style>
    
<style>
nav {
  width: 100%;
  background-color: #dddddd;
  margin: 0;
  padding: 0;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

nav li {
  float: left;
  margin: 0 10px !important;
}

nav a {
  display: block;
  padding: 10px;
  text-decoration: none;
  color: #000000;
}

nav a:hover {
  background-color: #ffffff;
  color: #000000;
}
</style>

# Happy Labz Technologies

<div>
<nav class="px-3 markdown-body">
  <ul>
    <li><a href="index.md">Home</a></li>
    <li><a href="navPages/how_to_use.md">How to Use</a></li>
    <li><a href="navPages/use_case.md">Use Case</a></li>
    <li><a href="navPages/contact.md">Contact</a></li>
  </ul>
</nav>
</div>

<div class="my-data px-3 my-5 markdown-body">
    <div class="container-data">
    <div class="box gray">
        <h2 id="aapl"><a href="{% link AAPL.md %}">AAPL</a></h2>
        <ul>
            <li>LAST: <b><span style="color: #ff0000;">Short</span></b> Apr 05 2023 15:00 PST</li>
            <li>DELTA: <b><span style="color: #167816;">1.26 (0.77%)</span></b> as of close May 15 2023</li>
        </ul>
    </div>
    <div class="box gray">
        <h2 id="amzn"><a href="{% link AMZN.md %}">AMZN</a></h2>
        <ul>
            <li>LAST: <b><span style="color: #167816;">Long</span></b> Nov 11 2022 15:00 PST</li>
            <li>DELTA: <b><span style="color: #167816;">6.17 (6.12%)</span></b> as of close May 15 2023</li>
        </ul>
    </div>
    <div class="box gray">
        <h2 id="googl"><a href="{% link GOOGL.md %}">GOOGL</a></h2>
        <ul>
            <li>LAST: <b><span style="color: #ff0000;">Short</span></b> Mar 28 2023 15:00 PST</li>
            <li>DELTA: <b><span style="color: #167816;">4.38 (4.34%)</span></b> as of close May 15 2023</li>
        </ul>
    </div>
    <div class="box gray">
        <h2 id="tsla"><a href="{% link TSLA.md %}">TSLA</a></h2>
        <ul>
            <li>LAST: <b><span style="color: #ff0000;">Short</span></b> Feb 16 2023 15:00 PST</li>
            <li>DELTA: <b><span style="color: #ff0000;">-36.96 (-18.29%)</span></b> as of close May 15 2023</li>
        </ul>
    </div>
    <div class="box gray">
        <h2 id="spy"><a href="{% link SPY.md %}">SPY</a></h2>
        <ul>
            <li>LAST: <b><span style="color: #ff0000;">Short</span></b> Apr 20 2023 15:00 PST</li>
            <li>DELTA: <b><span style="color: #167816;">0.32 (0.08%)</span></b> as of close May 15 2023</li>
        </ul>
    </div>
    <div class="box gray">
        <h2 id="UNK"><a href="{% link NEXT.md %}">Choose your Ticker</a></h2>
        <ul>
            <li>LAST: <b>???</b></li>
            <li>DELTA: <b>???</b> as of close May 15 2023</li>
        </ul>
    </div>
</div></div>