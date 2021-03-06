Perform a linear interpolation of this vector's position towards 'pnt' and return the interpolated vector without altering the original. 'p' controls the amount to move towards 'pnt'. 'p' is normally between 0 and 1 and where 0 means stay the original position and 1 means move all the way to 'pnt', but you can also have 'p' greater than 1 overshoot 'pnt', or less than 0 to move backwards away from 'pnt'.

```cpp
ofVec3f v1(0, 5, 0);
ofVec3f v2(10, 10, 20);
ofVec3f v3 = v1.getInterpolated(p2, 0.5); // v3 is (5, 7.5, 10)
ofVec3f v4 = v1.getInterpolated(p2, 0.8); // v4 is (8, 9, 16)
```
