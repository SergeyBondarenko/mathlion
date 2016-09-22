<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->

# Function sinh

Calculate the hyperbolic sine of a value,
defined as `sinh(x) = 1/2 * (exp(x) - exp(-x))`.

For matrices, the function is evaluated element wise.


## Syntax

```js
sinh(x)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | number &#124; BigNumber &#124; Complex &#124; Unit &#124; Array &#124; Matrix | Function input

### Returns

Type | Description
---- | -----------
number &#124; BigNumber &#124; Complex &#124; Array &#124; Matrix | Hyperbolic sine of x


## Examples

```js
sinh(0.5);       // returns number 0.5210953054937474
```


## See also

[cosh](cosh.md),
[tanh](tanh.md)