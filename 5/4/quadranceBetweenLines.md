# Relating to "Quadrance to a Line"

The quadrance from point `(x, y)` to line _h_ could be written `sqr(a * x + b * y + c) / scl(h)`.

## Quadrance Between Parallel Lines

The quadrance between parallel lines is equal to the quadrance from a point on one of the lines to the other line.

A point on line `(d, a, b)` satisfies `d + a * x + b * y = 0` or `-d - a * x = b * y`.

Given two lines `(c, a, b)` and `(d, a, b)`, i.e., parallel lines,
the quadrance between them is the quadrance between a point on `(d, a, b)` and line `(c, a, b)`, or

    sqr(c - d) / scl(h)

