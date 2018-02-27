# Even-Fibonacci-numbers

a = 0
b = 1
bound = 4000000
Sum = 0
while c < bound :
    c = a + b
    a = b
    b = c
if c % 2 == 0 :
    Sum += c
print (Sum)
