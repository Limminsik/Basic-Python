# 06_22 개발환경 세팅 Anaconda 
  Anaconda CMD Prompt : 마우스, 키보드가 없던 시절 명령어로 활용
   C:\Users\user>dir   존재하고 있는 파일들을 보여준다.
   C:\Users\user>cd    cd : change directory 특정 공간으로 이동하는 명령어,  cd .. : 전에 폴더로 이동
                      mkdir : make directory,  start . : file open
   C:\Users\user>python : 파이썬 실행

Jupyter Notebook / Jupyter Lab : 기능은 같다.
   C:\Users\user>Jupyter-Lab 실행 시 쥬피터 켜지면서 CMD 는 심장 역할만
   



# 06_23 Jupyter 둘러보기 - Markdown

   Markdown : Code가 아닌 텍스트 작성, https://gist.github.com/ihoneymon/652be052a0727ad59601 참고
    
# Python Class
## 셀에 대해서 배워봅시다
- 안녕하세요
  - 저는
  - 임민식입니다.

       Ctrl + shift + ' - ' = 셀 분리, shift + ' M ' = 셀 합치기
       
       명령어 치다가 Tab 누르면 명령어 자동화 및 검색 해줌 !
       
Jupyter extension 설치  https://github.com/jupyterlab/jupyterlab-toc


# 08_16 변수를 담아놓는 주머니, '자료형' 
https://aquaorinfosec.tistory.com/17
 ## CPU : 연산장치, Disk : 저장공간, RAM : context 처리공간
 - 변수 할당하기
    a = 1
 - 자료형 변수

    - 숫자( Integer 정수형, float ) : a =1, b = 2,3, c - -5
    - ### C언어의 경우 : int(a) = 1, float(b) = 2,3
    
 - list 자료형 : a = [ ],  [ ]를 이용하는것이 list
 - indexing : - 0부터 시작한다., -1 indexing : 맨 뒤, -2 indexing : 뒤에서 2번째
 - "범위" indexing : class_score[0:1] 0이상 1미만

 ## 다차원 list : [ ]
 - [[1,2], [1.2.3.]]

 ## 튜플(Tuple) : ( )
 - mutable vs immutalbe : 'tuple' object does not support item assignment
 - a = (1, 2,) _________
 
 ## 문자열(String)
    #문자열이란 문자, 단어 등으로 구성된 문자들의 집합 
 - 문자열 = 스트링(String) = 문자열 스트링(String)

 
 ## 딕셔너리(dict)
    #딕셔너리 자료형은 키(Key)와 값(Value)의 쌍으로 이루어진다.
  - Hashtable 메모리 저장 방식
  - 리스트와의 차이 : Find operation speed

## 집합(set)
    #집합은 원소의 순서가 유지되지 않고, 중복 원소를 갖지 않는다. 
  - 

## 불(Bool, Boolean)
    #True / False 의 값을 갖는 변수
  - a = True, b = False
  - a < 1
  - a == -1,  == : ~와 같니 ? 
