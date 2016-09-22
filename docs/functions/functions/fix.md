<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->

# Function fix

Round a value towards zero.
For matrices, the function is evaluated element wise.


## Syntax

```js
fix(x)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | number &#124; BigNumber &#124; Fraction &#124; Complex &#124; Array &#124; Matrix | Number to be rounded

### Returns

Type | Description
---- | -----------
number &#124; BigNumber &#124; Fraction &#124; Complex &#124; Array &#124; Matrix | Rounded value


## Examples

```js
fix(3.2);                // returns number 3
fix(3.8);                // returns number 3
fix(-4.2);               // returns number -4
fix(-4.7);               // returns number -4

var c = complex(3.2, -2.7);
fix(c);                  // returns Complex 3 - 2i

fix([3.2, 3.8, -4.7]);   // returns Array [3, 3, -4]
```


## See also

[ceil](ceil.md),
[floor](floor.md),
[round](round.md)