# 2667. Create Hello World Function

Write a function createHelloWorld. It should return a new function that always returns "Hello World".

```js
/**
 * @return {Function}
 */
var createHelloWorld = function() {
    
    return function(...args) {
        return "Hello World";
    }
};

/**
 * const f = createHelloWorld();
 * f(); // "Hello World"
 */
 ```

### 2620. Counter

Given an integer n, return a counter function. This counter function initially returns n and then returns 1 more than the previous value every subsequent time it is called (n, n + 1, n + 2, etc).

```js
/**
 * @param {number} n
 * @return {Function} counter
 */
var createCounter = function(n) {
    var num=n;
    return function() {
        return num++;
    };
};

/** 
 * const counter = createCounter(10)
 * counter() // 10
 * counter() // 11
 * counter() // 12
 */
 ```
