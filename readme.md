# Hello World!
 `# : 가장 큰 헤드라인      (제목) 문자를 표시`

# 마크다운 문법
## 1. 제목 (헤드라인, Headline)
* 1~6까지만 지원
```markdown
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

h2
-
h1
=

## 2. 수평선
* `*`나 `-`, `_` 등을 3개이상 입력하면 작성 가능

```
***
----
____
```
문단1
----
*****
문단2
_____

## 3. 줄바꿈
문장1
문장2

문장1(중간에 엔터)

문장2

문장1(엔터 후 띄어쓰기2칸)  
문장2

문장1(br태그)<br>
문장2

## 꾸미기
```markdown
**굵게**
** 굵게 ** <- 작동x
*기울게*
~~취소선~~
***굵고기울게***
<u>밑줄</u>
```
**굵게**
** 굵게 ** <- 작동x
*기울게*
~~취소선~~
***굵고기울게***
<u>밑줄</u>

## 인용문
* 박스를 통해서 특정 문구를 강조
* `>`를 사용해서 인용을 표시, 중첩가능
```markdown
> 첫번째 인용문
>> 두번째 인용문
>>> 세번째 인용문
>>>> 네번째 인용문
```
> 첫번째 인용문
>> 두번째 인용문
>>> 세번째 인용문
>>>> 네번째 인용문

## 테이블
```
|제목1|제목2|제목3|
|----|----|----|
|행1-1|행1-2|행1-3|
```
|제목1|제목2|제목3|
|-|-|-|
|행1-1|행1-2|행1-3|
|행2-1|행2-2|행2-3|

|제목1|제목2|제목3|
|:-|:-:|-:|
|좌측 정렬|가운데 정렬|우측 정렬|
|행2-1|행2-2|행2-3|