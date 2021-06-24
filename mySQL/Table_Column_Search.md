# 특정 테이블 및 칼럼명 검색
## 테이블명 검색하기
```
SELECT * FROM information_schema.TABLE_CONSTRAINTS WHERE TABLE_NAME LIKE '%테이블명%'
```
## 컬럼명 검색하기
```
SELECT * FROM information_schema.COLUMNS WHERE COLUMN_NAME LIKE '%컬럼명%'
```


## 단축키 지정하기
### 도구 > 옵션 > 키보드 > 쿼리 바로가기에 단축키로 명령문 입력해두고 '%검색명%'을 블록지정 후에 [Ctrl + 7] or [Ctrl + 8] 입력해서 검색 가능


## 참고 사이트
https://developro.tistory.com/64