## 문제 링크
https://school.programmers.co.kr/learn/courses/30/lessons/59414

## 정답
```sql
SELECT ANIMAL_ID,NAME,date_format(DATETIME,"%Y-%m-%d") as "날짜" from ANIMAL_INS
```

## date_format 정리(2번 DATETIME 형 변환)
https://tlrkswpcoding.tistory.com/102