# codingbat
##Warm up-1

###sleep_in
\\

```
def sleep_in(weekday, vacation):
   return (not weekday or vacation)
```

###monkey_trouble
\\

```
def monkey_trouble(a_smile, b_smile):
  return(a_smile  == b_smile)
```

###sum_double
\\

```
def sum_double(a, b):
   sum = a + b
   
   if a == b:
     sum = sum * 2
   return sum
```

###diff21
\\

```
def diff21(n):
   if n <= 21:
     return abs(21 - n)
   else:
     return abs(21 - n) * 2
```

###parrot_trouble
\\

```
def parrot_trouble(talking, hour):
   return(talking and (hour < 7 or hour > 20))
```

###makes10
\\

```
def makes10(a, b):
   sum = a + b
   return(a == 10 or b == 10 or sum == 10)
```

###near_hundred
\\

```
def near_hundred(n):
   return ((abs(100 - n) <= 10) or (abs(200 - n) <= 10))
```

###pos_neg
\\

```
def pos_neg(a, b, negative):
   if negative:
     return(a < 0 and b < 0)
   else:
     return((a < 0 and b > 0) or (a > 0 and b < 0))
```

###not_string
\\

```
def not_string(str):
  if str[:3] == "not":
    return str
  return "not " + str
```

###missing_char
\\

```
def missing_char(str, n):
  return str[:n] + str[n+1:]
```

###front_back
\\

```
def front_back(str):
  if len(str) <= 1:
    return str
  return str[-1:] + str[1:-1] + str[0]
```

###front3
\\

```
def front3(str):
  if len(str) >= 3:
    return str[:3] * 3
  return str *3
```

##Warm up-2
###string_times
\\

```
def string_times(str, n):
  return (str * n)
```

###front_times
\\

```
def front_times(str, n):
  return str[:3] * n
```

###string_bits
\\

```
def string_bits(str):
  result = ""
  for i in range(len(str)):
    if i % 2 == 0:
      result = result + str[i]
  return result
```

###string_Splosion
\\

```
def string_splosion(str):
  result = ""
  for i in range(len(str)):
    result = result + str[:i+1]
  return result
```

  



