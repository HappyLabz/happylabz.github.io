# Short Wallace 001 (No VWAP)
- Symbol: ES
- Date Range: 3/19/22 - 5/22/22
- Trading Period: 7:20-12:30

| Name | Win Percent | Profit |     | Name | Win Percent | Profit |
| ---- | ----------- | ------ | --- | ---- | ----------- | ------ |
| Sorted By <br> Profit | | | | Sorted By <br> Win Percentage |||
| Twenty-One | 100.00 | 10250.00 |     | Twenty-One | 100.00 | 10250.00 |
| Twenty | 100.00 | 10250.00 |     | Twenty | 100.00 | 10250.00 |
| Fourteen | 100.00 | 10250.00 |     | Fourteen | 100.00 | 10250.00 |
| Three | 100.00 | 10250.00 |     | Three | 100.00 | 10250.00 |
| Fifteen | 66.67 | 6750.00 |     | Nineteen | 100.00 | 5000.00 |
| Nineteen | 100.00 | 5000.00 |     | Eighteen | 100.00 | 5000.00 |
| Eighteen | 100.00 | 5000.00 |     | Twelve | 100.00 | 5000.00 |
| Twelve | 100.00 | 5000.00 |     | Two | 100.00 | 5000.00 |
| Two | 100.00 | 5000.00 |     | Fifteen | 66.67 | 6750.00 |
| Thirteen | 66.67 | 3000.00 |     | Thirteen | 66.67 | 3000.00 |
| Eight | 33.33 | 3000.00 |     | Seventeen | 66.67 | 1125.00 |
| Seventeen | 66.67 | 1125.00 |     | Sixteen | 66.67 | 1125.00 |
| Sixteen | 66.67 | 1125.00 |     | Ten | 66.67 | 1125.00 |
| Ten | 66.67 | 1125.00 |     | One | 66.67 | 1125.00 |
| One | 66.67 | 1125.00 |     | Eleven | 66.67 | -0.00 |
| Six | 33.33 | 875.00 |     | Eight | 33.33 | 3000.00 |
| Eleven | 66.67 | -0.00 |     | Six | 33.33 | 875.00 |
| Four | 33.33 | -875.00 |     | Four | 33.33 | -875.00 |
| Nine | 0.00 | -1750.00 |     | Nine | 0.00 | -1750.00 |
| Seven | 0.00 | -1750.00 |     | Seven | 0.00 | -1750.00 |
| Five | 0.00 | -1750.00 |     | Five | 0.00 | -1750.00 |


### Test One
* Sell when price hits the middle line of the 20p bollinger
* No Stoploss
* Results:
```
Total Trades: 3
Percent Up: 33.33
Percent Down: 66.67
Total Points Moved Down: 2.25
Potential Profit: 1125.00
Total Points Ups: 0.00 Count Ups: 1
Total Points Downs: 2.25 Count Downs: 2
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:30		Total Move Down: 1.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:25:20		Total Move Down: -0.00</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:29:45		Total Move Down: 1.25</code> <br />


</details>

### Test Two
* Sell when the price hits the lower line of the 20p 1std bollinger
* No Stoploss
* Results:
```
Total Trades: 3
Percent Up: 0.00
Percent Down: 100.00
Total Points Moved Down: 10.00
Potential Profit: 5000.00
Total Points Ups: 0.00 Count Ups: 0
Total Points Downs: 10.00 Count Downs: 3
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:06:10		Total Move Down: 3.50</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:26:00		Total Move Down: 1.75</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:30:45		Total Move Down: 4.75</code> <br />


</details>

### Test Three
* Sell when the price hits the lower line of the 20p 2std bollinger
* No Stoploss
* Results:
```
Total Trades: 3
Percent Up: 0.00
Percent Down: 100.00
Total Points Moved Down: 20.50
Potential Profit: 10250.00
Total Points Ups: 0.00 Count Ups: 0
Total Points Downs: 20.50 Count Downs: 3
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:07:40		Total Move Down: 6.75</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:33:25		Total Move Down: 4.75</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:34:00		Total Move Down: 9.00</code> <br />


</details>

### Test Four
* Sell when the price hits the middle line of the 20p bollinger
* Stoploss is -2 points
* Results:
```
Total Trades: 3
Percent Up: 66.67
Percent Down: 33.33
Total Points Moved Down: -1.75
Potential Profit: -875.00
Total Points Ups: 3.00 Count Ups: 2
Total Points Downs: 1.25 Count Downs: 1
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:10		Total Move Down: -0.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:24:05		Total Move Down: -3.00</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:29:45		Total Move Down: 1.25</code> <br />


</details>

### Test Five
* Sell when the price hits the middle line of the 20p bollinger
* Trailing Stop is -2 points
* Results:
```
Total Trades: 3
Percent Up: 100.00
Percent Down: 0.00
Total Points Moved Down: -3.50
Potential Profit: -1750.00
Total Points Ups: 3.50 Count Ups: 3
Total Points Downs: 0.00 Count Downs: 0
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:10		Total Move Down: -0.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:18:55		Total Move Down: -1.25</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:28:10		Total Move Down: -2.25</code> <br />


</details>

### Test Six
* Sell when the price hits the lower line of the 20p 1std bollinger
* Stoploss is -2 points
* Results:
```
Total Trades: 3
Percent Up: 66.67
Percent Down: 33.33
Total Points Moved Down: 1.75
Potential Profit: 875.00
Total Points Ups: 3.00 Count Ups: 2
Total Points Downs: 4.75 Count Downs: 1
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:10		Total Move Down: -0.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:24:05		Total Move Down: -3.00</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:30:45		Total Move Down: 4.75</code> <br />


</details>

### Test Seven
* Sell when the price hits the lower line of the 20p 1std bollinger
* Trailing Stop is -2 points
* Results:
```
Total Trades: 3
Percent Up: 100.00
Percent Down: 0.00
Total Points Moved Down: -3.50
Potential Profit: -1750.00
Total Points Ups: 3.50 Count Ups: 3
Total Points Downs: 0.00 Count Downs: 0
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:10		Total Move Down: -0.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:18:55		Total Move Down: -1.25</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:28:10		Total Move Down: -2.25</code> <br />


</details>

### Test Eight
* Sell when the price hits the lower line of the 20p 2std bollinger
* Stoploss is -2 points
* Results:
```
Total Trades: 3
Percent Up: 66.67
Percent Down: 33.33
Total Points Moved Down: 6.00
Potential Profit: 3000.00
Total Points Ups: 3.00 Count Ups: 2
Total Points Downs: 9.00 Count Downs: 1
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:10		Total Move Down: -0.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:24:05		Total Move Down: -3.00</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:34:00		Total Move Down: 9.00</code> <br />


</details>

### Test Nine
* Sell when the price hits the lower line of the 20p 2std bollinger
* Trailing Stop is -2 points
* Results:
```
Total Trades: 3
Percent Up: 100.00
Percent Down: 0.00
Total Points Moved Down: -3.50
Potential Profit: -1750.00
Total Points Ups: 3.50 Count Ups: 3
Total Points Downs: 0.00 Count Downs: 0
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:10		Total Move Down: -0.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:18:55		Total Move Down: -1.25</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:28:10		Total Move Down: -2.25</code> <br />


</details>

### Test Ten
* Sell when the price hits the middle line of the 20p bollinger
* Stoploss is -3 points
* Results:
```
Total Trades: 3
Percent Up: 33.33
Percent Down: 66.67
Total Points Moved Down: 2.25
Potential Profit: 1125.00
Total Points Ups: 0.00 Count Ups: 1
Total Points Downs: 2.25 Count Downs: 2
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:30		Total Move Down: 1.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:25:20		Total Move Down: -0.00</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:29:45		Total Move Down: 1.25</code> <br />


</details>

### Test Eleven
* Sell when the price hits the middle line of the 20p bollinger
* Trailing Stop is -3 points
* Results:
```
Total Trades: 3
Percent Up: 33.33
Percent Down: 66.67
Total Points Moved Down: -0.00
Potential Profit: -0.00
Total Points Ups: 2.25 Count Ups: 1
Total Points Downs: 2.25 Count Downs: 2
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:30		Total Move Down: 1.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:23:55		Total Move Down: -2.25</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:29:45		Total Move Down: 1.25</code> <br />


</details>

### Test Twelve
* Sell when the price hits the lower line of the 20p 1std bollinger
* Stoploss is -3 points
* Results:
```
Total Trades: 3
Percent Up: 0.00
Percent Down: 100.00
Total Points Moved Down: 10.00
Potential Profit: 5000.00
Total Points Ups: 0.00 Count Ups: 0
Total Points Downs: 10.00 Count Downs: 3
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:06:10		Total Move Down: 3.50</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:26:00		Total Move Down: 1.75</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:30:45		Total Move Down: 4.75</code> <br />


</details>

### Test Thirteen
* Sell when the price hits the lower line of the 20p 1std bollinger
* Trailing Stop is -3 points
* Results:
```
Total Trades: 3
Percent Up: 33.33
Percent Down: 66.67
Total Points Moved Down: 6.00
Potential Profit: 3000.00
Total Points Ups: 2.25 Count Ups: 1
Total Points Downs: 8.25 Count Downs: 2
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:06:10		Total Move Down: 3.50</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:23:55		Total Move Down: -2.25</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:30:45		Total Move Down: 4.75</code> <br />


</details>

### Test Fourteen
* Sell when the price hits the lower line of the 20p 2std bollinger
* Stoploss is -3 points
* Results:
```
Total Trades: 3
Percent Up: 0.00
Percent Down: 100.00
Total Points Moved Down: 20.50
Potential Profit: 10250.00
Total Points Ups: 0.00 Count Ups: 0
Total Points Downs: 20.50 Count Downs: 3
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:07:40		Total Move Down: 6.75</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:33:25		Total Move Down: 4.75</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:34:00		Total Move Down: 9.00</code> <br />


</details>

### Test Fifteen
* Sell when the price hits the lower line of the 20p 2std bollinger
* Trailing Stop is -3 points
* Results:
```
Total Trades: 3
Percent Up: 33.33
Percent Down: 66.67
Total Points Moved Down: 13.50
Potential Profit: 6750.00
Total Points Ups: 2.25 Count Ups: 1
Total Points Downs: 15.75 Count Downs: 2
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:07:40		Total Move Down: 6.75</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:23:55		Total Move Down: -2.25</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:34:00		Total Move Down: 9.00</code> <br />


</details>

### Test Sixteen
* Sell when the price hits the middle line of the 20p bollinger
* Stoploss is -5 points
* Results:
```
Total Trades: 3
Percent Up: 33.33
Percent Down: 66.67
Total Points Moved Down: 2.25
Potential Profit: 1125.00
Total Points Ups: 0.00 Count Ups: 1
Total Points Downs: 2.25 Count Downs: 2
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:30		Total Move Down: 1.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:25:20		Total Move Down: -0.00</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:29:45		Total Move Down: 1.25</code> <br />


</details>

### Test Seventeen
* Sell when the price hits the middle line of the 20p bollinger
* Trailing Stop is -5 points
* Results:
```
Total Trades: 3
Percent Up: 33.33
Percent Down: 66.67
Total Points Moved Down: 2.25
Potential Profit: 1125.00
Total Points Ups: 0.00 Count Ups: 1
Total Points Downs: 2.25 Count Downs: 2
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:05:30		Total Move Down: 1.00</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:25:20		Total Move Down: -0.00</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:29:45		Total Move Down: 1.25</code> <br />


</details>

### Test Eighteen
* Sell when the price hits the lower line of the 20p 1std bollinger
* Stoploss is -5 points
* Results:
```
Total Trades: 3
Percent Up: 0.00
Percent Down: 100.00
Total Points Moved Down: 10.00
Potential Profit: 5000.00
Total Points Ups: 0.00 Count Ups: 0
Total Points Downs: 10.00 Count Downs: 3
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:06:10		Total Move Down: 3.50</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:26:00		Total Move Down: 1.75</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:30:45		Total Move Down: 4.75</code> <br />


</details>

### Test Nineteen
* Sell when the price hits the lower line of the 20p 1std bollinger
* Trailing Stop is -5 points
* Results:
```
Total Trades: 3
Percent Up: 0.00
Percent Down: 100.00
Total Points Moved Down: 10.00
Potential Profit: 5000.00
Total Points Ups: 0.00 Count Ups: 0
Total Points Downs: 10.00 Count Downs: 3
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:06:10		Total Move Down: 3.50</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:26:00		Total Move Down: 1.75</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:30:45		Total Move Down: 4.75</code> <br />


</details>

### Test Twenty
* Sell when the price hits the lower line of the 20p 2std bollinger
* Stoploss is -5 points
* Results:
```
Total Trades: 3
Percent Up: 0.00
Percent Down: 100.00
Total Points Moved Down: 20.50
Potential Profit: 10250.00
Total Points Ups: 0.00 Count Ups: 0
Total Points Downs: 20.50 Count Downs: 3
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:07:40		Total Move Down: 6.75</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:33:25		Total Move Down: 4.75</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:34:00		Total Move Down: 9.00</code> <br />


</details>

### Test Twenty-One
* Sell when the price hits the lower line of the 20p 2std bollinger
* Trailing Stop is -5 points
* Results:
```
Total Trades: 3
Percent Up: 0.00
Percent Down: 100.00
Total Points Moved Down: 20.50
Potential Profit: 10250.00
Total Points Ups: 0.00 Count Ups: 0
Total Points Downs: 20.50 Count Downs: 3
```

<details><summary>Trades</summary>

<code>In: 2022-03-23 09:05:00		Out: 2022-03-23 09:07:40		Total Move Down: 6.75</code> <br />
<code>In: 2022-04-13 10:15:00		Out: 2022-04-13 10:33:25		Total Move Down: 4.75</code> <br />
<code>In: 2022-04-28 12:27:00		Out: 2022-04-28 12:34:00		Total Move Down: 9.00</code> <br />


</details>
