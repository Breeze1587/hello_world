# hello_world



+++++++++++++++++++++++++++++

A list practice in Python 

+++++++++++++++++++++++++++++

""
sort
reverse
"""
import random

numbers = []
for i in range(8):
    ran = random.randint(1, 100)
    numbers.append(ran)

numbers.sort()
print(numbers)

num = int(input('请输入一个1-100的数：'))

for i in numbers:
    if num <= i:
        numbers.insert(numbers.index(i), num)
        break

else:
    numbers.append(num)

print(numbers)


