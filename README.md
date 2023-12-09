# ASIGNMENT-MM-231
We consider these cases to cover the problem.
+ Case1: If the firm is a thriving business:
  Input:
    b = 1 2 3 4 5
    l = 10 20 30 40 50 60 70 80 90
    q = 100 200 300 400 500 600 700 800 900
    s = 0 1 2 3 4
    A1j = 4 5 4 6 3
    A2j = 6 3 5 6 3
    A3j = 5 7 8 3 5
    A4j = 3 5 7 8 2
    A5j = 6 7 8 3 4
    A6j = 5 7 3 6 8
    A7j = 3 4 7 2 6
    A8j = 7 4 3 7 3
  Output:
    > Optimal Result:  -13122.5
    > Parts Ordered
        j  level  marginal  lower  upper  scale
    0  j1  198.0       1.0    0.0    inf    1.0
    1  j2  216.0       2.0    0.0    inf    1.0
    2  j3  243.0       3.0    0.0    inf    1.0
    3  j4  210.0       4.0    0.0    inf    1.0
    4  j5  157.0       5.0    0.0    inf    1.0
    ---------Scenerio 1-----------------
    - First demand
        i  value
    0  i1    6.0
    1  i2    3.0
    2  i3    4.0
    3  i4    7.0
    4  i5    8.0
    5  i6    2.0
    6  i7    5.0
    7  i8    6.0
    - The number of units produced
        i  level  marginal  lower  upper  scale
    0  i1    6.0     -45.0    0.0    inf    1.0
    1  i2    3.0     -90.0    0.0    inf    1.0
    2  i3    4.0    -135.0    0.0    inf    1.0
    3  i4    7.0    -180.0    0.0    inf    1.0
    4  i5    8.0    -225.0    0.0    inf    1.0
    5  i6    2.0    -270.0    0.0    inf    1.0
    6  i7    5.0    -315.0    0.0    inf    1.0
    7  i8    6.0    -360.0    0.0    inf    1.0
    ---------Scenerio 2-----------------
    - Second demand
        i  value
    0  i1    2.0
    1  i2    6.0
    2  i3    3.0
    3  i4    5.0
    4  i5    5.0
    5  i6    4.0
    6  i7    4.0
    7  i8    6.0
    - The number of units produced
        i  level  marginal  lower  upper  scale
    0  i1    2.0     -45.0    0.0    inf    1.0
    1  i2    6.0     -90.0    0.0    inf    1.0
    2  i3    3.0    -135.0    0.0    inf    1.0
    3  i4    5.0    -180.0    0.0    inf    1.0
    4  i5    5.0    -225.0    0.0    inf    1.0
    5  i6    4.0    -270.0    0.0    inf    1.0
    6  i7    4.0    -315.0    0.0    inf    1.0
    7  i8    6.0    -360.0    0.0    inf    1.0
 Esily we see that our Z is exactly same as demand vector D. Why this happend?
+ Case2
  Input:
  b=9 8 11 6 7 
  l=23 23 17 29 14 16 28 17
  q=270 235 340 200 110 293 174 230
  s=8 4 9 3 4 
  A1j=1 9 6 4 3 
  A2j=2 3 9 0 5 
  A3j=10 6 10 8 1 
  A4j=6 1 2 7 4 
  A5j=3 3 1 1 6 
  A6j=9 2 7 7 3
  A7j=1 5 2 9 3 
  A8j=3 5 7 6 5
  Output:
    > Optimal Result:  -914.7843137254902
    > Parts Ordered
        j       level  marginal  lower  upper  scale
    0  j1  170.000000       0.0    0.0    inf    1.0
    1  j2  117.000000       0.0    0.0    inf    1.0
    2  j3  195.039216       0.0    0.0    inf    1.0
    3  j4  159.000000       0.0    0.0    inf    1.0
    4  j5   98.000000       0.0    0.0    inf    1.0
    ---------Scenerio 1-----------------
    - First demand
        i  value
    0  i1    5.0
    1  i2    6.0
    2  i3    6.0
    3  i4    8.0
    4  i5    4.0
    5  i6    5.0
    6  i7    5.0
    7  i8    3.0
    - The number of units produced
        i  level      marginal  lower  upper  scale
    0  i1    5.0  0.000000e+00    0.0    inf    1.0
    1  i2    6.0  0.000000e+00    0.0    inf    1.0
    2  i3    6.0  0.000000e+00    0.0    inf    1.0
    3  i4    8.0  0.000000e+00    0.0    inf    1.0
    4  i5    0.0  1.400000e+01    0.0    inf    1.0
    5  i6    5.0  0.000000e+00    0.0    inf    1.0
    6  i7    0.0  1.776357e-15    0.0    inf    1.0
    7  i8    0.0  5.980392e-01    0.0    inf    1.0
    ---------Scenerio 2-----------------
    - Second demand
        i  value
    0  i1    4.0
    1  i2    6.0
    2  i3    6.0
    3  i4    6.0
    4  i5    4.0
    5  i6    6.0
    6  i7    3.0
    7  i8    3.0
    - The number of units produced
        i     level  marginal  lower  upper  scale
    0  i1  4.000000  0.000000    0.0    inf    1.0
    1  i2  6.000000  0.000000    0.0    inf    1.0
    2  i3  6.000000  0.000000    0.0    inf    1.0
    3  i4  6.000000  0.000000    0.0    inf    1.0
    4  i5  0.764706  0.000000    0.0    inf    1.0
    5  i6  6.000000  0.000000    0.0    inf    1.0
    6  i7  1.137255  0.000000    0.0    inf    1.0
    7  i8  0.000000  1.401961    0.0    inf    1.0

  
  
