# Functions

Functions let us reuse code.

Here’s how a function looks:

```javascript
function name() {
  // code inside
}
```

To run the code inside the function, we call it by its name like this:

```javascript
name();
```

We can call it as many times as we want. This is how functions help us reuse code. Every time we call it, it runs the code inside the function:

```javascript
name();
name();
name();
```

# Return Statement

The `return` statement sends a value from the function back to where it was called.

```javascript
function name() {
  return 'siyam';
}

name();
```

The string `'siyam'` is returned to where the function was called, in this case `name();`.

**Note:** Any code written after the `return` will not run.

# Parameters

A parameter lets a function receive a value from outside.

```javascript
function name(nameInput) {
  console.log(nameInput);
}

name('siyam');
```

Here, `nameInput` is the parameter. When we call the function with `name('siyam');`, the value `'siyam'` is passed into `nameInput`.
