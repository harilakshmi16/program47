sum=0
number=int(input("enter a integer:"))
while(number!=0):
digit=number%10
sum=sum+digit
number=number//10
print("sum of digitd is:",sum)
Output:
enter a integer:46789
sum of digitd is: 34
Pgm 65:
for i in range(10,50):
if(i%3==0):
print(i)
Output:
12
15
18
21
24
27
30
33
36
39
42
45
48
