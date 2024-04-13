Currently implementing:


#### Array args
```ts
function callWithNum(b: number) {}
function callWithArray(a: number[]) {}
function callWithArrays(...args: number[][]) {}

callWithNum(1)
callWithNum([1])

callWithArray(1)
callWithArray([1]);

callWithArrays(1, 2, 3);
callWithArray([1], [2], [3]);
```

- Argument of type number is not assignable to parameter of type number[]
- Argument of type number is not assignable to parameter of type number[]

