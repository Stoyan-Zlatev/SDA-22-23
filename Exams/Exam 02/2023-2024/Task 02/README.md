# Task: Склад за ядки (Medium) - [HackerRank](<https://www.hackerrank.com/contests/2-2023-2024/challenges/kosi>)


### Statement:

В склад са разположени последователно $MISSING$ кашона с ядки. Първият кашон е на първа позиция, вторият на втора, а $MISSING$-тия на $MISSING$та. Кашонът на $MISSING$-та позиция тежи $MISSING$ килограма. Дадени са $MISSING$ на брой заявки за доставка на кашони. Една заявка изисква да се намерят позициите на точно два кашона, чиято сума от килограмите е равна на $MISSING$. Важно: Винаги има точно едно уникално решение.


### Input format

Първият ред съдържа едно цяло число $MISSING$ - броят на заявките

Всеки от следващите групи от по 3 реда е както следва:

Първият ред съдържа едно цяло число $MISSING$ - килограми

Вторият ред съдържа едно цяло число $MISSING$ - броят на кашоните в склада 

Третият ред съдържа $MISSING$ на брой цели числа $MISSING$ - теглото на всеки един от кашоните в склада


### Constraints



### Output format

Печатаме $MISSING$ на брой реда. Един ред съдържа 2 цели числа - позициите на кашоните, чийто сбор от килограмите е равен на $MISSING$. Важно: Първо печатаме по-малката позиция от двете


### Samples


#### Sample Input 0
```
1
6
4
3 4 5 3
```

#### Sample Output 0
```
1 4
```

#### Explanation 0
Дадена е една заявка, в която търсим сумата от килограмите на 2 кашона да е равна на 6. Дадени са ни 4ри кашона в склада. Печатаме 1ви и 4ти, защото на тези позиции стоят кашоните, чийто сума е равна на 6. 

#### Sample Input 1
```
2
7
5
5 4 1 2 8
10
6
6 2 1 5 2 9
```

#### Sample Output 1
```
1 4
3 6
```