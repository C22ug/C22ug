#Leap year

1234 2

5

6

7

8

year % 4 == 0 &

year% 100 !: 0 /

year% 400 == 0

9 def isLeap Year (year):

10 v

if (year % 4 == 0 and year % 100 != 0) or year% 400 == 0:

11

return True

12 v

13

14

15

16

else:

return False

year = 2014

17 if isLeapYear (year):

18 print(') is a leap year.'.format(year))

19 else:

20 print(') is not a leap year..format(year))
