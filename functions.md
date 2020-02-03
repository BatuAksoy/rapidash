# Functions

<style>
    h2  {
        text-transform: capitalize;
    }
</style>

<p class="tip">
All examples assume that you required Rapidash
</p>

```js
const r = require('rapidashjs');
```

___
## max

Computes the maximum value of array. If array is empty or falsey, undefined is returned.

### Examples
```js
r.max([1,2,3]) // 3
```
 ```js
r.max() // undefined
```
 ```js
r.max([]) // undefined
```



> max function by <a href="https://github.com/acanguven">acanguven</a>  

max can perform 62,106,436 ops/sec with benchmark data below.

```js
r.max([1,2,3,4,5,6,1,3,5,7,2,8,9,32,4,8,4,4,5,7,56,1,5,8,4,4,6]);
```


___
## factorial

Calculates the factorial of a number.

### Examples
```js
r.factorial(6) // 720
```



> factorial function by <a href="https://github.com/acanguven">acanguven</a>  

factorial can perform 9,284,260 ops/sec with benchmark data below.

```js
r.factorial(14);
```


___
## average

Returns the average of two or more numbers.

### Examples
```js
r.average() // NaN
```
 ```js
r.average(1) // 1
```
 ```js
r.average(1,2) // 1.5
```
 ```js
r.average(1,2,3) // 2
```
 ```js
r.average(1,2,3,0) // 1.5
```



> average function by <a href="https://github.com/acanguven">acanguven</a>  

average can perform 42,538,449 ops/sec with benchmark data below.

```js
r.average(1,2,3,0,73,53,23,54,23,74,3,42);
```


___
## primes

Generates primes up to a given number.

### Examples
```js
r.primes(10) // [2,3,5,7]
```



> primes function by <a href="https://github.com/acanguven">acanguven</a>  

primes can perform 30,793 ops/sec with benchmark data below.

```js
r.primes(150);
```


