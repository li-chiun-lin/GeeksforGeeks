# Easy

Consider a long alley with a $N$ number of doors on one side. All the doors are closed initially. You move to and from in the alley changing the states of the doors as follows: you open a door that is already closed and you close a door that is already opened.

You start at one end go on altering the state of the doors till you reach the other end and then you come back and start altering the states of the doors again.

- In the first go, you alter the states of doors numbered $1, 2, 3, ... , n$.
- In the second go, you alter the states of doors numbered $2, 4, 6, ..., n$.
- In the third go, you alter the states of doors numbered $3, 6, 9, ..., n$
- You continue this till the $N$-th go in which you alter the state of the door numbered $N$.

You have to find the number of open doors at the end of the procedure.

```cpp
class Solution {
  public:
    int noOfOpenDoors(long long N) {
        return sqrt(N);
    }
};
```
