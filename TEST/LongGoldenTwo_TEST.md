# Long Golden Two 
- Symbol: TEST
- Date Range: 3/19/22 - 5/22/22
- Trading Period: 7:20-12:30
- Number of Trades: 4

![Plot](LongGoldenTwoTEST.png)

| Name | Win Percent | Profit | Avg Profit / Trade |     | Name | Win Percent | Profit | Avg Profit / Trade |
| ---- | ----------- | ------ | ------------------ | --- | ---- | ----------- | ------ | ------------------ |
| Sorted By <br> Profit | | | | | Sorted By <br> Win Percentage ||||
| Thirty-Seven | 75.00 | 35500.00 | 8875.00 |     | Thirty-Seven | 75.00 | 35500.00 | 8875.00 |
| Thirty-Six | 50.00 | 14125.00 | 3531.25 |     | Thirty-Six | 50.00 | 14125.00 | 3531.25 |
| Thirty-Five | 25.00 | -3000.00 | -750.00 |     | Thirty-Five | 25.00 | -3000.00 | -750.00 |

### Test Thirty-Five
* Sell when the linear regression slope changes to negative
* No Stoploss
* Results:
```
Total Trades: 4
Percent Up: 25.00
Percent Down: 75.00
Total Points Moved Up: -6.00
Potential Profit: -3000.00
Total Points Ups: 10.00 Count Ups: 1
Total Points Downs: -16.00 Count Downs: 3
```

<details><summary>Trades</summary>

<code>In: 2022-07-01 06:46:00		Out: 2022-07-01 06:55:05		Total Position Time: 09:05		Total Move Up: 10.00		Total to Date: 10.00</code> <br />
<code>In: 2022-07-01 11:05:00		Out: 2022-07-01 11:09:05		Total Position Time: 04:05		Total Move Up: -3.00		Total to Date: 7.00</code> <br />
<code>In: 2022-07-05 07:39:00		Out: 2022-07-05 07:44:05		Total Position Time: 05:05		Total Move Up: -8.75		Total to Date: -1.75</code> <br />
<code>In: 2022-07-05 08:59:00		Out: 2022-07-05 09:04:05		Total Position Time: 05:05		Total Move Up: -4.25		Total to Date: -6.00</code> <br />


</details>

### Test Thirty-Six
* Sell when the bias changes to negative
* No Stoploss
* Results:
```
Total Trades: 4
Percent Up: 50.00
Percent Down: 50.00
Total Points Moved Up: 28.25
Potential Profit: 14125.00
Total Points Ups: 81.75 Count Ups: 2
Total Points Downs: -53.50 Count Downs: 2
```

<details><summary>Trades</summary>

<code>In: 2022-07-01 06:46:00		Out: 2022-07-01 07:20:05		Total Position Time: 34:05		Total Move Up: -24.00		Total to Date: -24.00</code> <br />
<code>In: 2022-07-01 11:05:00		Out: 2022-07-01 12:31:00		Total Position Time: 86:00		Total Move Up: 26.00		Total to Date: 2.00</code> <br />
<code>In: 2022-07-05 07:39:00		Out: 2022-07-05 08:06:05		Total Position Time: 27:05		Total Move Up: -29.50		Total to Date: -27.50</code> <br />
<code>In: 2022-07-05 08:59:00		Out: 2022-07-05 12:31:00		Total Position Time: 212:00		Total Move Up: 55.75		Total to Date: 28.25</code> <br />


</details>

### Test Thirty-Seven
* Sell when the STDEV slope changes to negative
* No Stoploss
* Results:
```
Total Trades: 4
Percent Up: 75.00
Percent Down: 25.00
Total Points Moved Up: 71.00
Potential Profit: 35500.00
Total Points Ups: 91.25 Count Ups: 3
Total Points Downs: -20.25 Count Downs: 1
```

<details><summary>Trades</summary>

<code>In: 2022-07-01 06:46:00		Out: 2022-07-01 07:01:05		Total Position Time: 15:05		Total Move Up: 9.50		Total to Date: 9.50</code> <br />
<code>In: 2022-07-01 11:05:00		Out: 2022-07-01 12:31:00		Total Position Time: 86:00		Total Move Up: 26.00		Total to Date: 35.50</code> <br />
<code>In: 2022-07-05 07:39:00		Out: 2022-07-05 07:47:05		Total Position Time: 08:05		Total Move Up: -20.25		Total to Date: 15.25</code> <br />
<code>In: 2022-07-05 08:59:00		Out: 2022-07-05 12:31:00		Total Position Time: 212:00		Total Move Up: 55.75		Total to Date: 71.00</code> <br />


</details>