# Square_root_python by importing math function
import math 
c = 50
h = 30
value = []
lst = [ x for x in input('Enter the values by seperating with \',\' ').split(',') ]
for d in lst :
    value.append(str(int(round(math.sqrt((2*c*int(d))/h)))))
print(','.join(value))
