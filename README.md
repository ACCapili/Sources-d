# Sources-d
def multiply(a, b):
  return a * b
multiply(5, 4)
20

def is_long(word):
  if len(word) > 8:
     return f"{word} is a long word."
is_long("artificial")
'artificial is a long word.
'
def addition(*args):
   result = 0
   for i in args:
      result += i
   return result
print(addition(1,4))
5
print(addition(1,7,3))
11

def arg_printer(a, b, option=True, **kwargs):
   print(a, b)
   print(option)
   print(kwargs)
arg_printer(3, 4, param1=5, param2=6)
3 4
True
{'param1': 5, 'param2': 6}

a = [4,6,7,3,2]
b = [x for x in a if x > 5]
b
[6, 7]

