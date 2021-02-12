# Relating to "Quadrance to a Line"

The quadrance from point `(x, y)` to line _h_ could be written `sqr(a * x + b * y + c) / scl(h)`.

For the special case where `(x, y) = (0, 0)`, the quadrance is `sqr(c) / scl(h)`.

## Quadrance Between Parallel Lines

The quadrance between parallel lines is equal to the quadrance from a point on one of the lines to the other line.

A point on line `(d, a, b)` satisfies `d + a * x + b * y = 0` or `-d - a * x = b * y`.

Given two lines `(c, a, b)` and `(d, a, b)`, i.e., parallel lines,
the quadrance between them is the quadrance between a point on `(d, a, b)` and line `(c, a, b)`, or

    sqr(c - d) / scl(h)
    
## Swath of a Line

If the quadrance from a point `(x, y)` to a line _h_, `(c, a, b)`, is less than some number _K_, i.e.,

    sqr(a * x + b * y + c) / scl(h) < K
    
We might say that the point `(x, y)` is within the _swath of quadrance K_ of line `(a, b, c)`.

Points with quadrance to line _h_ less than the quadrance between lines `(c +/- w, a, b)` and _h_ are within the swath of quadrance `sqr(w)/scl(h)`.
