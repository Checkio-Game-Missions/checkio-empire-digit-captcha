**Precondition:**

```python
matrix_rows == 5
5 <= matrix_columns < 30
all(all(x in (0, 1) for x in row) for row in matrix)
digit_width == 3
digits_space == 1
```

Each digit contains no more than one wrong pixel.
