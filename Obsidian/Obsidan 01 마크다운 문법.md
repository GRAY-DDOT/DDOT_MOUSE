
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```MD
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```
# 문단 구분
문단 1
문단 1

문단 2 //빈 줄 넣어 문단 구분

## **뷰 모드시 여러 줄/여러 개 공백은 출력 안됨
- `&nbsp;` (공백)
- `<br>` (빈줄)
### 예시
문단1        그냥 공백
문단1


문단2 그냥 줄바꿈

문단1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `&nbsp;`공백
문단1<br>
<br>
문단2  `<br>`줄 바꿈





# 텍스트 스타일
|Style|Syntax|Example|Output|
|-----|-------|-----|--------|
|Bold(굵게)|`** **` or `__ __`|`**Bold text**`|**Bold text**|
|Italic<br>(이테릭, 기울임)|`* *` or `_ _`|`*Italic text*`|_Italic text_|
|Strikethrough<br>(취소선)|`~~ ~~`|`~~Striked out text~~`|~~Striked out text~~|
|Highlight(강조)|==예시 불가==|==코드 오류 생김== | ==Highlighted text== |
|Bold and nested italic<br>(굵게, 일부 기울임)|`** **` and `_ _`|`**Bold text and _nested italic_ text**`|**Bold text and _nested italic_ text**|
|Bold and italic<br>(전부 굵고 기울임)|`*** ***` or `___ ___`|`***Bold and italic text***`|**_Bold and italic text_**|

# 인용(Quote), 들여쓰기

> 인용하는 말.

\- 출처

비슷한 기능 [[콜아웃]]

# 코드 표시

`인라인 코드`

``` 언어/형식 이름


코드내용
```


# 외부 링크
[이름](url)
