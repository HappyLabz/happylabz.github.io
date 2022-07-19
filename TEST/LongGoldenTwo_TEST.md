# Long Golden Two 
- Symbol: TEST
- Date Range: 3/19/22 - 5/22/22
- Trading Period: 7:20-12:30
- Number of Trades: 9

![Plot](LongGoldenTwoTEST.png)

| Name | Win Percent | Profit | Avg Profit / Trade |     | Name | Win Percent | Profit | Avg Profit / Trade |
| ---- | ----------- | ------ | ------------------ | --- | ---- | ----------- | ------ | ------------------ |
| Sorted By <br> Profit | | | | | Sorted By <br> Win Percentage ||||
| Seventy-Two | 88.89 | 200375.00 | 22263.89 |     | Seventy-Two | 88.89 | 200375.00 | 22263.89 |
| Seventy-Four | 44.44 | 4000.00 | 444.44 |     | Seventy-Four | 44.44 | 4000.00 | 444.44 |
| Seventy-Five | 44.44 | -2250.00 | -250.00 |     | Seventy-Five | 44.44 | -2250.00 | -250.00 |
| Seventy-Three | 44.44 | -14750.00 | -1638.89 |     | Seventy-Three | 44.44 | -14750.00 | -1638.89 |

### Test Seventy-Two
* Sell when the linear regression slope is negative
* No Stoploss
* Results:
```
Total Trades: 9
Percent Up: 88.89
Percent Down: 11.11
Total Points Moved Up: 400.75
Potential Profit: 200375.00
Total Points Ups: 423.25 Count Ups: 8
Total Points Downs: -22.50 Count Downs: 1
```

<details><summary>Trades</summary>

<code>In: 2022-07-08 06:50:00		Out: 2022-07-08 06:31:05		Total Position Time: 1421:05		Total Move Up: 2.25		Total to Date: 2.25</code> <br />
<code>In: 2022-07-08 07:35:00		Out: 2022-07-08 06:31:05		Total Position Time: 1376:05		Total Move Up: -22.50		Total to Date: -20.25</code> <br />
<code>In: 2022-07-11 08:45:00		Out: 2022-07-08 06:31:05		Total Position Time: 1306:05		Total Move Up: 22.75		Total to Date: 2.50</code> <br />
<code>In: 2022-07-11 09:45:00		Out: 2022-07-08 06:45:05		Total Position Time: 1260:05		Total Move Up: 31.25		Total to Date: 33.75</code> <br />
<code>In: 2022-07-12 06:50:00		Out: 2022-07-08 06:31:05		Total Position Time: 1421:05		Total Move Up: 24.75		Total to Date: 58.50</code> <br />
<code>In: 2022-07-12 08:40:00		Out: 2022-07-08 06:31:05		Total Position Time: 1311:05		Total Move Up: 25.00		Total to Date: 83.50</code> <br />
<code>In: 2022-07-13 06:50:00		Out: 2022-07-08 06:31:05		Total Position Time: 1421:05		Total Move Up: 90.25		Total to Date: 173.75</code> <br />
<code>In: 2022-07-13 07:50:00		Out: 2022-07-08 06:38:05		Total Position Time: 1368:05		Total Move Up: 82.50		Total to Date: 256.25</code> <br />
<code>In: 2022-07-14 08:20:00		Out: 2022-07-08 06:40:05		Total Position Time: 1340:05		Total Move Up: 144.50		Total to Date: 400.75</code> <br />


</details>

### Test Seventy-Three
* Sell when the linear regression slope changes to negative
* No Stoploss
* Results:
```
Total Trades: 9
Percent Up: 44.44
Percent Down: 55.56
Total Points Moved Up: -29.50
Potential Profit: -14750.00
Total Points Ups: 12.00 Count Ups: 4
Total Points Downs: -41.50 Count Downs: 5
```

<details><summary>Trades</summary>

<code>In: 2022-07-08 06:50:00		Out: 2022-07-08 07:09:05		Total Position Time: 19:05		Total Move Up: -4.25		Total to Date: -4.25</code> <br />
<code>In: 2022-07-08 07:35:00		Out: 2022-07-08 07:45:05		Total Position Time: 10:05		Total Move Up: 4.75		Total to Date: 0.50</code> <br />
<code>In: 2022-07-11 08:45:00		Out: 2022-07-11 08:50:05		Total Position Time: 05:05		Total Move Up: -4.00		Total to Date: -3.50</code> <br />
<code>In: 2022-07-11 09:45:00		Out: 2022-07-11 10:01:05		Total Position Time: 16:05		Total Move Up: 1.25		Total to Date: -2.25</code> <br />
<code>In: 2022-07-12 06:50:00		Out: 2022-07-12 07:13:05		Total Position Time: 23:05		Total Move Up: -11.50		Total to Date: -13.75</code> <br />
<code>In: 2022-07-12 08:40:00		Out: 2022-07-12 08:56:05		Total Position Time: 16:05		Total Move Up: -3.50		Total to Date: -17.25</code> <br />
<code>In: 2022-07-13 06:50:00		Out: 2022-07-13 07:11:05		Total Position Time: 21:05		Total Move Up: -18.25		Total to Date: -35.50</code> <br />
<code>In: 2022-07-13 07:50:00		Out: 2022-07-13 07:59:05		Total Position Time: 09:05		Total Move Up: 3.50		Total to Date: -32.00</code> <br />
<code>In: 2022-07-14 08:20:00		Out: 2022-07-14 08:31:05		Total Position Time: 11:05		Total Move Up: 2.50		Total to Date: -29.50</code> <br />


</details>

### Test Seventy-Four
* Sell when the bias changes to negative
* No Stoploss
* Results:
```
Total Trades: 9
Percent Up: 44.44
Percent Down: 55.56
Total Points Moved Up: 8.00
Potential Profit: 4000.00
Total Points Ups: 40.50 Count Ups: 4
Total Points Downs: -32.50 Count Downs: 5
```

<details><summary>Trades</summary>

<code>In: 2022-07-08 06:50:00		Out: 2022-07-08 06:52:05		Total Position Time: 02:05		Total Move Up: -6.50		Total to Date: -6.50</code> <br />
<code>In: 2022-07-08 07:35:00		Out: 2022-07-08 08:35:00		Total Position Time: 60:00		Total Move Up: 13.00		Total to Date: 6.50</code> <br />
<code>In: 2022-07-11 08:45:00		Out: 2022-07-11 08:48:05		Total Position Time: 03:05		Total Move Up: -4.50		Total to Date: 2.00</code> <br />
<code>In: 2022-07-11 09:45:00		Out: 2022-07-11 10:19:00		Total Position Time: 34:00		Total Move Up: 9.25		Total to Date: 11.25</code> <br />
<code>In: 2022-07-12 06:50:00		Out: 2022-07-12 06:53:05		Total Position Time: 03:05		Total Move Up: 3.25		Total to Date: 14.50</code> <br />
<code>In: 2022-07-12 08:40:00		Out: 2022-07-12 09:19:05		Total Position Time: 39:05		Total Move Up: -0.25		Total to Date: 14.25</code> <br />
<code>In: 2022-07-13 06:50:00		Out: 2022-07-13 06:58:05		Total Position Time: 08:05		Total Move Up: -9.00		Total to Date: 5.25</code> <br />
<code>In: 2022-07-13 07:50:00		Out: 2022-07-13 08:47:00		Total Position Time: 57:00		Total Move Up: -12.25		Total to Date: -7.00</code> <br />
<code>In: 2022-07-14 08:20:00		Out: 2022-07-14 09:11:00		Total Position Time: 51:00		Total Move Up: 15.00		Total to Date: 8.00</code> <br />


</details>

### Test Seventy-Five
* Sell when the STDEV slope changes to negative
* No Stoploss
* Results:
```
Total Trades: 9
Percent Up: 44.44
Percent Down: 55.56
Total Points Moved Up: -4.50
Potential Profit: -2250.00
Total Points Ups: 13.00 Count Ups: 4
Total Points Downs: -17.50 Count Downs: 5
```

<details><summary>Trades</summary>

<code>In: 2022-07-08 06:50:00		Out: 2022-07-08 06:51:05		Total Position Time: 01:05		Total Move Up: -5.50		Total to Date: -5.50</code> <br />
<code>In: 2022-07-08 07:35:00		Out: 2022-07-08 07:51:05		Total Position Time: 16:05		Total Move Up: 0.50		Total to Date: -5.00</code> <br />
<code>In: 2022-07-11 08:45:00		Out: 2022-07-11 08:47:05		Total Position Time: 02:05		Total Move Up: -3.25		Total to Date: -8.25</code> <br />
<code>In: 2022-07-11 09:45:00		Out: 2022-07-11 10:04:05		Total Position Time: 19:05		Total Move Up: 8.00		Total to Date: -0.25</code> <br />
<code>In: 2022-07-12 06:50:00		Out: 2022-07-12 06:58:05		Total Position Time: 08:05		Total Move Up: -0.25		Total to Date: -0.50</code> <br />
<code>In: 2022-07-12 08:40:00		Out: 2022-07-12 08:42:05		Total Position Time: 02:05		Total Move Up: -3.00		Total to Date: -3.50</code> <br />
<code>In: 2022-07-13 06:50:00		Out: 2022-07-13 06:54:05		Total Position Time: 04:05		Total Move Up: -5.50		Total to Date: -9.00</code> <br />
<code>In: 2022-07-13 07:50:00		Out: 2022-07-13 07:59:05		Total Position Time: 09:05		Total Move Up: 3.50		Total to Date: -5.50</code> <br />
<code>In: 2022-07-14 08:20:00		Out: 2022-07-14 08:35:05		Total Position Time: 15:05		Total Move Up: 1.00		Total to Date: -4.50</code> <br />


</details>