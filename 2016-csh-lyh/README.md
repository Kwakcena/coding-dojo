## 1. 이해

* 숫자의 범위 a: 1~12, b: 1~31
* ["SUN","MON","TUE","WED","THU","FRI","SAT"]
* 2016년 각 월별 일수 [31,29,31,30,31,30,31,31,30,31,30,31]

## 2. 계획

1. a를 받으면 1월 1일을 기준으로 a 전 월까지 일수를 모두 더하여
a월 1일 기준으로 일수를 만든다.
2. 1에서 구한 일수를 7로 나눈 나머지를 구한다.
3. 밑에 나머지 별 요일표를 기준으로 return
나머지
0 THU
1 FRI
2 SAT
3 SUN
4 MON
5 TUE
6 WED

## 3. 실행

## 4. 반성
