---
layout: single
title: "SQL-Final-Week"
---

# Subquery , With , Case 

- subquery는 Select절 , From절, Where절 로 나뉘어진다.

ex) select ( select * from * where * ) 과 같은 형태로 사용

    select * from ( select * from * where * ) 과 같은 형태로 사용

    select * from * where ( select * from * where * ) 과 같은 형태로 사용

- With은 table을 만들어 사용
  
  with 임시테이블명 as ( ) 처럼 사용하고 

  select * from 임시테이블명 과 같이 사용한다

- Case절은 조건에 따라 값을 정해주는데 사용

case 컬럼 
    when 조건1 then 값1
    when 조건2 then 값2
    else 값3
    end

    와 같이 사용한다


- Join 과 Subquery를 활용하는 일이 많을 것 같다.