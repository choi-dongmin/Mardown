# Markup 

- 텍스트 기반의 파일을 지원하기 위한 문서에 추가되는 정보를 기입하는 언어

1. Presentational markup(프레젠테이션 마크업)
- 마크업 종류중 하나인 위즈윗(WYSIWYG)효과를 생성하는것
- 단락 구분을 위한 공백, 새로운 장이나 절의 시작을 표시하는 문장은 글씨 크기, 그림이나 도표를 적절하게 배치시키는 등

2. Procedural markup(절차적 마크업)
- 처음부터 끝까지 순차적으로 텍스트를 처리

3. Descriptive markup(설명 마크업)

## Markdown
- HTML, XML 과 같이 Markup 언어의 일종.

### 마크다운 작성 방법 

1. 제목
- 제목이되는 헤드라이트의 글자 크기 조정

```
# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6
```
![화면 캡처 2022-07-06 200752](https://user-images.githubusercontent.com/57117748/177536983-e5d377d3-95ec-42c5-bf91-21c2ee74f55a.png)

2. 경계줄
- 경계줄을 생성한다
```
---
```
![화면 캡처 2022-07-06 201558](https://user-images.githubusercontent.com/57117748/177538165-4fd9f2b5-05fe-43bb-a3f0-e115e475851a.png)


3. 강조
```
하늘에 *구름* 한 조각.

하늘에 **구름** 한 조각.

하늘에 ***구름*** 한 조각.

하늘에 _구름_ 한 조각.

하늘에 __구름__ 한 조각.

하늘에 ___구름___ 한 조각.

하늘에 *_구름_* 한 조각.

하늘에 *__구름__* 한 조각.

하늘에 _*구름*_ 한 조각.

하늘에 __*구름*__ 한 조각.
```

하늘에 *구름* 한 조각.

하늘에 **구름** 한 조각.

하늘에 ***구름*** 한 조각.

하늘에 _구름_ 한 조각.

하늘에 __구름__ 한 조각.

하늘에 ___구름___ 한 조각.

하늘에 *_구름_* 한 조각.

하늘에 *__구름__* 한 조각.

하늘에 _*구름*_ 한 조각.

하늘에 __*구름*__ 한 조각.

4. 인용문
```
> https://www.google.com

>> https://www.google.com
```

> https://www.google.com

>> https://www.google.com

5. 목록
```
- 목록1
- 목록2
- 목록3
  - 하위 목록1
  - 하위 목록2

* 목록1
* 목록2

* 목록1
  - 하위 목록1
    + 하하위 목록1 

1. 목록1
    1. 하위목록1
    2. 하위목록2
```
![화면 캡처 2022-07-06 202050](https://user-images.githubusercontent.com/57117748/177538889-dbf93e2b-b174-4ad5-adb4-656f58331ffa.png)

6. 코드블록
```java
a = 1
b = 1
print(a+b)
```

```python
a = 1
b = 1
print(a+b)
```

```yaml
- name: abc
  hosts: webserver

  tasks:
  - debug:
      msg: "hello world"
```

7. 링크
```
https://kubernetes.io

[Kube Official Site](https://kubernetes.io)

[쿠버네티스 공식 사이트](https://kubernetes.io)에서 내용을 참조하세요.
```

https://kubernetes.io

[Kube Official Site](https://kubernetes.io)

[쿠버네티스 공식 사이트](https://kubernetes.io)에서 내용을 참조하세요.

8. 이미지
```
![tmux image](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/202px-Tux.svg.png)
```
![tmux image](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/202px-Tux.svg.png)

9. 테이블
```
|번호|이름|갯수|
|-:|:-:|:-|
|1|사과|100|
|2|배|2000|
|3|딸기|3000|
```
|번호|이름|갯수|
|-:|:-:|:-|
|1|사과|100|
|2|배|2000|
|3|딸기|3000|

10. 취소선
```
현재 버전은 ~~1.0.1~~ 입니다.
```
현재 버전은 ~~1.0.1~~ 입니다.

11. 작업 목록
```
- [ ] todo 1
- [ ] todo 2
- [X] todo 3
```

- [ ] todo 1
- [ ] todo 2
- [X] todo 3
