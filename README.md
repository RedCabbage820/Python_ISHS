# Python_ISHS
2025 Python School Study

<hr/>

# 목차

|목차|이동|목차|이동|
|----|----|
|1차|[이동 버튼](#1차)|11차|[이동 버튼](#11차)|
|2차|[이동 버튼](#2차)|ㅡㅡㅡ|ㅡㅡㅡ|
|3차|[이동 버튼](#3차)|ㅡㅡㅡ|ㅡㅡㅡ|
|4차|[이동 버튼](#4차)|ㅡㅡㅡ|ㅡㅡㅡ|
|5차|[이동 버튼](#5차)|ㅡㅡㅡ|ㅡㅡㅡ|
|6차|[이동 버튼](#6차)|ㅡㅡㅡ|ㅡㅡㅡ|
|7차|[이동 버튼](#7차)|ㅡㅡㅡ|ㅡㅡㅡ|
|8차|[이동 버튼](#8차)|ㅡㅡㅡ|ㅡㅡㅡ|
|9차|[이동 버튼](#9차)|ㅡㅡㅡ|ㅡㅡㅡ|
|10차|[이동 버튼](#10차)|ㅡㅡㅡ|ㅡㅡㅡ|

<hr/>

# 1차

```Python

print("Hello World!")
# print("Hello World!")

#print를 입력 후 괄호를 붙이고 안에 내용 작성
#--> 원하는 결과가 출력됨
#한글,알파벳 등의 문자들은 따옴표'' 혹은 큰따옴표"" 안에 넣어야 함.
#변수나 숫자 등은 그냥 넣어야 됨

#ex)
print("나는 나다.")
print(12)
a = 12
print(a)

```

<hr/>

# 2차

```Python

# 02-1. 숫자형 자료형
"""
숫자형이란 숫자 형태로 이루어진 자료형으로.
우리가 흔히 사용하는 123 같은 정수, 12.34 같은 실수,
드물게 사용하지만 8진수나 16진수 같은 것도 있다.
"""
T = 82 #변수는 "="기호를 기준으로 지정됨.왼쪽은 이름,오른쪽은 내용임.
t = 822 #변수의 이름은 알파벳대문자 혹은 소문자로 가능하다.
T_t = 8338 #변수 이름에 기호가 들어가면 않되지만, 언더바(_)는 가능하다.
팔십이다 = 80 #파이썬은
#유니코드(세상의 모든 문자들을 전산화(전자기기 작동)되게 한 것)이 지원되기 때문에
#한글이나 히라가나, 한자나 심지어는 아랍문자도 이름이 될 수 있다.
#안정성을 위해 알파벳들과 언더바만 쓰도록 하자.

'''정수형 : '''
a = 123

'''실수형 : '''
a = -3.45

''' 8진수 : '''
a = 0o177

''' 16진수 : '''
a = 0x8FF

# 1. 사칙연산
a = 3
b = 4
a + b # 7 출력
a * b # 12 출력
a / b # 0.75 출력
# 2. x의 y제곱을 나타내는 ** 연산자
a = 2
b = 3
a ** b #8출력
# 3. 나눗셈 후 나머지를 반환하는 % 연산자
a = 7
b = 3
a % b # 1 출력
# 4. 나눗셈 후 몫을 반환하는 /,// 연산자
7 / 4 # 1.75
7 // 4 # 1 (정수값 출력)

# Q. 14를 3으로 나누었을 때 몫(정수값)과 나머지를
#    출력하시오. 몫 : 4   , 나머지 : 2



# 02-2.문자열 자료형
"""
문자열이란 문자, 단어 등으로 구성된 문자들의 집합
"Life is too short, You need Python"
"a"
"123" (따옴표로 둘러싸여 있으면 문자열로 사용)
"""
a = '123'
b = '456'
a + b # '123456

# 문자열 사용 방법
# 1. 큰 따옴표(")또는 작은 따옴표(')로 둘러싸기
 "Hello World"
 'Python is fun'
# 2. 문자열 안에 작은 따옴표나 큰 따옴표를 포함시키고 싶을 때
food = "Pyhton's favorite food is perl"
say = '"Python is very easy." he says.'
# 3. 줄 바꾸는 이스케이프 코드 '\n' 삽입하기
print("Life is too short\nYou need Python")
# 4. 작은따옴표 3개 또는 큰따옴표 3개로 줄바꾸기
multiline = '''
Life is too short
You need Python
'''

```

<hr/>

# 3차

```Python

# <예제 1>
score = 70
print("첫 번째 점수 : ", score)

# <예제 2>
# 원의 둘레 : 2*원주율(파이)*반지름(r)
# 원의 넓이 : 원주율(파이)*반지름(r)의 제곱

p = 3.141592
r = 5
result1 = 2*p*r
result2 = p*r**2
print("원의 둘레 = " , result1) #파이썬은 원래 여러개의 결과를 출력 할 수 있다.
print("원의 넓이 = " , result2)

age = 18
pi = 3.14
x = 'abc'
type(age)

```

<hr/>

# 4차

```Python

# 문자열 연산
# 1. 문자열 덧셈
head = "Pyton"
tail = "is fun!"
head + tail   # 'Python is fun!' 출력
# 2. 문자열 곱하기
a = "Python"
a * 2  # 'PythonPython'

# Q. 문자열 곱하기를 사용하여 아래와 같은 프로그램을 만드시오.
============================== # (30개)
'My Program"
============================== # (30개)

line = "="*30
p = "My Program"
print(line,"\n",p,"\n",line) # \n은 키보드의 Enter역할을 함

# 3. 문자열 길이 구하기
a = 'Life is too short'
len(a)   # 17 출력(len()은 입력받은 문장의 길이를 계산할 수 있으며,
#공백(띄어쓰기)도 개수로 계산한다.)


# 문자열 인덱싱과 슬라이싱
# 1. 인덱싱(가리킨다)
a = "Life is too short, You need python"
#    0123456789012345678901234567890123
#              1         2         3
"""
각 문자마다 번호를 매기면 L은 첫 번째 자리를 뜻하는 숫자 0,
중간에 있는 short 의 s는 12시가 된다.
※파이썬은 0부터 숫자를 센다.
※공백 문자 역시 L, i, f, e와 같은 문자와 동일하게 취급
"""
a[3]  # 'e' 출력
a[19]  # 'Y' 출력
a[-1]  # 'n' 출력 (뒤에서부터 읽기 위해 마이너스(-) 기호 사용

# 2. 슬라이싱(잘라낸다)
a = "Life is too short, You need Python"
#     0123456789012345678901234567890123
#              1         2         3
b = a[0] + a[1] + a[2] + a[3]
b   # 'Life' 출력

a[0:4] # 위와 같은 형태로 'Life' 출력
a[0:3] # 'Lif' 출력 ☆(0 <= a < 3)
a[5:7] # 'is' 출력
a[:7] # 'Life is' (시작 번호를 생략하면 문자열의 처음부터 출력
a[19:] # 'You need Python'
        # (끝 번호를 생략하면 시작 번호의 문자부터 끝까지 출력)
a[:]  # 'Life is roo short, You need python'

# Q1. 변수 a에 다음과 같은 문자열이 저장되어 있다.
#     변수 year, day, weather를 만들어 2001은 year에, 0331은 day에,
#     Rainy는 weather에 각각 저장하여 출력하시오.
#     (단, 슬라이싱 기법으로 각각의 문자열을 저장하시오.
a = "20010331Rainy"
year = a[:4]
day = a[4:8]
weather = a[8:]


# Q2. 변수 a에 'Pithon'이라는 문자열이 저장되어 있다.
#     변수 a와 문자열 'y'만 사용하여 'Python'을 출력하시오.
a = 'Pithon'
print(a[:1],'y',a[2:])

```

<hr/>

# 5차

```Python

# Q2. 변수 a에 'Pithon'이라는 문자열이 저장되어 있다.
#     변수 a와 문자열 'y'만 사용하여 'Python'을 출력하시오.
a = 'Pithon'
a[:1] + 'y' + a[2:] # 'Python'

# 2-1. 슬라이싱의 다른 기능
a = "Life is too short, You need Python"
#    0123456789012345678901234567890123
#              1         2         3
a[0:16:2]   # 'Lf stoso' 출력
# 변수이름[시작 인덱스:종료 인덱스:오프셋]
# 오프셋 숫자만큼 문자를 건너뛰면서 시작 인덱스부터
# 종료 인덱스 -1까지 출력

# Q. 다음 프로그램을 예측하시오
a = "Life is too short, You need Python"
a[3:10] #e is to
a[-10:31] #eed Pyt
a[-8:] #Life is too s
a[:-21] #Life is too s
a[30:] #thon
a[3:12:3] #eso
a[-18:28:2] #t o ed
a[-15:-3:2] #Yune y
a[2:21:] #fe is too short, Yo

```

<hr/>

# 6차

```Python

# 문자열 포매팅
"""
"현재 온도는 18도입니다."의 문자열이 시간이 지나서
기온이 20도가 되었을 때 다음 문장을 출력한다.
"현재 온도는 20도입니다."
위와 같이 문자열 안의 특정한 값을 바궈야 할 경우
이것을 가능하게 해주는 것이 문자열 포매팅이다.

문자열 포맷 코드
%s : 문자열(String) - 숫자 또는 문자열로 표현할때 사용
%c : 문자 1개(Character)
%d : 정수(Integer) - 음수, 0, 양수
%f : 실수(Floating-point)
%% : %(문자 자체)
"""
# "문장문장%d글글글" %2
# %d 부분에 숫자 2 대입
# 구조 해석
# "문장문장 넣고싶은거 글글글" 넣고싶은거

# 1. 숫자 대입
'I eat %d apples.' %3   # ' I eat 3 apples.'

# 2. 문자열 대입
'I eat %s apples.' %'five'   # ' I eat five apples.'

# 3. 변수로 대입
number = 3
'I eat %d apples.' %number   # ' I eat 3 apples.'

# Q.아래 프로그램의 실행 결과가 다음과 같을 때 빈칸에
#   들어갈 알맞은 포맷 코드는?
number = 10
day = 'three'
'I eat (1) apples, so I was sick for (2) days.' %(number,day)
# 'I eat 10 apples, so I was sick for three days.'
# 정답 : (1) : %d , (2) : %s

#정답이 입력된 완성형 코드
number = 10
day = 'three'
'I eat %d apples, so I was sick for %s days.' %(number,day)

# 4. %문자 표시
'Error is %d%.' %75 # 'Error 75%

#올바른 입력
'Error is %d%%.' %75
```

<hr/>

# 7차

```Python

#문자열 포메팅

*모맨 코드와 숫자 사용하기

#1. 정렬과 공백

"%10s"%'hi' #전체길이가 10개인 문자열 공간에서(스페이스 키 8번+"hi"2칸)

#대상되는 값을 오른쪽으로 정렬

"%-10s"%'hi' #'hi        '
"%-10sjane"%'hi' #'hi    jane'
"%3s"%'Hello' #'hello'(='%3s')

#2. 소수점 표현하기

"%f" %3.42134234 #'3.421342'
"%0.4f" %3.42134234 #'3.4213'
"%10.4f" %3.42134234 #' 3.4213'
                #(전체 길이가 1개인 문자열 공간에서
                #오른쪽으로 정렬

# Q. 다음 실행결과를 보고, 빈칸에 들어갈 말을 쓰시오

(1) "%6sjaewoo"%'Hello' #'Hellojaewoo ' (공백=1칸)
(2) "soft%3s"%'hi' # 'soft hi' (공백 1칸)
(3) "%-10.4fclass" %3.141592 #131415    class (3백개만)
(4) "class%-10.5f" %3.141592 #'class3.14159   ' (공백 3칸)

"""

"현재 온도는 18도 입니다"의 문자열이 시간이 지나 기온이 20도가 되었을 때 다음 문장을 출력한다

"현재 온도는 20도입니다"

위와 같이 문자열 안의 특정한 값을 바꿔야 할 경우

이것을 가능하게 해주는 것이 문자열 포메팅이다.





문자열 포멧 코드

%s : 문자열(숫자를 문자열로 표현할 때 또한 사용)

%c : 문자 1개(character)

%d : 정수(Integer)

%f : 실수(floating - point)

%% : '%' 출력시 사용

"""



#1. 숫자 대입

print("I eat %d apples" %3)



#2. 문자열 대입

print("I eat %s apples" %"five")



#3. 문자 대입

print("I eat %c apples" %'5')



#4. 숫자 값을 나타내는 변수로 대입

number = 3

print("I eat %d apples" %number)



# Q. 아래 프로그램의 실행 결과가 다음과 같을 때 빈칸에 들어갈 알맞은 포맷 코드는?

number = 10

day = "three"

print("I eat (1) apples. So I was sick for (2) days"%(number, day))

# answer : (1) : %d,  (2) :%s



# 5. '%' 출력

"Error is %d%%" %75



#숫자형 자료형

(1)  183.1828           #포멧코드 : %f(실수)

(2)  -2847                #포멧코드 : %d(정수)

(3) 0                         #포멧코드 : %d (")

(4) 1589                   #포멧코드 : %d (")

#문자형 자료형



(1)  'a'       #포멧코드 : %c, %d(문자 1개는 c, d 둘다 사용 가능)

(2)  "hello"     #포멧코드 : %d (문자열은 d 만 사용 가능)

(3)   274           #문자열 아니므로 c, d 전부 사용 불가

```

<hr/>

# 8차

```Python

# f 문자열 포맷팅
name = '홍길동'
age = 30
f'나의 이름은 {name}입니다. 나이는 {age}입니다.'

# 1. 수식
f'나는 내년이면 {age+1}살이 된다.'
# '나는 내년이면 31살이 된다.'

# 2. 딕셔너리(Key값과 같은 Value값을 한 쌍으로 갖는 자료형)
d = {'name':'홍길동', 'age' : 30}
f'나의 이름은 {d["name"]}입니다. 나이는 {d["age"]}입니다.

# 3. 정렬
f'{"hi":<10}'   # 'hi        ' (왼쪽 정렬)
f'{"hi":>10}'   # '        hi' (오른쪽 정렬)
f'{"hi":^10}'   # '    hi    ' (가운데 정렬)
f'{"hi":=^10}'   # '    hi    ' (가운데 정렬하고 '='문자로 공백 채우기)

# 4. 소수점 표현
y = 3.42134234
f'{y:0.4f}'     # '3.4213' (소수점 네번째 자리까지만 출력)
f'{y:10.4f}'     # '    3.4213' (소수점 네번째 자리까지만 출력하고
                 #               전체 자리수를 10으로 맞춤)

# 5. {}문자 표현
f'{{and}}'  # '{and}'

# Q. f 문자열 포매팅을 사용해 ' !!!python!!! ' 문자열을 출력하시오.
# 정답 :
f'{"!!!python!!!":^14}'
"{0:^14}".format('!!!python!!!') #이것도 가능

# 문자열 관련 함수
# 1. 문자열 길이 구하기
a = 'Life is too short'
len(a)  # 17 출력

# 2. 특정 문자의 개수 구하기(count)
a = 'hobby'
a.count('b')    # 2 출력

# 3. 위치 알려주기 1(find)
a = 'Python is the best choice'
a.find('n')     # 5
a.find('e')     # 12 (e가 처음으로 나온 위치를 반환)
a.find('k')     # -1 (찾는 문자나 문자열이 존재하지 않는다면 -1 반환)

# 4. 위치 알려주기 2(index)
a = 'Python is the best choice'
a.index('t')    # 2
a.index('k')    # 오류 발생

# 5. 문자열 삽입(join)
a = '_'
b = 'abcd'
a.join(b)   # 'a_b_c_d' (변수 a의 '_'가 변수 b에 저장된
            #            문자열 사이사이에 '_'가 삽입된)
# a.join('abcd') # 'a_b_c_d'
",".join(b) # 'a,b,c,d,'

# 6. 대문자를 소문자로 바꾸기(lower)
a = 'HI'
a.lower # 'hi'

# 7. 소문자를 대문자로 바꾸기(upper)
a = 'hello'
a.upper() # 'HELLO'

```

<hr/>

# 9차

```Python

# 문자열 관련 함수
# 1. 문자열 길이 구하기(len)
a = "Life is too short"
len(a)  # 17

# 2. 특정 문자 개수 세기(count)
a = 'hobby'
a.count('b')    # 2

# 3. 위치 알려주기 1(find)
a = 'Python is the best choice'
a.find('n')     # 5
a.find('k')     # -1 (찾는 문자나 문자열이 존재하지 않는다면 -1 반환)
a.find('e')     # 12 ('e'가 처음으로 나온 위치만 반환)

# 4. 위치 알려주기 2(index)
a.index('n')    # 5
a.index('k')    # 오류 발생

# 5. 문자열 삽입(join)
a = ','
b = 'abcd'
a.join(b)   # 'a,b,c,d'

# 6. 소문자를 대문자로 바꾸기(upper)
a = 'hi'
a.upper()   # 'HI'

# 7. 대문자를 소문자로 바꾸기(lower)
a = 'HI'
a. lower()  # 'hi'

# 8. 왼쪽 공백 지우기(lstrip) -> l은 left을 의미
a = '      hi  '
a.lstip()   # 'hi  '

# 9. 오른쪽 공백 지우기(rstrip) -> r은 right를 의미
a = '      hi  '
a.lstip()   # '      hi'

# 10. 양쪽 공백 지우기(strip)
a = '      hi  '
a.stip()   # 'hi'

# 11. 문자열 바꾸기(replace)
a = '안성은'
a.replace('안', '박')     # '박성은'

# 12. 문자열 나누기(split)
a = '인천반도체고등학교 소프트웨어과 1학년 2반'
a.split()   # ['인천반도체고등학교 소프트웨어과 1학년 2반']
b = 'a=b=c=d'
b.split('=')    # ['a', 'b', 'c', 'd']

# Q1. 다음과 같은 문자열 a:b:c:d가 있다. 이를 a#b#c#d로 바꾸려고 할 때
#     빈칸에 들어갈 말은? (단, 함수를 사용하여 출력하시오.)
a = "a:b:c:d"
b = _________
print(b)    # 'a#b#c#d' 출력

# Q1. 정답
a = "a:b:c:d"
b = a.replace(":", "#")
print(b)

# Q2. 변수 a에 저장된 '장비과'를 '소프트웨어과'로 바꾸려고 한다.
#     다음 (ㄱ), (ㄴ)에 들어갈 말은?
a = '장비과'
a.(ㄱ)('(ㄴ)', '소프트웨어')

# Q2. 정답
a = '장비과'
a.replace('장비', '소프트웨어')

# Q3. 각각의 이름을 리스트에 하나씩 저장하려고 한다. 출력값이 다음과 같을때
#     (ㄱ), (ㄴ)에 들어갈 말은?
a = '사만다르 권민성 박관용 박세민'
a.(ㄱ)('(ㄴ)')# ['사만다르', '권민성', '박관용, '박세민']

# Q3. 정답
a = '사만다르 권민성 박관용 박세민'
a.split(' ')

```

<hr/>

# 10차

```Python

# 2-3. 리스트 자료형
"""
리스트 : 물품이나 사람의 이름 따위를 일정한 순서로 적어 놓은 것.
"""

# 리스트의 형태
리스트 변수이름 = [요소1, 요소2, 요소3, ...]
odd = [1, 3, 5, 7, 9]

a = ""
b = []
c = ['Life', 'is', 'too', 'short']
d = [1, 2, 'Life', 'is']
e =[1, 2, ['Life', 'is']]
f = 123

type(a) #<class 'str'> (문자열 자료형)
type(b) #<class 'int'> (숫자형(정수) 자료형)
type(c) #<class 'str'> (리스트 자료형)

# 리스트의 인덱싱과 슬라이싱
a = [1, 2, 3]
b = ['1', '2', '3']
a   # [1, 2, 3]
a[0]    # 1
a[0] + a[2] # 4 (1+4)
b[0] + b[2] # 13 ('1'+'3')
a[-1]   # 3

# 1-1. 중첩된 리스트
a = [1, 2, 3, ['a', 'b', 'c']]
    # 0 1 2   3~~~~~~~~~~~~
    #           0    1    2
a[0]    # 1
a[3]    # ['a', 'b', 'c']
a[3][0] # 'a'

# Q1. 다음 프로그램의 결과값을 예측하여 쓰고, 해석하시오.
a = b = [1, 2, 3]
a[1] = 4
print(b)    # 결과값 : [1, 4, 3]
# 해석 : 인덱스 번호 1번(2번째 값)을 4로 바꾼다.

# Q2. 다음과 같은 삼중 리스트에서 'Life' 문자열만 출력하시오.
a = [1, 2, ['a', 'b', ['Life', 'is']]]
# 정답 :
a[2][2][0]

```

<hr/>

# 11차

```Python

# 2. 리스트의 슬라이싱(1)
a = [1, 2, 3, 4, 5]
    #0  1  2  3  4
a[0:2]  # [1, 2] (0부터 시작하고 인덱스 2의 자리 숫자는 포함하지 않는다.)
※ 문자열의 슬라이싱 방법과 같음

# 2-1. 리스트의 슬라이싱(2)
a = [0, 10, 20, 30, 40, 50, 60, 70, 80, 90]
    # 0  1   2   3   4   5   6   7   8   9
a[2:8:5]  # [20, 70]
변수[시작 인덱스:종료 인덱스:오프셋]
#오프셋 숫자만큼 문자를 건너뛰면서 시작 인덱스부터 종료 인덱스 -1까지 출력

# Q1. a = [1, 2, 3, 4, 5]에서 슬라이싱(1) 방법을 사용하여 리스트 [2, 3]을 출력하라.
# 정답 :
a = [1, 2, 3, 4, 5]
a[1:3]

# Q2. 다음 리스트에서 슬라이싱(2) 방법을 사용하여 ['a', 'c']를 출력하시오.
a = [1, 2, 3, ['a', 'b', 'c'], 4, 5]
# 정답 :
a[3][0:3:2]

# 3. 리스트 연산하기
# 3-1. 리스트 연산하기(+)
a = [1, 2, 3]
b = [4, 5, 6]
a + b    # [1, 2, 3, 4, 5, 6]

# 3-2. 리스트 반복하기(*)
a = [1, 2, 3]
a * 3   # [1, 2, 3, 1, 2, 3, 1, 2, 3]

# 3-3. 리스트 길이 구하기
a = [1, 2, 3]
len(a)  # 3

# 4. 리스트에서 수정과 삭제
# 4-1. 리스트 수정
a = [1 , 2, 3]
a[2] = 4
a    # [1, 2, 4]

# 4-2. 리스트 삭제(del 함수)
a = [1, 2, 3]
del a[1]
a   # [1, 3] (인덱스 1번 자리 요소를 삭제)

# Q. 다음 리스트에서 del 함수와 슬라이싱을 사용하여 [1, [3], 5]의 결과값을 출력하시오.
a = [1, [2, 3, 4], 5]
# 정답 :
del a[1][0:3:2]
a

```
