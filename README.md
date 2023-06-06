```
const s1 = [[3, 3], [0, 0], [6, 6]]
const s2 = [[2, 2], [4, 4], [0, 0], [4, 4], [0, 0], [0, 0], [5, 5], [2, 2]]

const res = subsequenceDTW(s1, s2)

console.log(res)
```

output

```
{
  optimalPath: [ [ 0, 3 ], [ 1, 4 ], [ 1, 5 ], [ 2, 6 ] ],
  aStar: 3,
  bStar: 6,
  optimalSubsequence: [ [ 4, 4 ], [ 0, 0 ], [ 0, 0 ], [ 5, 5 ] ],
  accumulatedCost: 2.8284271247461903
}
```