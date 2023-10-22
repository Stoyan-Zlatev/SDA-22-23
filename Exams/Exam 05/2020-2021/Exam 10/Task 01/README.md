# Task: Доставки (Medium) - [HackerRank](<https://www.hackerrank.com/contests/sda-2020-2021-test10-f43j2hj/challenges/challenge-2794>)


### Statement:

Фирма за доставки иска да оптимизира доставките си от офис до офис. За целта и трябва да и се направи приложение, с което да може да изчислява от дадено офис какви са оптималните пътища до другите офиси.


### Input format

N, M  - съответно броят на офисите и броят на пътищата между тях.

На следващите m реда са описани пътища с по три цели положителни числа:  u, v, w - описва автомобилен двупосочен път от офис u до офис v, което има разстояние w. (0 &lt;= u, v &lt; N)

На последния ред е дадено s - номерът на офиса от който търсим минималните пътища.


### Constraints

1 &lt;= N &lt;=2 * 10^5 ;1 &lt;= M &lt;= 5 * 10^6
тегла на ребрата &lt; 10^5

### Output format

отпечатайте N-1 числа разделени с интервал, тези числа показват последователно какво е разстоянието от стартовия възел до всеки един от останалите върхове сортирани по номера на върха. 

Ако връх е недостижим изведете -1


### Samples


#### Sample Input 0
```
4 4
1 2 24
1 4 20
3 1 3
4 3 12
1
```

#### Sample Output 0
```
24 3 15
```