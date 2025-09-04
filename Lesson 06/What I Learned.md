# Booleans

Booleans have 2 values:

- `true`
- `false`

# Order of operations (precedence)

1. Parentheses `()`
2. Multiplication and division `* /`
3. Addition and subtraction `+ -`
4. Comparison operators (`>`, `<`, `>=`, `<=`, `===`, `!==`)
5. Logical operators (`&&`, `||`, `!`)

Note: operators on the same line share precedence and are evaluated left to right.

# Comparison operators

- `>` greater than
- `<` less than
- `>=` greater than or equal to
- `<=` less than or equal to
- `===` equal to (checks value and type)
- `!==` not equal (checks value and type)

# Logical operators

- `&&` and
- `||` or
- `!` not

# If statements

If statements let you write multiple blocks of code, then choose which block runs.

- `if` runs its block only when the condition is true or truthy
- `else if` checks another condition when the previous `if` or `else if` was false or falsy
- `else` runs when none of the previous conditions were true

Example:

```js
const age = 15;

if (age >= 18) {
  // runs if age is 18 or older
} else if (age >= 13) {
  // runs if age is 13 to 17
} else {
  // runs if age is under 13
}
```

- The condition goes inside the `()`
- The code to run goes inside the `{}`

# Falsy values

These values are considered falsy in JavaScript:

1. `false`
2. `0`
3. `''` (empty string)
4. `NaN`
5. `undefined`
6. `null`

Note: Any value not on this list is truthy.
