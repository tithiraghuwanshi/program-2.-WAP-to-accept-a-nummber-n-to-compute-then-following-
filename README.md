# program-2.-WAP-to-accept-a-nummber-n-to-compute-then-following-
a. check if 'n' is prime or not
prime number
n=int(input('enter a number'))           # n=15
f=0

for i in range(2,n):
  if n%i==0:
    f=1
    print('NOT PRIME')
    break

if f==0:
  print('PRIME')
