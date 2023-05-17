
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
        <td>Apr 01 2022 15:00 PST</td>
        <td>-1.42 %</td>
        <td>1.42 %</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Short</td>
        <td>Apr 06 2022 15:00 PST</td>
        <td>-0.18 %</td>
        <td>1.60 %</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Short</td>
        <td>Aug 19 2022 15:00 PST</td>
        <td>-16.19 %</td>
        <td>17.79 %</td>
    </tr>
    <tr>
        <td>4</td>
        <td>Long</td>
        <td>Oct 18 2022 15:00 PST</td>
        <td>4.14 %</td>
        <td>21.93 %</td>
    </tr>
    <tr>
        <td>5</td>
        <td>Long</td>
        <td>Nov 11 2022 15:00 PST</td>
        <td>-13.41 %</td>
        <td>8.52 %</td>
    </tr>
    <tr>
        <td>6</td>
        <td>Long</td>
        <td>Jan 06 2023 15:00 PST</td>
        <td>12.57 %</td>
        <td>21.09 %</td>
    </tr>
    <tr>
        <td>7</td>
        <td>Long</td>
        <td>Mar 02 2023 15:00 PST</td>
        <td>17.93 %</td>
        <td>39.02 %</td>
    </tr>
    <tr>
        <td>8</td>
        <td>Short</td>
        <td>May 15 2023 15:00 PST</td>
        <td>0.10 %</td>
        <td>38.92 %</td>
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
            <td>AAPL</td>
            <td>2022-04-01 13:00:00 - 2023-05-15 13:00:00</td>
            <td>38.92 %</td>
        </tr>
        <tr>
            <td>S&P 500</td>
            <td>2022-04-01 13:00:00 - 2023-05-15 13:00:00</td>
            <td>-8.81 %</td>
        </tr>
        <tr>
            <td></td>
            <td style="text-align: right;"><b>Profit Using HLT vs. Holding S&P 500:</b></td>
            <td>47.73 %</td>
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
