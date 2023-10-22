# Task: Профил на дърво (Medium) - [HackerRank](<https://www.hackerrank.com/contests/sda-2019-2020-exam-2e3nr4rr/challenges/challenge-2352>)


### Statement:

Напишете функция, която намира как изглежда едно двоично дърво за търсене погледнато отляво. При гледане на дървото отляво виждаме за всяко ниво на дървото най-левият възел. т.е се вижда корена, най-лявата част от най-левият клон и след това на всяко следващо ниво най-левият възел на дървото (това може да са възли от различни клонове на дървото). На примера отдолу са отблязани с зелена точка възлите които се виждат като ляв профил на дървото.

<img src="https://s3.amazonaws.com/hr-assets/0/1579812434-26957311ea-Screenshotfrom2020-01-2322-42-45.png" alt="image" title="">


### Input format

Реализирайте функцията, която е в темплейта.


### Constraints

възлите на дървото ще са по-малко от 100,000

### Output format

принтирайте числата във възлите започвайки последователно от корена и стигайки до най-дълбокия възел виждан от ляво.


### Samples


#### Sample Input 0
```
5
2 0 5 8 3 
```

#### Sample Output 0
```
2 0 3 
```