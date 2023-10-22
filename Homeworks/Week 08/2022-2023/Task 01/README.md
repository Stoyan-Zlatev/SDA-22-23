# Task: Магазин за Баници (Medium) - [HackerRank](<https://www.hackerrank.com/contests/sda-hw-8-2022/challenges/fullstack-developer>)


### Statement:

В един щастлив ден се оказвате собственик на магазин за баници. Един ден получавате N на брой поръчки за баници, всяка от които започва във време t[i] и за изпълнението и ще отнеме време f[i], където i е номера на поръчката. Магазинът ви обаче има политика да обслужва най-бързата за приготвяне и ще я довърши изцяло преди да се заеме с нова поръчка. В същия момент като приключите поръчката, взимате нова и започвате да я изпълнявате

Забележка: Ако в един момент има повече от 1 поръчка, която е най-бърза за приключване, Сашко иска да започне с тази, която е била подадена първа (тази която е била най-рано във входа).


### Input format

На първия ред на стандартния вход ще получите броя на поръчките N

На следвашите N реда ще получите по две числа t[i] и f[i], съответно времето от което нататък включително ще може да се започне поръчката и колко време ще отнеме за изпълнение i-тата поръчка (i e номера на реда, като номерацията започава от 0) 


### Constraints

1 &lt;= N &lt;= 10^5
1 &lt;= t,f &lt;= 10^9

### Output format

На стандартния изход изкарайте реда, в който поръчките ще се свършат от магазина.

Индексите в реда на изпълнение разделени с интервал.


### Samples


#### Sample Input 0
```
4
3 3
2 4
1 2
7 1
```

#### Sample Output 0
```
2 0 1 3
```

#### Explanation 0
В момент едно единствеанта поръчка, която може да се започне е третата задача(тази с индекс 2), така че можете да започнете нея. Тя ще отнеме време 2 и ще бъде готова във време 3. Във време 3 има две поръчки, които ще могат да се започнат(тези с индекс 0 и 1). Може да започнете задачата с индекс 0 понеже тя ще отнеме по-малко време за свършване(3&lt;4). Във време 6 той ще сте готови със поръчката и само една поръчка ще бъде възможно да се започне тогава(тази с индекс 1). Тя ще бъде готова във време 10 и в този момент ще бъде започната последната останала поръчка. Реда на изпълнение на задачаите е:
2 0 1 3