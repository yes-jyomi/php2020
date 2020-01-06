# PHP 실습 :file_folder:
2020년 겨울방학 PHP 방과후


## 알아야 할 것
php에서 C:\Bitnami\wampstack-7.3.13-0\apache2\htdocs 가 루트


## PHP 문법
* ```<?php        ?>```
* ```echo``` 이용하여 출력
* ```;``` 으로 마무리
* 주석 : ```//```, ```/*     */```
* 변수 선언 시 타입선언 안 함.
* 변수 앞에 ```$``` 붙음.
* ```.``` 을 연결연산자로 사용함.
* 태그를 섞어 사용할 때는 ```echo``` 와 ```""```로 둘러싸야 함.


## php.ini
php 설정 파일
* display_errors = On
* log_errors = On


## 배열 선언 방법
* 구버전
  ```$arr = array('a', 'b', 'c', 'd', 'e');```
* 최근 버전
```$arr2 = ['a', 'b', 'c', 'd', 'e'];```


## 파일 읽기
1. fopen(file_name, "r")
2.  * fgetc() : 한 글자씩 (사용 시 <br> 태그 사용해서 출력)
    * fgets() : 한 줄씩
    * fread(filepointer, filesize)
    * file_get_contents
3. fclose()


## 파일 쓰기
1. fopen(file_name, "w")
2.  * fputs()
    * fread()
    * file_put_contents()
3. fclose()


## 파일 복사하기
```copy ( $file_name , $new_file_name )```
