# Determinant of Two Points

We might define the _determinant of two points_ `(x1, y1)` and `(x2, y2)` to be the number `x1 * y2 - x2 * y1`.

We might write `det(p, q)`, where `p` and `q` are points.

# Definition of `del`

Given an ordered pair of numbers `(a, b)`, `del((a, b)) = b - a`.

# Line Though Two Points

Given two distinct points `p = (x1, y1), q = (x2, y2)` and
two ordered pairs `X = (x1, x2), Y = (y1, y2)`,
we might write the line through two points as `(det(p, q), del(Y), del(X))` or
`det(p, q) + x * del(Y) + y * del(X) = 0`.
