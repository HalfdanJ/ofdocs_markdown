Divides 'x' by 'vec.x', divides 'y' by 'vec.y', and divides 'z' by 'vec.z'.

```cpp
ofVec3f v1 = ofVec3f(40, 20, 10); 
ofVec3f v2 = ofVec3f(2, 4, 10);
v1 *= v2; // v1 is now (20, 5, 1)
```

Useful for scaling a 3D point by a non-uniform scale.
