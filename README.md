# KUPYPY

### 이번 주 9.2(토) 발표
```
- Think Bayes Chp5 : 강은진
- Think Bayes Chp6 : 임진주
- HML Chp14 : 송서하, 이우진
- IP Chp8 : 이아름, 최시현
- 논문 발표(내용 알려줘..) : 정재윤
```

### 서브모듈 로드
###### KUPYPY
```bash
git clone https://github.com/KUpypy/KUPYPY
git submodule init
git submodule update
```

### 서브모듈에서 업로드
###### KUPYPY/SUBMODULE-NAME
```bash
git checkout master
git add .
git commit -m "upload from submodule"
git push origin master
```

### 양식
> [예시](http://nbviewer.jupyter.org/github/kupypy/past/blob/master/HML/Chp11/%28HML%29Chp11_Training%20Deep%20Neural%20Nets.ipynb)

```
시작은

# ChpXX. 챕터명

Header 1로 시작하고,

발표자와 발표일 기재(같은 형식으로)

그 밑에 구분선을 넣고( markdown ---)

본문 시작..

챕터명이 header 1이엇으니, 그 밑 소제목들은 전부 header 2 이상이 됨.

pdf 상에서 목차를 보면 정확히 어떤식의 구조인지 나와있으니 그것과 동일하게 작성할 것

Header로 구분을 줌

예를 들어 그림 예시에 대해서,

## Training RNNs

### Training a Sequence Class..
내용
### Training to Predict Time...
내용
### Creative RNN
내용...

## Deep RNNs
...

이런 식으로 작성해야 함.

책에서 강조하는 부분은 bold나 italic으로 꼭 표시해주기

중요한 그래프 이미지나 코드 절대 빼먹지 않기(전부 확인함)

정말 필요 없다고 생각되는 부분이 있으면 생략해도 무방함

작성법을 모를시에 정지원에게 물어봐서 꼭 처리하기(당일날 물어보면 안됨..)
```
