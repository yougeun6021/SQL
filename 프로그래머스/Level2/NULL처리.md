## 문제링크
https://school.programmers.co.kr/learn/courses/30/lessons/59410

## 정답

```sql
SELECT  ANIMAL_TYPE,IFNULL(NAME,"No name") as NAME,SEX_UPON_INTAKE  from ANIMAL_INS order by ANIMAL_ID;
```

## IFNULL 정리(1번 NULL 처리)
https://tlrkswpcoding.tistory.com/102