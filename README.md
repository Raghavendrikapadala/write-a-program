# write-a-program
def is_leap(year):
  leap=false
if year%400==0 :
    leap=True;
 elif year%4==0 and year%100!=0:
    leap=True;
return leap
year = int(raw_input())
print is_leap(year)
