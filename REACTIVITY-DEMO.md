# Vanilla JavaScript Reactivity Demo

This directory contains a demonstration of building reactive HTML pages using vanilla JavaScript, without any frameworks.

## About

This demo implements the concepts from the article "Simplest Reactivity in Web Pages Using Vanilla JavaScript", showcasing how to build a reactive system from scratch.

## File

- `reactivity-demo.html` - A standalone HTML page with embedded JavaScript demonstrating reactivity concepts

## How to View

Simply open `reactivity-demo.html` in any modern web browser. No build process or server required!

You can also serve it using any HTTP server:

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx http-server
```

Then navigate to `http://localhost:8080/reactivity-demo.html`

## Features Demonstrated

### 1. Reactive Values
Core building blocks that track changes and notify subscribers:
- Create reactive values with initial state
- Subscribe to changes
- Update values and trigger subscriptions automatically

### 2. Reactive Expressions
Computed values that automatically update when dependencies change:
- Simple arithmetic operations (addition)
- Complex calculations (shopping cart with subtotal, tax, total)
- Text transformations (uppercase, lowercase, character count, reverse)

### 3. Multiple Subscribers
Single reactive values can have multiple subscribers, each reacting independently to changes.

## Code Structure

The demo includes two main functions:

- **`reactiveValue(initialValue)`** - Creates a reactive value with get/set/subscribe methods
- **`reactiveExpression(fn, ...dependencies)`** - Creates a computed reactive value based on other reactive values

## Interactive Demos

1. **Demo 1**: Simple reactive value with multiple outputs
2. **Demo 2**: Reactive expression for addition
3. **Demo 3**: Complex reactive expressions (shopping cart calculator)
4. **Demo 4**: Text transformations

Try typing in the input fields to see the reactive updates in action!
