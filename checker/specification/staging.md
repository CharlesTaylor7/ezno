Currently implementing:

> This file is for work-in-progress and can help separating features that are being implemented to regressions

> https://github.com/microsoft/TypeScript/blob/main/src/lib/es5.d.ts#L1581-L1605

#### never type

```ts
function loops(): never {
    while (true);
}

loops() satisfies string;

```

- expected string, found never

