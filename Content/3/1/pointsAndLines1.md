# Lines

## Notation

Herein, we prefer to denote a line

    (c, a, b)
    
(We prefer to place the terms in ascending order, i.e., zero-order term first, first order terms second.)

We prefer to write the equation of a line similarly:

    c + a * x + b * y = 0
    
## Evaluating a Point with Respect to a Line

We might choose to evaluate the expression `c + a * x + b * y` for a given line `(c, a, b)` and point `(x, y)`.

We call this _evaluating a point with respect to a line_.
    
## Definition of _pitch_

The _pitch_ of line `(c, a, b)` is `(a, b)`.

Pitch is not quite the same as _slope_, since `(0, b)` is a well-defined pitch, but slope `b/0` is undefined.

## Definition of _scale_ (of a line)

The _scale_ of a line `(c, a, b)` is `a * a + b * b`.

    scl((c, a, b)) = a * a + b * b

This quantity appears in DP3.4 (Theorem 8, Foot of an altitude), DP4.1 (Theorem 13, Reflection of a point in a line), DP5.4 (Theorem 25, Quadrance to a line), DP6.1 (Definition of spread), and perhaps elsewhere.
