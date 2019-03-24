# python-basics

1. 변수명 만들기
     예약어를 제외한 글자를 변수명으로 사용한다.
     예약어: False, continue, if, else, abs, from, def, global, is , finally, None
     변수명의 첫글자는 밑줄문자 또는 영문자로 시작한다.
     
2. 변수에 값 대입하기
     파이선은 자료형을 따로 명시하지 않는다.
     변수에 값이 대입되는 시점에 자료형이 자동적으로 지정
     ~~~python
     number=1
     number+1
     pi = 3.14
     pi*2
     
     ~~~
3. 자료형 개념
   >수치형 자료
    >>int_data = 1 \
    >>float_data = 3.14\
    >>complex_data = 1+5j
   
   >문자열 자료
   >>str_data = 'I love Python'\
   >>str_data1 = '반갑습니다'
    
   >리스트 자료 : 객채를 순서있게 나열
   >>list_data = [1,2,3]
   
   >튜플 자료 : 객체를 순서있게 나열하지만 요소 값을 변경할 수 없음
   >>tuple_data = (1,2,3)
   
   >사전 자료 : '키: 값'으로 된 한 쌍이 요소로 구성. 순서가 없으며 키를 이용하여 대응 값을 찾음
   >>dict_data = {0:'False', 1:'True'}

4. if문 개념
```python
x = 1
y = 2

if x >= y:
     print('x가 y보다 크거나 같습니다.')
else:
     print('x가 y보다 작습니다.')
```

5. if~elif문
```python

x = 1
y = 2

if x > y:
     print('x가 y보다 크거나 같습니다.')
elif x < y:
     print('x가 y보다 작습니다.')
else:
     print('x와 y가 같습니다')
```

6. for문
```python
str='abcdef'
for x in str:
    print(X)
```

```python
scope = [1,2,3,4,5]
for x in scope:
    print(x)
```

7. 자료형 출력 개념
```python
a = 200
msg = 'I love Python'
list_data = {'a':97, 'b':98}
print(a)
print(msg)
print(list_data)
print(list_data[0])
print(dict_data)
print(dict_dict['a'])
```

```python
dic=['a':97, 'b':98, 'c':99, 'd':100]
for x in dic:
    print(x)
```

```python
for x in range(10)
    print(x)
```

8. for,continue,break 문
```python
scope = [1,2,3,4,5]
for x in scope:
    print(x)
    if x < 3:
         continue
    else:
         break
```

9. for~else 문
```python
scope = [1,2,3]
for x in scope:
    print(x)
else:
    print('Perfect')
```

10. while 문
```python
x = 0
while x < 10:
    x = x+1
    if x < 3:
         continue
    print(x)
    if x > 7:
         break
```

```python
x = 1
total = 0
while 1:
    total = tatal + x
    if total > 100000:
         print(x)
         print(total)
         break
    x = x + 1
```



