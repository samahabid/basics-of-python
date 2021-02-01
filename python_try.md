```python
print("\tpython")
```

    	python
    


```python
print("language:\npython\njava")
```

    language:
    python
    java
    


```python
message="hello world"
print(message)
```

    hello world
    


```python
name="samah"
print(name.upper())
print(name.lower())
```

    SAMAH
    samah
    


```python
first_name='samah'
last_name='abid'
print(first_name,last_name)
```

    samah abid
    


```python
print('samah','abid',sep='#')
```

    samah#abid
    


```python
first_name="samah"
last_name="abid"
full_name=f"{first_name} {last_name}"
print(full_name)
```

    samah abid
    


```python
print(f"my name is {full_name}")
```

    my name is samah abid
    

num=100
print(num)


```python
num=100
print(num)
```

    100
    


```python
print(2/3)
```

    0.6666666666666666
    


```python
print(12//5)
```

    2
    


```python
print((2*3)+5)
```

    11
    


```python
print(0.1 + 0.5)
```

    0.6
    


```python
print(2/2)

```

    1.0
    


```python
x,y,z=1,2,3
print(z)
```

    3
    


```python
names=['ali','ahmed','sara','mona']
print(names)
```

    ['ali', 'ahmed', 'sara', 'mona']
    


```python
names[-1]
```




    'mona'




```python
names[0]='max'
print(names)
```

    ['max', 'ahmed', 'sara', 'mona']
    


```python
names.append('eman')
names
```




    ['max', 'ahmed', 'sara', 'mona', 'eman']




```python
new_names=[]
new_names.append('egypt')
new_names.append('US')
new_names.append('india')
new_names.append('turkey')
new_names
```




    ['egypt', 'US', 'india', 'turkey']




```python
l1=['s','a','m']
l2=['a','h']
l1.extend(l2)
l1
```




    ['s', 'a', 'm', 'a', 'h']




```python
new_names.insert(3,'England')
new_names
```




    ['egypt', 'US', 'india', 'England', 'turkey']




```python
del (new_names[2])
new_names
```




    ['egypt', 'US', 'England', 'turkey']




```python
poped_name=new_names.pop()
poped_name
```




    'England'




```python
names=['ali','ahmed','sara','mona']
names.remove('mona')
names
```




    ['ali', 'ahmed', 'sara']




```python
nums=[4,2,3,1,5]
nums.sort()
nums
```




    [1, 2, 3, 4, 5]




```python
nums=[4,2,3,1,5]
nums.sort(reverse=True)
nums
```




    [5, 4, 3, 2, 1]




```python
len(nums)
```




    5






```python
nums[3]
```




    2




```python
names=['ali','ahmed','sara','mona']
for name in names:
    print(name)
```

    ali
    ahmed
    sara
    mona
    


```python
names=['ali','ahmed','sara','mona']
for name in names:
    print(name)
print('unknown')    
```

    ali
    ahmed
    sara
    mona
    unknown
    


```python
for value in range(1,5):
    print(value)
```

    1
    2
    3
    4
    


```python
numbers=list(range(1,16,2))
numbers
```




    [1, 3, 5, 7, 9, 11, 13, 15]




```python
names=['ali','ahmed','sara','mona']
print(names[0:3])
print(names[2:3])
print(names[:3])
print(names[2:])
```

    ['ali', 'ahmed', 'sara']
    ['sara']
    ['ali', 'ahmed', 'sara']
    ['sara', 'mona']
    mona
    


```python
names=['ali','ahmed','sara','mona']
lower_names=[i.upper()for i in names]
lower_names
```




    ['ALI', 'AHMED', 'SARA', 'MONA']




```python
string_list = ["a", "B", "C"]

for i in range(len(string_list)):


    string_list[i] = string_list[i].lower()


print(string_list)
```

    ['a', 'b', 'c']
    


```python
dimension=(250,100)
print(dimension[0])
```

    250
    


```python
for i in dimension:
    print(i)
```

    250
    100
    


```python
user={'Name':'sama','age':20}
print(user['Name'])
```

    sama
    


```python
user={'Name':'sama','age':20}
user['country']='Egypt'
user['Phone']= 2345566
user

```




    {'Name': 'sama', 'age': 20, 'country': 'Egypt', 'Phone': 2345566}




```python
user['country']='USA'
user
```




    {'Name': 'sama', 'age': 20, 'country': 'USA', 'Phone': 2345566}




```python
del(user['country'])
user
```




    {'Name': 'sama', 'age': 20, 'Phone': 2345566}




```python
favouraties_lang={'ahmed':'python','ali':'c','ali':'c++','mona':'python'}
favouraties_lang['ali']
```




    'c++'




```python
favouraties_lang['mohamed']
```


    ---------------------------------------------------------------------------

    KeyError                                  Traceback (most recent call last)

    <ipython-input-83-e7b089029471> in <module>
    ----> 1 favouraties_lang['mohamed']
    

    KeyError: 'mohamed'



```python
for k,v in user.items():
    print(f'\nk:{k}')
    print(f'v:{v}')
    
```

    
    k:Name
    v:sama
    
    k:age
    v:20
    
    k:Phone
    v:2345566
    


```python
age=15
if age!=19:
    print('cannot vote')
```

    cannot vote
    


```python
names=['mohamed','ahmed','sara','mona']
for i in names:
    if i=='ahmed':
        print(i.upper())
    else:
        print(i.title())
```

    Mohamed
    AHMED
    Sara
    Mona
    


```python
msg=input('please enter ypur problem')
msg
```

    please enter ypur problemffff
    




    'ffff'




```python
name=input('please enter your name')
print(f'\nHello,{name}!')
```

    please enter your namesama
    
    Hello,sama!
    


```python
num=1
while num<=5:
    print(num)
    num+=1
```

    1
    2
    3
    4
    5
    


```python
def say_hello():
    print('hello')
say_hello()
```

    hello
    


```python
def say_hello(user_name):
    print(f'\nhello',user_name)
say_hello('ahmed')
```

    
    hello ahmed
    


```python
a=(10**3+2*10)-(0.5* 10**-3)
b=(10**2)+(2*10**-5)
Equ=a/b
print(Equ)
```

    10.199992960001408
    


```python
def group_txt(group_name):
    print(len(group_name))
group_txt('Dsc machine learning on Track')   
```

    29
    


```python
names=['ali','mohamed','mahmoud','ahmed']
print(names[-2])
```

    mahmoud
    


```python
print(3**4)
```

    81
    


```python
txt='Hello world'
print(txt[2:5])
```

    llo
    


```python
car={'brand':'ford','model':'mustang','year':1964}
print(car.pop('model'))
```

    mustang
    


```python
my_dict={'key1':[1,2,3],'key2':['Item0','Item1','Item2']}
print(my_dict['key2'][-3].lower())
```

    item0
    


```python
tp=(1,2,3)
print(2*tp)
```

    (1, 2, 3, 1, 2, 3)
    

t1=(1)
t2=(3,4)
t1+=5
print(t1)
print(t1+t2)


```python
t1= (1)
t2 = (3,4)
t1 + = 5
print(t1)
print(t1+t2)
```


      File "<ipython-input-120-6f8237b93c5b>", line 3
        t1+ = 5
            ^
    SyntaxError: invalid syntax
    



```python
l1=[]
l1.append([1,[2,3],4])
l1.extend([7,8,9])
print(l1[0][1][1]+l1[2])
```

    11
    


```python
l1=[2,1.33,'mach',0,'ine',None,'G',True]
val1=0
val2=0
for x in l1:
    if (type(x)==int or type(x)==float):
        val1 +=x
    elif(type(x)==str):
         val2 +=x
    else:
        break
print(val1,val2)        
        
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-138-0fa02691156a> in <module>
          6         val1 +=x
          7     elif(type(x)==str):
    ----> 8          val2 +=x
          9     else:
         10         break
    

    TypeError: unsupported operand type(s) for +=: 'int' and 'str'



```python
d=[]
for i in[1,2,3,4][::-1]:
    d.append(i)
print(d)        
```

    [4, 3, 2, 1]
    


```python
d={'k1':[1,2,{'k2':['this is tricky',{'tough':[1,2,['hello']]}]}]}
print(d['k1'][2]['k2'][1]['tough'][2][0])
```

    hello
    


```python
t=(1,2,3,4,5,6,7,8)
print(t[t[t[6]-3]-6])
```

    8
    


```python
a=[ 1.        ,  1.18367347,  1.36734694,  1.55102041,  1.73469388,
        1.91836735,  2.10204082,  2.28571429,  2.46938776,  2.65306122,
        2.83673469,  3.02040816,  3.20408163,  3.3877551 ,  3.57142857,
        3.75510204,  3.93877551,  4.12244898,  4.30612245,  4.48979592,
        4.67346939,  4.85714286,  5.04081633,  5.2244898 ,  5.40816327,
        5.59183673,  5.7755102 ,  5.95918367,  6.14285714,  6.32653061,
        6.51020408,  6.69387755,  6.87755102,  7.06122449,  7.24489796,
        7.42857143,  7.6122449 ,  7.79591837,  7.97959184,  8.16326531,
        8.34693878,  8.53061224,  8.71428571,  8.89795918,  9.08163265,
        9.26530612,  9.44897959,  9.63265306,  9.81632653, 10.        ]
print(dtype(a))
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-140-539e31ac07ac> in <module>
          9         8.34693878,  8.53061224,  8.71428571,  8.89795918,  9.08163265,
         10         9.26530612,  9.44897959,  9.63265306,  9.81632653, 10.        ]
    ---> 11 print(dtype(a))
    

    NameError: name 'dtype' is not defined

