# Game of Fire

Rules:

```
1. x_ij empty  == (a)                ==>  tree

2. x_ij tree   == (p / lightning)    ==>  fire

3. x_ij tree   == (fire / neighbor)  ==>  fire

4. x_ij fire   ==                    ==>  empty

5. x_ij not triggered                ==>  same status
```

Example implementation with 2 matrices: now and then

```
1. zero out then
2. walk through now and populate then
3. copy then to now
```
