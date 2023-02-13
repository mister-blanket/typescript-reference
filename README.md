# typescript-reference

## Interface
Declare types for a class
``` js
    interface User {
        name: string;
        id: number;
    }

    const user: User = {
        name: "Hayes",
        id: 0,
    };
```

## Unions
Used to specify specific allowed values
`type MyBool = true | false;`
``` js
    type WindowStates = "open" | "closed" | "minimized";
    type LockStates = "locked" | "unlocked";
    type PositiveOddNumbersUnderTen = 1 | 3 | 5 | 7 | 9;
```

## Generics
Generics provide variables to types. A common example is an array. An array without generics could contain anything. An array with generics can describe the values that the array contains.
``` js
    type StringArray = Array<string>;
    type NumberArray = Array<number>;
    type ObjectWithNameArray = Array<{ name: string }>;
```