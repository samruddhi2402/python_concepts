# Python `for-else` Statement

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

- The loop starts from `0` and prints `0`, `1`, and `2`.
- When `i` becomes `3`, the `break` statement stops the loop.
- Because the loop ends with `break`, the `else` block is not executed.

## Key Takeaway

The `else` block in a `for` loop runs **only if the loop completes without a `break` statement**.

> This is a simple-looking Python feature that can be confusing for beginners, so I documented it as part of my learning journey.
