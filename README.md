# markdown-test
마크다운 설명

### 11. 표
|번호|아이디|이름|레벨|이메일|등록일|
|:-----|:-----|:------|-----:|:----------------|:---------------:|
|1     |james1 |이상무1 |1     |jamesol@param.com|2023-01-27|
|2     |james2 |이상무2 |1     |jamesol@param.com|2023-01-27|
|3     |james3 |이상무3 |1     |jamesol@param.com|2023-01-27|
|4     |james4 |이상무4 |1     |jamesol@param.com|2023-01-27|
|5     |james5 |이상무5 |1     |jamesol@param.com|2023-01-27|

### 10. 인라인
문단 중간에 `CODE`를 넣을 수 있습니다.

### 9. 강조
Spring을 만끽하세요.  
**Spring**을 만끽하세요.  
*Spring*을 만끽하세요.

### 8. 이미지 넣기
![테스트지이미지](https://github.com/hamin081234/markdown-test/blob/main/5GDFSGAPEBAT5PC6E27XXZPXF4.jpg "롯데월드 사진")

### 7. 하이퍼링크
[e클래스](https://cafe.daum.net/pcwk "e클래스의 cafe입니다.")

### 6. 가로라인
---
___
-------

### 5. 코드블록
```
def detail(request, question_id):
    """Question 상세"""
    print(question_id)
    # question = Question.objects.get(id=question_id)
    question = get_object_or_404(Question, pk=question_id)

    context = {'question': question}
    return render(request, "pybo/question_detail.html", context)
```

### 4. 목록
1. 아이템1
2. 아이템2 
    1. 1단계 하위 아이템
        1. 2.1단계 하위 아이템

- 아이템 1
- 아이템 2
  - 1단계 하위 아이템
    - 2단계 하위 아이템

순서없는 목록
* 목록이름
- 목록1
+ 목록2

순서있는 목록
1. 목록 이름
2. 목록1
3. 목록2
4. 목록3

### 3. 인용문
> 인용할 내용을 넣으면 됩니다.
> 빈 줄이 없으면 자동으로 인용 상자에 포함이 됩니다

### 2. 헤더
# 헤더1
## 헤더2
### 헤더3
#### 헤더4
##### 헤더

### 1. 문단 구분을 위한 개행
문단을 작성 합니다.  
겨울이 가고 봄이 옵니다.\
(개행은 공백 두개 또는 \)

