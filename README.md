# markdown20240125
markdown

### 1. 문단 구분을 위한 개행
겨울 바다를 걸어 보자  
(개행 : space 2)  
겨울을 만끽 해

### 2. 해더
''' #을 1~6개 사용 '''
# java
## oracle
### HTML
#### CSS
##### javascript
###### spring

### 3. 인용 상자
#4-코드블럭
>여기에 인용할 내용을 넣기  
>>빈 줄이 없으면 자동으로 인용 상자에 포함 됨
식사 맛있게 했나요?

인용이 끝

### 4. 코드 블럭
```java
public class Hello{
  public static void main(String[] args){
    System.out.println("Hello, world");
  }
}
```

### 5. 목록
---
- 아이템1
+ 아이템2
  - 1단계 하위 아이템
    * 2단계 하위 아이템
* 아이템3
---
1. 아이템1
2. 아이템2  
   9. 1단계 하위 아이템  
       10. 2단계 하위 아이템
9. 아이템3
---
#### 무순서 목록
* 목록이름1
- 목록이름2
+ 목록이름3

#### 순서있는 목록
1. 목록1
1. 목록2
1. 목록3

### 6. 가로선
화면 전체를 가로지르는 가로선 : -, * 을 3개 이상
---
***
----
### 7. 하이퍼 링크
```
[링크텍스트](링크URL) 
```
[daum cafe](https://cafe.daum.net/pcwk "수업자료 cafe")

### 8. 이미지 넣기
```
![링크텍스트](링크URL)
```
![window 이미지](https://github.com/Olaf247/markdown20240125/blob/main/doc/win.png)

