
<style>
.hits {
            border-collapse: collapse;
            width: 100%;
        }
        .hits th, td {
            padding: 8px;
            border-bottom: 1px solid #ddd;
        }
        
        .hits td {text-align: right;}
        .hits th {text-align: left;}
        
        .hits tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        
        .chartCol {
            width: 50%;
            float: left;
            padding: 20px;
        }  
</style>
    
<style>
nav {
  width: 100%;
  background-color: #0369a1;
  margin: 0;
  padding: 0;
  border-radius: 25px;
  border: 1px solid black;
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
  color: #ffffff;
  font-weight: 600;
  font-size: 18px;
}

nav a:hover {
  background-color: #ffffff;
  color: #000000;
}
</style>

<style>
footer {
  margin-top: 10px;
  padding: 10px;
}

footer p {
  color: #000000;
  font-size: 12px;
  margin-bottom: 10px !important;
}

footer ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  align: center;
}

footer li {
  display: inline-block;
  margin: 0 10px;
  text-align: center;
  width: 100%
}

footer a {
  color: #000000;
  text-decoration: none;
}

footer p {
    font-size: 11px;
    text-align: center;
    margin: 5px;
}
</style>

# Happy Labz Technologies

<div>
<nav class="px-3 markdown-body">
  <ul>
    <li><a href="{% link index.md %}">Home</a></li>
    <li><a href="{% link navPages/how_to_use.md %}">How to Use</a></li>
    <li><a href="{% link usecase/usecase.md %}">Use Case</a></li>
    <li><a href="{% link navPages/contact.md %}">Contact</a></li>
  </ul>
</nav>
</div>

<br>

<table class="hits">
    <tr>
        <th>No.</th>
        <th>Direction</th>
        <th>Date</th>
        <th>Move (Percent)</th>
        <th>Move (Cumulative Percentage Gain)</th>
      </tr>
    <tr>
        <td>1</td>
        <td>Short</td>
        <td>Apr 05 2022 15:00 PST</td>
        <td>-4.17 %</td>
        <td>4.17 %</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Short</td>
        <td>Apr 06 2022 15:00 PST</td>
        <td>-32.32 %</td>
        <td>36.49 %</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Long</td>
        <td>May 26 2022 15:00 PST</td>
        <td>0.07 %</td>
        <td>36.57 %</td>
    </tr>
    <tr>
        <td>4</td>
        <td>Long</td>
        <td>Jun 22 2022 15:00 PST</td>
        <td>22.06 %</td>
        <td>58.63 %</td>
    </tr>
    <tr>
        <td>5</td>
        <td>Short</td>
        <td>Aug 05 2022 15:00 PST</td>
        <td>0.78 %</td>
        <td>57.85 %</td>
    </tr>
    <tr>
        <td>6</td>
        <td>Short</td>
        <td>Aug 08 2022 15:00 PST</td>
        <td>-0.63 %</td>
        <td>58.48 %</td>
    </tr>
    <tr>
        <td>7</td>
        <td>Short</td>
        <td>Sep 22 2022 15:00 PST</td>
        <td>-57.32 %</td>
        <td>115.80 %</td>
    </tr>
    <tr>
        <td>8</td>
        <td>Long</td>
        <td>Dec 30 2022 15:00 PST</td>
        <td>64.02 %</td>
        <td>179.82 %</td>
    </tr>
    <tr>
        <td>9</td>
        <td>Short</td>
        <td>Feb 16 2023 15:00 PST</td>
        <td>-17.33 %</td>
        <td>197.14 %</td>
    </tr>
    
</table>
<table class="hits">
    <thead>
        <th></th>
        <th>Date Range</th>
        <th>Move Percentage Gain</th>
    </thead>
    <tbody>
        <tr>
            <td>TSLA</td>
            <td>2022-04-05 13:00:00 - 2023-02-16 13:00:00</td>
            <td>197.14 %</td>
        </tr>
        <tr>
            <td>S&P 500</td>
            <td>2022-04-05 13:00:00 - 2023-02-16 13:00:00</td>
            <td>-9.48 %</td>
        </tr>
        <tr>
            <td></td>
            <td style="text-align: right;"><b>Profit Using HLT vs. Holding S&P 500:</b></td>
            <td>206.62 %</td>
        </tr>
    </tbody>
</table>

![Plot](charts/TSLAstatic.png)
<footer>
    <p>The information provided on this website is for informational purposes only and does not constitute professional financial advice; please consult with a financial advisor before making any investment decisions.</p>
  <ul>
    <li>Copyright &copy; 2023 HappyLabz Technologies. All rights reserved.</li>
  </ul>
</footer>
