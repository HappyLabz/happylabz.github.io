
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

<style>
footer {
  background-color: #dddddd;
  margin-top: 10px;
  padding: 10px;
}

footer p {
  color: #000000;
  font-size: 12px;
}

footer ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

footer li {
  display: inline-block;
  margin: 0 10px;
}

footer a {
  color: #000000;
  text-decoration: none;
}
</style>

# Happy Labz Technologies

<div>
<nav class="px-3 markdown-body">
  <ul>
    <li><a href="{% link index.md %}">Home</a></li>
    <li><a href="{% link navPages/how_to_use.md %}">How to Use</a></li>
    <li><a href="{% link navPages/use_case.md %}">Use Case</a></li>
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
        <th>Move (Cumulative Percentage)</th>
      </tr>
    <tr>
        <td>1</td>
        <td>Long</td>
        <td>Sep 07 2022 15:00 PST</td>
        <td>21.18</td>
        <td>21.18</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Long</td>
        <td>Sep 08 2022 15:00 PST</td>
        <td>20.98</td>
        <td>42.16</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Long</td>
        <td>Mar 03 2023 15:00 PST</td>
        <td>22.51</td>
        <td>64.66</td>
    </tr>
    
</table>

![Plot](charts/MSFT.png)
<footer>
    <ul>
        <li>Copyright &copy; 2023 HappyLabz Technologies. All rights reserved.</li>
        <li style="float: right"><a href="mailto:mark@happylabz.tech?subject=Let's Talk">Contact Us</a></li>
    </ul>
</footer>
