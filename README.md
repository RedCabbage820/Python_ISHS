# Python_ISHS
2025 Python School Study

<hr/>

# 목차

|목차|이동|
|----|----|
|1차|[이동 버튼 1](#1차)|
|2차|[이동 버튼 2](#2차)|
|3차|[이동 버튼 3](#3차)|
|4차|[이동 버튼 4](#4차)|
|5차|[이동 버튼 5](#5차)|
|6차|[이동 버튼 6](#6차)|
|7차|[이동 버튼 7](#7차)|
|8차|[이동 버튼 8](#8차)|
|9차|[이동 버튼 9](#9차)|
|10차|[이동 버튼 10](#10차)|
|11차|[이동 버튼 11](#11차)|
|12차|[이동 버튼 12](#12차)|
|13차|[이동 버튼 13](#13차)|
|14차|[이동 버튼 14-1](#14-1차)|
|-|[이동 버튼 14-2](#14-2차)|
|15차|[이동 버튼 15](#15차)|
|16차|[이동 버튼 16](#16차)|
|17차|[이동 버튼 17](#17차)|

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
print(a[:1]+'y'+a[2:])

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
<hr/>

# 12차

```Python

# 5. 리스트 관련 함수
# 5-1. 리스트에 요소 추가(append : 덧붙이다, 첨부하다)
a = [1, 2, 3];
a.append(4)
a   # [1, 2, 3, 4]
a.append([5, 6])    # 리스트 안에는 어떤 자료형도 추가할 수 있다.
a   # [1, 2, 3, 4, [5, 6]]

# 5-2. 리스트 정렬(sort : 분류하다, 구분하다)
a = [2, 1, 3, 4]
a.sort()
a   # [1, 2, 3, 4]
a = ['d', 'c', 'b', 'a']
a.sort()
a   # ['a', 'b', 'c', 'd']

# 5-3. 리스트 뒤집기(reverse : 뒤바꾸다, 반전시키다)
a = ['a', 'b', 'c', 'd']
a.reverse()
a   # ['d', 'c', 'b', 'a'] (현재 리스트 그 자체에서 거꾸로 뒤집는다.)

# Q. [1,3,5,4,2] 리스트를 [5,4,3,2,1]로 바꾸려고 한다.
#   빈칸에 들어갈 함수는?
a = [1,3,5,4,2]
a.___________   # [1,2,3,4,5] 출력
a.___________   # [5,4,3,2,1] 출력
#정답
a = [1,3,5,4,2]
a.sort()
a.reverse()

# 5-4. 위치 반환(index : 색인(필요한 정보를 찾아낸다.))
a = ['a', 'b', 'c', 'd']
      0    1    2    3
a.index('b')    # 1 출력 (1은 a의 두번째 요소(a[1])를 나타낸다.)
a.index('d')    # 3 출력 (a[3])

# 5-5. 리스트에 요소 삽입(insert : 끼워넣다, 삽입하다)
a = [1, 2, 3]
a.insert(0,4)
a   # [4, 1, 2, 3] (a[0] 위치에 4를 삽입한다.)
a.insert(3,5)
a   # [4, 1, 2, 5, 3]

# 5-6. 리스트 요소 제거(remove : 내보내다)
a = [1, 2, 3, 1, 2, 3]
a.remove(3)
a   # [1, 2, 1, 2, 3]
    # 3이라는 값을 2개 가지고 있을 경우 첫번째 3만 제거된다.)
a.clear()
a   # []

# 5-7. 리스트 요소 끄집어내기(pop : 펑하고 터지다)
a = [1, 2, 3]
a.pop() # 리스트의 맨 마지막 요소를 출력
a   # [1, 2] (그 요소를 삭제)
a = [1, 2, 3]
a.pop(1)    # 2
a   # [1, 3] (a[1]의 값을 출력하고 a[1]의 값을 리스트에서 삭제한다.)

# 5-8. 리스트에 포함된 요소 x의 개수 세기(count)
a = [1, 2, 3, 1]
a.count(1)  # 2
            # 1이라는 값이 리스트 a에 2개가 들어있으므로 2를 출력

# 5-9. 리스트 확장(extend)
a = [1, 2, 3]
a.extend([4])
a   # [1, 2, 3, 4]
a.extend([5, 6, 7])
a   # [1, 2, 3, 4, 5, 6, 7]
b = [8, 9]
a.extend(b)
a   # [1, 2, 3, 4, 5, 6, 7, 8, 9]

# Q1. 다음 프로그램에서 빈칸에 알맞은 말을 넣으시오.
a = ['a', 'b', 'c', 'd']
result = __________
print(a)    # ['a', 'c', 'd']
prind(result)   # 'b'
# 정답 :
a = ['a', 'b', 'c', 'd']
result = a.pop(3)
print(a)
print(result)

# Q2. ['Life', 'is', 'too', 'short'] 리스트를 Life is too short
#   문자열로 만들 때 빈칸에 들어갈 말은?
a = ['Life', 'is', 'too', 'short']
result = ___________
print(result)   # Life is too short 출력
# 정답 :
a = ['Life', 'is', 'too', 'short']
result = " ".join(a)
print(result)

```

<hr/>

# 13차

```Python

# Q. 다음 프로그램의 실행결과를 보고 빈칸에 숫자를 순서대로 쓰시오.
a = b = [1, 2, 3]
a[_] = _
print(b)    # [1, 4, 3]
# 정답 :
a = b = [1, 2, 3]
a[1] = 4


# 02-4. 튜플 자료형
"""
리스트와 거의 비슷하지만 몇가지 다른 점이 있다.
-리스트는 []로 감싸지만 튜플은 ()로 감싼다.
-리스트는 값을 생성, 삭제, 수정이 가능하지만 튜플은 값을 바꿀 수
 없다.
 (튜플의 요소값을 지우거나 변경하려고 하면 오류가 발생함)
"""
# 튜플의 형태
a = ()
b = (1,)    # 하나의 요소만을 가질 때는 요소 뒤에 콤마(,)를
            # 반드시 붙인다.
c = (1, 2, 3)
d = 1, 2, 3     # 괄호를 생략해도 사용 가능함
e = ('a', 'b', ('ab', 'cd'))

# Q. 다음 프로그램의 결과값을 보고 빈칸에 들어갈 말을 순서대로
#    쓰시오.
color = 247, 129, 216
___, ___, ___ = color
print(red)   # 216
print(blue)  # 247
print(green) # 129
# 정답
color = 247, 129, 216
blue, green, red = color
print(red)
print(blue)
print(green)

# Q. 다음 프로그램의 결과값을 보고 빈칸에 들어갈 말을 순서대로
#    쓰시오.
a, b, c = 57, 287, 46
a, b, c = __, __, __
print(a)    # 287
print(b)    # 46
print(c)    # 57
# 정답
a, b, c = 57, 287, 46
a, b, c = b, c, a
print(a)
print(b)
print(c)

```

<hr/>

# 14-1차

```Python

a = [1, 2, 3]
a.pop() # 3
a   # [1, 2]

a = [1, 2, 3]
a.insert(0,4)   # [4, 1, 2, 3]

```

# 14-2차

```Python

# 02-4. 튜플 자료형
"""
리스트와 거의 비슷하지만 몇가지 다른 점이 있다.
 - 리스트는 []로 둘러싸지만 튜플은 ()로 둘러싼다.
 - 리스트는 값을 생성, 수정, 삭제가 가능하지만 튜플은 값을
 - 바꿀 수 없다.
   (튜플의 요소를 지우거나 변경하려고 하면 오류가 발생한다.)
"""

# 튜플의 형태
a = ()
b = (1,)    # 하나의 요소만을 가질 때는 요소 뒤에 콤마(,)를 반드시 붙여야함
c = (1, 2, 3)
d = 1, 2, 3 # 괄호를 생략해도 튜플로 사용 가능함
e = ('a', 'b', ('ab', 'cd'))

# Q. 다음 프로그램의 결과값을 예측하여 빈칸에 쓰시오.
color = 129, 247, 216
reed, green, blue = color
print(blue) # 결과값 : 216
print(green) # 결과값 : 247
print(red) # 결과값 : 129

# 튜플 다루기
# 1. 인덱싱
t1 = (1, 2, 'a', 'b')
    # 0  1   2    3
t1[0]   # 1 출력
t1[3]   # 'b' 출력

# 2. 슬라이싱
t1 = (1, 2, 'a', 'b')
t1[::2] # (1, 'a') 출력
        # 처음부터 끝가지 2칸씩 건너 뛰면서 출력

# 3. 튜플 더하기
t1 = (1, 2, 'a', 'b')
t2 = (3, 4)
t1 + t2   # (1, 2, 'a', 'b', 3, 4) 출력

# 4. 튜플 곱하기
t2 = (3, 4)
t2 * 3    # (3, 4, 3, 4, 3, 4) 출력

# 5. 튜플 길이 구하기
t1 = (1, 2, 'a', 'b')
len(t1) # 4 출력 (튜플 요소의 개수를 출력)

# Q1. a = (1, 2, 3)이라는 튜플에 값 4를 추가하여 (1, 2, 3, 4)를
#   만들어 출력하시오.
# 정답
a = (1, 2, 3)
a + (4,)

# Q2. 다음과 같은 두 변수를 이용하여 아래와 같이 두가지
#     결과값을 나타내려고 한다. 가능한 방법을 서술하시오.
x = (1, 2, 3)
y = [4, 5, 6]

# 결과값 : (1,2,3,4,5,6)
# 결과값 : [1,2,3,4,5,6]
# 정답
x + tuple(y,)
list(x) + y
```
<hr/>

# 15차

```Python

# 튜플의 패킹과 언패킹
# 1. 패킹(묶다)
human = (180, 60)
print(human)    # (180, 60)

#2. 언패킹(풀어내다)
human = (180, 60)
height, weight = human  # human 변수에 저장된 요소들이
                        # 순서대로 하나씩
                        # height와 weight애 저장됨
print(height)   # 180
print(weight)   # 60

# Q. 다음 프로그램의 결과값을 예측하여 빈칸에 쓰시오.
a, b, c = 57, 287, 46
a, b, c = b, c, a
print(a)    # 결과값 : ______
print(b)    # 결과값 : ______
print(c)    # 결과값 : ______
# 정답 :
a, b, c = 57, 287, 46
a, b, c = b, c, a
print(a)    # 결과값 : 287
print(b)    # 결과값 : 46
print(c)    # 결과값 : 57


# 02-5. 딕셔너리 자료형
"""
연관 배열 또는 해시라고도 하며, Key와 Value를 한 쌍으로 갖는 자료형이다.
"""

# 딕셔너리의 형태
"""
Key와 Value의 여러 개의 쌍이 {}로 둘러싸여있고,
Key:Value 형태로 이루어져 있으며, 쉼표(,)로 구분되어 있다.
"""
{Key1: Value, Key2: Value2, ...}

# 딕셔너리의 예(1)
a = {'name':'pey','phone':'01023532838','birth':'11-18'}
Key : name, phone, birth
Value : pey, 01023532838, 11-18

# 딕셔너리의 예(2)
a = {1:'hi'}    # Key: 1, Value: 'hi'
b = {'a':[1,2,3]}   # Key: 'a', Value: [1,2,3]
                    # Value 값에 리스트 사용 가능

# 딕셔너리 쌍 추가. 삭제하기
# 1. 딕셔너리 쌍 추가하기
a = {1:'a'}
a[2] = 'b'  # {2:'b'} 쌍 추가
            # 리스트나 튜플의 a[2]와는 전혀 다름
            # Key에 해당하는 2를 나타냄
a   # {1: 'a', 2: 'b'}
a['name'] = 'pey'
a   # {1: 'a', 2: 'b', 'name': 'pey'}
a[3] = [1,2,3]
a   # {1: 'a', 2: 'b', 'name': 'pey', 3: [1,2,3]}

# 2. 딕셔너리 쌍 삭제하기
del a[1]    # Key값이 1인 Key:Value 쌍 삭제
a   # {2: 'b', 'name': 'pey', 3: [1,2,3]}

# Q. 다음 딕셔너리 a에서 'B'에 해당되는 값을 추출해보자.
a = {'A': 90, 'B': 80, 'C': 70}
result = _______________
print(a)    # {'A':90, 'C': 70} 출력
print(result)   # 80 출력
# 정답 :
a = {'A': 90, 'B': 80, 'C': 70}
result = a.pop('B')
print(a)    # {'A':90, 'C': 70} 출력
print(result)   # 80 출력

```

<hr/>

# 16차

```Python

# 딕셔너리 사용 방법
# 1. Key 값을 사용해 Value 얻기(1)
grade = {'pey': 10, 'julliet': 99}
grade['pey']    # 1 출력
                # Key 값이 'pey'인 딕셔너리의 Value를 반환
# 1-1. Key값을 사용해 Value 얻기(2)
a = {1:'a', 2:'b'}
a[1]    # Key 값이 1인 요소의 Value를 반환
        # ※ 딕셔너리에서의 a[1]은 리스트나 튜플의 a[1]과는 전혀 다름
        #   딕셔너리 변수에서 []안의 숫자 1은 두번째 요소를 뜻하는 것이
        #   아니라 Key에 해당하는 1을 나타낸다.
        # 'a' 출력

# 2. 딕셔너리를 만들 때 주의할 사항(1)
a = {1:'a', 2:'b'}  # 1이라는 Key값이 중복으로 사용
a   # {1: 'b'}
    # 1:'a' 쌍이 무시됨
# 2-1. 딕셔너리를 만들 때 주의할 사항(2)
a = {[1,2]:'hi'}    # Key 값에 리스트 사용 불가
a   # 오류 발생
    # ※ 딕셔너리의 Key 값을 설정하는 기준은 값이 변하는지 변하지 않는지에
    # 달려 있다. Key 값에 넣을 값이 변한다면 사용 불가,
    # 변하지 않는다면 사용 가능

# 정리
"""
(1) 딕셔너리의 Value 값에 리스트 사용 가능
(2) 딕셔너리의 리스트나 튜플의 인덱싱, 슬라이싱 사용 불가
(3) 딕셔너리의 Key 값에 리스트는 쓸 수 없지만, 튜플은 사용 가능
(4) 딕셔너리의 Key 값에 딕셔너리 사용 불가
"""

# 딕셔너리의 관련 함수
# 1. Key 리스트 만들기(keys())
a = {'name':'pey', 'phone': '01012341234', 'birth': '11-18'}
a.keys()    # dict_keys(['name', 'phone', 'birth'])
            # Key 값들만 모아서 객체 형태로 출력
list(a.keys())  # ['name', 'phone', 'birth']
                # Key 값들만 모아서 리스트 형태로 출력

# 2. Value 리스트 만들기(values())
a = {'name':'pey', 'phone': '01012341234', 'birth': '11-18'}
a.values()  # dict_values(['pey', '01012341234', '11-18'])
list(a.values())    # ['pey', '01012341234', '11-18']

# 3. Key:Value 쌍 얻기(items())
a.items()
# dict_items([('name', 'pey'), ('phone', '01012341234'), ('birth', '11-18')])

# 4. Key:Value 쌍 모두 지우기(clear())
a.clear()
a   # {}
    # 빈 딕셔너리

# 5. Key 값으로 Value 얻기(get())
a = {'name':'pey', 'phone': '01012341234', 'birth': '11-18'}
a['name']   # 'pey' 출력
a.get('name')   # 출력
# 5-1. Key 값이 없을 경우(get(x, '결과값')
a.get('weight', '70kg')     # '70kg'

# 6. 해당 Key 값이 딕셔너리 안에 존재하는지 확인하기(in)
a = {'name':'pey', 'phone': '01012341234', 'birth': '11-18'}
'name' in a    # True
'email' in a   # False

# 딕셔너리 month에 3월부터 4월까지 추가하는 프로그램을 작성해보자.
month = {'1월': 'january', '2월':'Fabruary','5월':'May'}
# 실행결과
month   # {'1월': 'january', '2월':'Fabruary', '3월':'March','4월':'April'}

# 정답
month = {'1월': 'january', '2월':'Fabruary'}
del month['5월']
month['3월'] = 'March'
month['4월'] = 'April'
month


# 02-6. 집합 자료형(세트)
"""
집합에 관련된 것을 쉽게 처리하기 위해 만든 자료형
set 키워드를 사용해 만들 수 있다.
"""

# 집합 자료형의 형태
s1 = set("Hello")
print(s1)   # {'l', 'o', 'H', 'e'}
            # 문자열 입력 가능
s2 = set([1,2,3])
print(s2)   # {1, 2, 3}
            # 리스트 사용 가능

# 집합 자료형의 특징
# - 중복을 허용하지 않는다.
# - 숫서가 없다.
# - 빈 세트를 생성할 때는 s = set() 사용
    # (s = {}와 같이 만들면 세트 형식이 아니라 빈 딕셔너리 형식으로 만들어짐
# - 인덱싱과 슬라이싱을 지원하지 않는다. (리스트나 튜플로 변환 후 가능)
s1 = set([1,2,3])
l1 = list(s1)   # 리스트로 변환
print(l1)   # [1, 2, 3] 출력
t1 = tuple(s1)  # 튜플로 변환
print(t1)   # (1, 2, 3) 출력

# Q. 집합 자료형의 특징을 이용하여 다음 리스트 a에서 중복 숫자를
#    제거하지오.
a = [1, 1, 1, 2, 2, 3, 3, 4, 4, 5]
aSet = ________    # a 리스트를 집합 자료형으로 변환
b = ________    # 집합 자료형을 리스트 자료형으로 다기 변환
print(b)    # [1, 2, 3, 4, 5] 출력
# 정답
a = [1, 1, 1, 2, 2, 3, 3, 4, 4, 5]
aSet = set(a)
b = list(aSet)
print(b)

# Q. 다음과 같은 삼중 리스트에서 'Life' 문자열만 출력하려고 한다.
#   (ㄱ), (ㄴ), (ㄷ)에 들어갈 숫자를 각각 쓰시오
#   정답 : (ㄱ)    2 , (ㄴ)     2, (ㄷ)    0
a = [1, 2, ['a', 'b', ['Life', 'is']]]
a[ㄱ][ㄴ][ㄷ]

# Q. 다음 프로그램에서 빈칸 안에 들어갈 말은?
#   정답 : (ㄱ) a.pop('B')
a = {'A': 90, 'B': 80, 'C': 70}
result = (ㄱ)
print(a)    # {'A':  90, 'C':70} 출력
print(result)   # 80 출력

```

<hr/>

# 17차

```Python

print("언젠간 배움")

```

<hr/>
