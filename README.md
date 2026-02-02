year = int(input(&quot;Enter a year: &quot;))
if (year % 4) == 0:
if (year % 100) == 0:
if (year % 400) == 0:
print(year, &quot; is a leap year&quot;)

else:
print(year, &quot; is not a leap year&quot;)
else:
print(year, &quot; is a leap year&quot;)
else:
print(year, &quot; is not a leap year&quot;)
output
Enter a year: 2000
2000 is a leap year
