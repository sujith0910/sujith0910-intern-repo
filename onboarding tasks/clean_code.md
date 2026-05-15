# Naming Variables & Functions

## Best Practices

Good variable and function names should be clear, meaningful, and easy to understand. A name should explain what the value stores or what the function does without needing extra comments. For example, `totalPrice` is better than `tp`, and `calculateDiscount()` is better than `calc()`.

Variable names should usually describe data, while function names should describe actions. Using names like `userName`, `orderTotal`, `isLoggedIn`, and `getCustomerDetails()` makes the code easier to read.

---

## Example of Unclear Code

```javascript
function c(a, b) {
  let x = a * b;
  return x;
}
```

In this example, the function name `c` and variables `a`, `b`, and `x` are unclear. It is difficult to understand what the function is doing without reading the full logic.

---

## Refactored Code

```javascript
function calculateTotalPrice(price, quantity) {
  let totalPrice = price * quantity;
  return totalPrice;
}
```

After refactoring, the function name and variable names clearly explain the purpose of the code. It is now easier to understand that the function calculates the total price based on price and quantity.

---

## Reflection

A good variable or function name should be simple, descriptive, and related to its purpose. It should make the code easier to understand without needing many comments.

Poorly named variables can make code confusing and harder to maintain. Other developers may need extra time to understand what the code is doing, and this can increase the chance of mistakes during debugging or future changes.

Refactoring improved the readability because the new names clearly explain the meaning of each value and the purpose of the function. The code became easier to follow, even for someone reading it for the first time.