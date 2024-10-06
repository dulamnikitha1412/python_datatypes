# python_datatypes
python datatypes

1) Integer (int) ---->  whole numbers <br>
Ex: 0,3,9,100,-4,-78...etc <br>

Format Specifier for int is %d or %i <br>

2) Float ----> Having Decimal values or containing point values <br>
   Ex: 0.1, 5.7 , -4.7.....etc <br>

Format Specifer for float is %f <br>

3) String (str) :- <br>

Anything enclosed between single quotes or double quotes
or triple quotes or three times double quotes kept inside
the print statement or assigned to a variable is called strings.

Format Specifier for string is %s <br>
Ex: print('hi'); print("hi"); print('''hi'''); print("""hi""")<br>

a='hey' ; b="hey" ; c='''hey''' ; d="""hey"""<br>


4) Boolean (bool):-<br>

The Bool will give the answer in True or False.
Depending upon the statement.

Ex:  print(4<2) # False ; print(6>1)  # True

In python if we see a word starting with is , then it 
results our answer in terms of bool ( True/False)


------------------------------------------------------
How to check the datatype given by me is of which type?

type() method will let us know it is of which datatype.<br>

''' About Integer Data Type  '''<br>
print(type(6))<br>
print(type(2))<br>
print(type(0))<br>
print(type(-7))<br>

a=6<br>
print(a)<br>
print('%d' %a)<br>
print('%i' %a)<br>

-------------------------------------

"""" Float Data Type"""<br>
print(type(0.0))<br>
print(type(2.3))<br>
print(type(-6.7))<br>
print(type(.3))<br>

b=4.7 <br>
print(b)<br>
print('%f' %b) <br>
print('%.1f' %b)<br>
print('%.2f' %b)<br>
print('%.3f' %b)<br>
print('%3f' %b)<br>
print('%8f' %b)<br>
print('%9f' %b)<br>
print('%12f' %b)<br>

print(type('hi')) <br>
print(type('8')) <br>
print(type('4.7')) <br>

a='hi' ; b="bye" ; c='''chai'''; d="""die"""<br>
print(a,type(a))<br>
print(b,type(b))<br>
print(c,type(c))<br>
print(d,type(d))<br>

print('%s'%b)<br>
print('%s'%a)<br>
print('%s'%c)<br>

print(type(True))<br>
print(type(False))<br>
print(6<7) # True<br>
print(4>7) # False<br>
print(7==7) # True<br>
print(7!=7) # False<br>

print('hey'.isidentifier())<br>
print('_hey'.isidentifier())<br>
print('5hey'.isidentifier())






