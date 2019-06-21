# targel-21-06-20199

targe 21/06/2019
#1
def mySqr (x):
    return x**2
r1 = mySqr(6)
print(r1)
#2
def myMul (x ,y ):
    return x+y
r2 = myMul(8 ,5 )
print(r2)
#3
def myFactorial (x):
    atz = 1
    for n in range(2, x + 1):
        atz = atz * n
    return atz

r3= myFactorial (5)
print (r3)

#4
def myCheckEven (x):
    if x % 2==0:
        return True
    else:
        return False

r4 = myCheckEven (60)
print(r4)

#5
def myAverage (aList):
  average = sum(aList) / len(aList)
  return average

print(myAverage({3 , 8 , 6 , 78 }))
l1 = [9 ,100 ,23 ,5, 2]
average1 = myAverage(l1)
print(f'average of list {l1} is {average1}')

#6
def myConcat(s1 , s2):
    return s1+ ' ' + s2
Fname = "bugs"
Lname = "bunny"
print(myConcat(Fname , Lname))


