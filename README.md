# studyPython
부경대 IoT 파이썬 학습 리포지토리


## 1일차
1. 기본구성
    - Git/Github 설치 및 연동
    - Visual Stduio code 설치 및 연동
    - Python 설치
2. 파이썬 기본
    - 콘솔출력

```python
# desc : 콘솔출력 - 주석
print('Hello, Python!!') # 콘솔출력 함수
```

## 2일차
1. 파이썬 기본
    - 변수
    - 자료형
    - 연산자
    - 흐름제어

```python
# 변수
val = 1

# 자료형
print(type(val))    # <class 'int'>

# 문자열 포맷팅
pi = 3.141592
print(f'파이는 {pi}입니다.')        # 파이는 3.141592입니다.
print(f'파이는 {pi:0.2f}입니다.')   # 파이는 3.14입니다.
print(f'파이는 {pi:10.3f}입니다.')  # 파이는          3.142입니다.
```

## 3일차
1. 파이썬 기본
    - 흐름제어
        - if
        - for
        - while
    - 구구단 프로그램
    - 함수


>>**디버깅 F5**
>>>오류를 찾거나 소스코드를 이해하기위해 사용
>>>중단점, 변수, 조사식, F10 : 다음 행 실행