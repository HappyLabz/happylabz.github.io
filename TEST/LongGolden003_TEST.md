# Long Golden 003 
- Symbol: TEST
- Date Range: 3/19/22 - 5/22/22
- Trading Period: 7:20-12:30
- Number of Trades: 9

![Plot](LongGolden003TEST.png)

| Name | Win Percent | Profit | Avg Profit / Trade |     | Name | Win Percent | Profit | Avg Profit / Trade |
| ---- | ----------- | ------ | ------------------ | --- | ---- | ----------- | ------ | ------------------ |
| Sorted By <br> Profit | | | | | Sorted By <br> Win Percentage ||||
| Seventy-Two | 88.89 | 219375.00 | 24375.00 |     | Seventy-Two | 88.89 | 219375.00 | 24375.00 |
| Seventy-Four | 55.56 | 13125.00 | 1458.33 |     | Seventy-Four | 55.56 | 13125.00 | 1458.33 |
| Seventy-Five | 44.44 | 6625.00 | 736.11 |     | Seventy-Five | 44.44 | 6625.00 | 736.11 |
| Seventy-Three | 44.44 | -10250.00 | -1138.89 |     | Seventy-Three | 44.44 | -10250.00 | -1138.89 |

### Test Seventy-Two
* Sell when the linear regression slope is negative
* No Stoploss
* Results:
```
Total Trades: 9
Percent Up: 88.89
Percent Down: 11.11
Total Points Moved Up: 438.75
Potential Profit: 219375.00
Total Points Ups: 460.25 Count Ups: 8
Total Points Downs: -21.50 Count Downs: 1
```

<details><summary>Trades</summary>

<code>In: 2022-07-08 07:30:00		Out: 2022-07-08 06:31:05		Total Position Time: 1381:05		Total Move Up: -21.50		Total to Date: -21.50</code> <br />
<code>In: 2022-07-11 08:20:00		Out: 2022-07-08 06:31:05		Total Position Time: 1331:05		Total Move Up: 22.25		Total to Date: 0.75</code> <br />
<code>In: 2022-07-11 08:30:00		Out: 2022-07-08 06:31:05		Total Position Time: 1321:05		Total Move Up: 19.75		Total to Date: 20.50</code> <br />
<code>In: 2022-07-12 06:50:00		Out: 2022-07-08 06:31:05		Total Position Time: 1421:05		Total Move Up: 24.75		Total to Date: 45.25</code> <br />
<code>In: 2022-07-12 08:30:00		Out: 2022-07-08 06:32:05		Total Position Time: 1322:05		Total Move Up: 21.50		Total to Date: 66.75</code> <br />
<code>In: 2022-07-13 06:50:00		Out: 2022-07-08 06:31:05		Total Position Time: 1421:05		Total Move Up: 90.25		Total to Date: 157.00</code> <br />
<code>In: 2022-07-13 07:45:00		Out: 2022-07-08 06:39:05		Total Position Time: 1374:05		Total Move Up: 86.25		Total to Date: 243.25</code> <br />
<code>In: 2022-07-14 08:10:00		Out: 2022-07-08 06:42:05		Total Position Time: 1352:05		Total Move Up: 150.75		Total to Date: 394.00</code> <br />
<code>In: 2022-07-15 07:10:00		Out: 2022-07-08 06:36:05		Total Position Time: 1406:05		Total Move Up: 44.75		Total to Date: 438.75</code> <br />


</details>

### Test Seventy-Three
* Sell when the linear regression slope changes to negative
* No Stoploss
* Results:
```
Total Trades: 9
Percent Up: 44.44
Percent Down: 55.56
Total Points Moved Up: -20.50
Potential Profit: -10250.00
Total Points Ups: 13.25 Count Ups: 4
Total Points Downs: -33.75 Count Downs: 5
```

<details><summary>Trades</summary>

<code>In: 2022-07-08 07:30:00		Out: 2022-07-08 07:41:05		Total Position Time: 11:05		Total Move Up: 2.50		Total to Date: 2.50</code> <br />
<code>In: 2022-07-11 08:20:00		Out: 2022-07-11 08:22:05		Total Position Time: 02:05		Total Move Up: 1.00		Total to Date: 3.50</code> <br />
<code>In: 2022-07-11 08:30:00		Out: 2022-07-11 08:32:05		Total Position Time: 02:05		Total Move Up: -0.75		Total to Date: 2.75</code> <br />
<code>In: 2022-07-12 06:50:00		Out: 2022-07-12 07:13:05		Total Position Time: 23:05		Total Move Up: -11.50		Total to Date: -8.75</code> <br />
<code>In: 2022-07-12 08:30:00		Out: 2022-07-12 08:33:05		Total Position Time: 03:05		Total Move Up: -1.75		Total to Date: -10.50</code> <br />
<code>In: 2022-07-13 06:50:00		Out: 2022-07-13 07:11:05		Total Position Time: 21:05		Total Move Up: -18.25		Total to Date: -28.75</code> <br />
<code>In: 2022-07-13 07:45:00		Out: 2022-07-13 07:55:05		Total Position Time: 10:05		Total Move Up: -1.50		Total to Date: -30.25</code> <br />
<code>In: 2022-07-14 08:10:00		Out: 2022-07-14 08:23:05		Total Position Time: 13:05		Total Move Up: 7.00		Total to Date: -23.25</code> <br />
<code>In: 2022-07-15 07:10:00		Out: 2022-07-15 07:17:05		Total Position Time: 07:05		Total Move Up: 2.75		Total to Date: -20.50</code> <br />


</details>

### Test Seventy-Four
* Sell when the bias changes to negative
* No Stoploss
* Results:
```
Total Trades: 9
Percent Up: 55.56
Percent Down: 44.44
Total Points Moved Up: 26.25
Potential Profit: 13125.00
Total Points Ups: 54.25 Count Ups: 5
Total Points Downs: -28.00 Count Downs: 4
```

<details><summary>Trades</summary>

<code>In: 2022-07-08 07:30:00		Out: 2022-07-08 08:31:00		Total Position Time: 61:00		Total Move Up: 11.25		Total to Date: 11.25</code> <br />
<code>In: 2022-07-11 08:20:00		Out: 2022-07-11 08:28:05		Total Position Time: 08:05		Total Move Up: 0.50		Total to Date: 11.75</code> <br />
<code>In: 2022-07-11 08:30:00		Out: 2022-07-11 08:36:05		Total Position Time: 06:05		Total Move Up: -0.75		Total to Date: 11.00</code> <br />
<code>In: 2022-07-12 06:50:00		Out: 2022-07-12 06:53:05		Total Position Time: 03:05		Total Move Up: 3.25		Total to Date: 14.25</code> <br />
<code>In: 2022-07-12 08:30:00		Out: 2022-07-12 09:11:05		Total Position Time: 41:05		Total Move Up: -10.50		Total to Date: 3.75</code> <br />
<code>In: 2022-07-13 06:50:00		Out: 2022-07-13 06:58:05		Total Position Time: 08:05		Total Move Up: -9.00		Total to Date: -5.25</code> <br />
<code>In: 2022-07-13 07:45:00		Out: 2022-07-13 08:43:00		Total Position Time: 58:00		Total Move Up: -7.75		Total to Date: -13.00</code> <br />
<code>In: 2022-07-14 08:10:00		Out: 2022-07-14 09:03:00		Total Position Time: 53:00		Total Move Up: 19.75		Total to Date: 6.75</code> <br />
<code>In: 2022-07-15 07:10:00		Out: 2022-07-15 08:15:00		Total Position Time: 65:00		Total Move Up: 19.50		Total to Date: 26.25</code> <br />


</details>

### Test Seventy-Five
* Sell when the STDEV slope changes to negative
* No Stoploss
* Results:
```
Total Trades: 9
Percent Up: 44.44
Percent Down: 55.56
Total Points Moved Up: 13.25
Potential Profit: 6625.00
Total Points Ups: 26.25 Count Ups: 4
Total Points Downs: -13.00 Count Downs: 5
```

<details><summary>Trades</summary>

<code>In: 2022-07-08 07:30:00		Out: 2022-07-08 07:47:05		Total Position Time: 17:05		Total Move Up: 4.50		Total to Date: 4.50</code> <br />
<code>In: 2022-07-11 08:20:00		Out: 2022-07-11 08:22:05		Total Position Time: 02:05		Total Move Up: 1.00		Total to Date: 5.50</code> <br />
<code>In: 2022-07-11 08:30:00		Out: 2022-07-11 08:35:05		Total Position Time: 05:05		Total Move Up: -3.25		Total to Date: 2.25</code> <br />
<code>In: 2022-07-12 06:50:00		Out: 2022-07-12 06:58:05		Total Position Time: 08:05		Total Move Up: -0.25		Total to Date: 2.00</code> <br />
<code>In: 2022-07-12 08:30:00		Out: 2022-07-12 08:34:05		Total Position Time: 04:05		Total Move Up: -2.50		Total to Date: -0.50</code> <br />
<code>In: 2022-07-13 06:50:00		Out: 2022-07-13 06:54:05		Total Position Time: 04:05		Total Move Up: -5.50		Total to Date: -6.00</code> <br />
<code>In: 2022-07-13 07:45:00		Out: 2022-07-13 07:55:05		Total Position Time: 10:05		Total Move Up: -1.50		Total to Date: -7.50</code> <br />
<code>In: 2022-07-14 08:10:00		Out: 2022-07-14 08:27:05		Total Position Time: 17:05		Total Move Up: 4.25		Total to Date: -3.25</code> <br />
<code>In: 2022-07-15 07:10:00		Out: 2022-07-15 07:33:05		Total Position Time: 23:05		Total Move Up: 16.50		Total to Date: 13.25</code> <br />


</details>