참고: https://guides.github.com/features/mastering-markdown/


# 헤드
<h1> html태그도 같이 적용할 수 있다.</h1>

## 헤드2
<h2> markdown으로 안되면 html태그로 적용할 수 있다.</h2>

### 헤드3
코드 입력하기:  
```
def test():
    print("test")
```

#syntax coloring 적용하기: python 스타일로 적용
```python
def test():
    print("test")
```
```JavaScript
def test():
    print("test")
```
```C++
def test():
    print("test")
```

``` sh
$ rm -rf /dir
```


#코드를 문장 사이에 표시하기:

텐서플로우 `import tensorflow as tf;` 사용합니다.


#강조하기

이탤릭: *이탤릭* or _이탤릭_

볼드: **볼드** or __볼드__

이탤릭+볼드: **_이탤릭+볼드_**


#리스트만들기

- 하나
- 둘
- 셋
  - 셋하나
  - 셋둘
    - 셋둘하나
    - 셋둘둘


#링크만들기
```
[link name](link address)
```
1. [link name](link address)
2. <a href="./link address"> 링크만들기 </a>

#이미지 링크만들기

```
![이미지 설명](이미지 경로)
```
1. ![이미지 설명](이미지 경로)
2. <img src="이미지 경로" width = '숫자'>
3. <a href="이미지 클릭했을때 갈 링크주소"><img src="이미지 경로" width = '숫자'> </a>
   
#테이블 만들기

헤더 1 | 헤더 2| 헤더 3 
------- | ------- | ------- 
내용을 입력한다 | 파이프 전에 띄어쓰기 조심하고 | 임의로 표를 만들 수 있다.