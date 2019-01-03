#[Variables scope](https://github.com/bachdx2812/wesbos-learning/blob/master/es6.io/01-new-variables/var-let-const.html)
The `var` variable is `scoped` to the `function`
While `let` & `const` is `scoped` to the `block`

#[Variable mutatation](https://github.com/bachdx2812/wesbos-learning/blob/master/es6.io/01-new-variables/let-const.html)
The `const` variable cannot be reassign for recreate
but the attributes of `const` object still can be changed

#[Replacing the IFFE](https://github.com/bachdx2812/wesbos-learning/blob/master/es6.io/01-new-variables/let-const-real-life.html)
The `var` will accidentally change the window
`name` variable which possiblely being used
in another third-party libraries which is not good

#[Temporal Dead Zone & When to use `var`](https://github.com/bachdx2812/wesbos-learning/blob/master/es6.io/01-new-variables/temporal-dead-zone.html)
- `var` variable can be access before it defined while `const` & `let` cant

- When to use `var`
* use `const` by default
* only use `let` if rebinding is needed
* (var shouldn't be used in ES6)
