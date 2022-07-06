# Short Bulldog 001 (Bias Switch)
- Symbol: TEST
- Date Range: 3/19/22 - 5/22/22
- Trading Period: 7:20-12:30
- Number of Trades: 5
![Plot](ShortBulldog001TEST(BiasSwitch).png)

| Name | Win Percent | Profit | Avg Profit / Trade |     | Name | Win Percent | Profit | Avg Profit / Trade |
| ---- | ----------- | ------ | ------------------ | --- | ---- | ----------- | ------ | ------------------ |
| Sorted By <br> Profit | | | | | Sorted By <br> Win Percentage ||||
| Thirty-Five | 20.00 | 2500.00 | 500.00 |     | Thirty-Five | 20.00 | 2500.00 | 500.00 |
| Thirty-Six | 20.00 | -11625.00 | -2325.00 |     | Thirty-Six | 20.00 | -11625.00 | -2325.00 |
| Thirty-Seven | 20.00 | -14375.00 | -2875.00 |     | Thirty-Seven | 20.00 | -14375.00 | -2875.00 |

### Test Thirty-Five
* Sell when the linear regression slope changes to positive
* No Stoploss
* Results:
```
Total Trades: 5
Percent Up: 80.00
Percent Down: 20.00
Total Points Moved Down: 5.00
Potential Profit: 2500.00
Total Points Ups: 8.00 Count Ups: 4
Total Points Downs: 13.00 Count Downs: 1
```

<details><summary>Trades</summary>

<code>In: 2022-07-01 11:52:00		Out: 2022-07-01 11:58:05		Total Position Time: 06:05		Total Move Down: -0.25		Total to Date: 0.25</code> <br />
<code>In: 2022-07-05 07:41:00		Out: 2022-07-05 07:54:05		Total Position Time: 13:05		Total Move Down: 13.00		Total to Date: -12.75</code> <br />
<code>In: 2022-07-05 08:49:00		Out: 2022-07-05 08:55:05		Total Position Time: 06:05		Total Move Down: -3.25		Total to Date: -9.50</code> <br />
<code>In: 2022-07-05 11:06:00		Out: 2022-07-05 11:12:05		Total Position Time: 06:05		Total Move Down: -1.25		Total to Date: -8.25</code> <br />
<code>In: 2022-07-05 11:07:00		Out: 2022-07-05 11:12:05		Total Position Time: 05:05		Total Move Down: -3.25		Total to Date: -5.00</code> <br />


</details>

### Test Thirty-Six
* Sell when the bias changes to positive
* No Stoploss
* Results:
```
Total Trades: 5
Percent Up: 80.00
Percent Down: 20.00
Total Points Moved Down: -23.25
Potential Profit: -11625.00
Total Points Ups: 40.75 Count Ups: 4
Total Points Downs: 17.50 Count Downs: 1
```

<details><summary>Trades</summary>

<code>In: 2022-07-01 11:52:00		Out: 2022-07-01 12:21:55		Total Position Time: 29:55		Total Move Down: -0.00		Total to Date: -0.00</code> <br />
<code>In: 2022-07-05 07:41:00		Out: 2022-07-05 08:10:55		Total Position Time: 29:55		Total Move Down: 17.50		Total to Date: -17.50</code> <br />
<code>In: 2022-07-05 08:49:00		Out: 2022-07-05 08:59:05		Total Position Time: 10:05		Total Move Down: -1.50		Total to Date: -16.00</code> <br />
<code>In: 2022-07-05 11:06:00		Out: 2022-07-05 11:35:55		Total Position Time: 29:55		Total Move Down: -16.75		Total to Date: 0.75</code> <br />
<code>In: 2022-07-05 11:07:00		Out: 2022-07-05 11:36:55		Total Position Time: 29:55		Total Move Down: -22.50		Total to Date: 23.25</code> <br />


</details>

### Test Thirty-Seven
* Sell when the STDEV slope changes to positive
* No Stoploss
* Results:
```
Total Trades: 5
Percent Up: 80.00
Percent Down: 20.00
Total Points Moved Down: -28.75
Potential Profit: -14375.00
Total Points Ups: 42.75 Count Ups: 4
Total Points Downs: 14.00 Count Downs: 1
```

<details><summary>Trades</summary>

<code>In: 2022-07-01 11:52:00		Out: 2022-07-01 12:21:55		Total Position Time: 29:55		Total Move Down: -0.00		Total to Date: -0.00</code> <br />
<code>In: 2022-07-05 07:41:00		Out: 2022-07-05 07:47:05		Total Position Time: 06:05		Total Move Down: 14.00		Total to Date: -14.00</code> <br />
<code>In: 2022-07-05 08:49:00		Out: 2022-07-05 09:18:55		Total Position Time: 29:55		Total Move Down: -3.50		Total to Date: -10.50</code> <br />
<code>In: 2022-07-05 11:06:00		Out: 2022-07-05 11:35:55		Total Position Time: 29:55		Total Move Down: -16.75		Total to Date: 6.25</code> <br />
<code>In: 2022-07-05 11:07:00		Out: 2022-07-05 11:36:55		Total Position Time: 29:55		Total Move Down: -22.50		Total to Date: 28.75</code> <br />


</details>