# Python `for-else` Statement

This example demonstrates how the `else` block works with a `for` loop in Python.

## Code

```python
for i in range(5):
    if i == 3:
        break
    print(i)
else:
    print("stop")
```

## Output

```
0
1
2
```

## Explanation

- The loop starts with `i = 0` and prints `0`.
- Then `i = 1` and prints `1`.
- Next `i = 2` and prints `2`.
- When `i = 3`, the `break` statement is executed, which immediately terminates the loop.
- Since the loop was interrupted by `break`, the `else` block is **not executed**.

## Key Takeaway

The `else` block of a `for` loop executes only if the loop completes normally without encountering a `break` statement.

> Although `for-else` looks simple, it's a Python feature that many beginners misunderstand. This example helped me understand that the `else` block depends on whether the loop finishes naturally or exits with `break`.
