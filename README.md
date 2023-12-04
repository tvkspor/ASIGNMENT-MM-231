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

  
  
