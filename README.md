================================================================================
   PCEP DARAJASI — VARIANTLI TEST (FOR / WHILE / FUNCTIONS)
================================================================================
Daraja: PCEP-30-02
Savollar soni: 30 ta
Ko'rsatma: Har bir kodning natijasini aniqlang.
================================================================================


1-SAVOL
   def f(n):
       s = 0
       for i in range(1, n + 1):
           s += i
       return s
   print(f(5))
   a) 10    b) 15    c) 5     d) 25


2-SAVOL
   def f(n):
       s = 0
       for i in range(n):
           s += 1
       return s
   print(f(4))
   a) 3     b) 4     c) 5     d) 0


3-SAVOL
   def f(x):
       return x * 2
   print(f(3) + f(4))
   a) 14    b) 7     c) 24    d) 10


4-SAVOL
   def f(a, b=10):
       return a + b
   print(f(5))
   a) 5     b) 15    c) 10    d) Xato


5-SAVOL
   def f(a, b=10):
       return a + b
   print(f(5, 2))
   a) 15    b) 7     c) 12    d) 52


6-SAVOL
   def f(n):
       c = 0
       for i in range(1, n + 1):
           if i % 2 == 0:
               c += 1
       return c
   print(f(10))
   a) 4     b) 5     c) 6     d) 10


7-SAVOL
   def f(n):
       i = 0
       c = 0
       while i < n:
           c += i
           i += 1
       return c
   print(f(4))
   a) 6     b) 10    c) 4     d) 3


8-SAVOL
   def f(n):
       r = 1
       for i in range(1, n + 1):
           r *= i
       return r
   print(f(4))
   a) 10    b) 24    c) 16    d) 12


9-SAVOL
   def f():
       s = ""
       for c in "abc":
           s += c
       return s
   print(f())
   a) abc   b) a b c c) cba   d) ['a','b','c']


10-SAVOL
   def f(n):
       i = 1
       while i <= n:
           i *= 2
       return i
   print(f(5))
   a) 4     b) 8     c) 5     d) 16


11-SAVOL
   def f(lst):
       s = 0
       for x in lst:
           s += x
       return s
   print(f([1, 2, 3, 4]))
   a) 10    b) 4     c) 24    d) 6


12-SAVOL
   def f(n):
       out = []
       for i in range(n):
           if i == 2:
               continue
           out.append(i)
       return out
   print(f(5))
   a) [0,1,2,3,4]  b) [0,1,3,4]  c) [2]  d) [0,1]


13-SAVOL
   def f(n):
       for i in range(n):
           if i == 3:
               break
       return i
   print(f(10))
   a) 10    b) 3     c) 2     d) 9


14-SAVOL
   def f(a, b):
       return a - b
   print(f(3, 7))
   a) 4     b) -4    c) 10    d) -10


15-SAVOL
   def f(x):
       y = x + 1
   print(f(5))
   a) 6     b) 5     c) None  d) Xato


16-SAVOL
   def f(n):
       c = 0
       while n > 0:
           n //= 2
           c += 1
       return c
   print(f(8))
   a) 3     b) 4     c) 8     d) 2


17-SAVOL
   def f(n):
       s = 0
       for i in range(1, n):
           for j in range(1, n):
               s += 1
       return s
   print(f(4))
   a) 9     b) 16    c) 12    d) 6


18-SAVOL
   def f(*args):
       return len(args)
   print(f(1, 2, 3, 4, 5))
   a) 1     b) 5     c) 0     d) Xato


19-SAVOL
   def f(n):
       return sum(range(n))
   print(f(5))
   a) 15    b) 10    c) 5     d) 0


20-SAVOL
   def f(n):
       res = 0
       i = 1
       while True:
           if i > n:
               break
           res += i
           i += 1
       return res
   print(f(5))
   a) 10    b) 15    c) cheksiz  d) 5


21-SAVOL
   x = 10
   def f():
       x = 5
       return x
   print(f(), x)
   a) 5 5   b) 5 10  c) 10 10 d) 10 5


22-SAVOL
   def f(n):
       c = 0
       for i in range(n):
           if i % 3 == 0:
               c += 1
       return c
   print(f(10))
   a) 3     b) 4     c) 5     d) 10


23-SAVOL
   def f(s):
       c = 0
       for ch in s:
           if ch == 'a':
               c += 1
       return c
   print(f("banana"))
   a) 2     b) 3     c) 1     d) 6


24-SAVOL
   def f(n):
       out = []
       i = n
       while i > 0:
           out.append(i)
           i -= 1
       return out
   print(f(3))
   a) [1,2,3]  b) [3,2,1]  c) [0,1,2]  d) [3,2,1,0]


25-SAVOL
   def f(n):
       return [i * i for i in range(1, n + 1)]
   print(f(4))
   a) [1,2,3,4]  b) [1,4,9,16]  c) [0,1,4,9]  d) [2,4,6,8]


26-SAVOL
   def f(a, b, c):
       return a + b + c
   print(f(1, 2, 3))
   a) 6     b) 123   c) 5     d) Xato


27-SAVOL
   def f(n):
       t = 0
       for i in range(1, n + 1):
           if i % 2 == 0:
               continue
           t += i
       return t
   print(f(6))
   a) 9     b) 12    c) 21    d) 6


28-SAVOL
   def f(n):
       count = 0
       while n != 1:
           if n % 2 == 0:
               n //= 2
           else:
               n = 3 * n + 1
           count += 1
       return count
   print(f(6))
   a) 6     b) 8     c) 5     d) 9


29-SAVOL
   def f(lst):
       m = lst[0]
       for x in lst:
           if x > m:
               m = x
       return m
   print(f([3, 7, 2, 9, 4]))
   a) 7     b) 9     c) 3     d) 4


30-SAVOL
   def f(n):
       s = 0
       for i in range(n):
           for j in range(n):
               if i == j:
                   s += 1
       return s
   print(f(4))
   a) 16    b) 4     c) 8     d) 12
