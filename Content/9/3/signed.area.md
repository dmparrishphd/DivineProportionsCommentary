Signed Area
===========

The signed area is expressed as one-half the determinant

    | x1 y1 1 |
    | x2 y2 1 |   =   x1 y2 - x2 y1 + x2 y3 - y3 y2 + x3 y1 - x1 y3
    | x3 y3 1 |

Translating the triangle does not affect its area.
Therefore, in order to compute the above determinant,
we could proceed as follows:
   
    | x1 y1 1       x1 y1 0 |       |    0         0         1 |
    | x2 y2 1   -   x1 y1 0 |   =   | x2 - x1   y2 - y1      1 |   = (x2 - x1) * (y3 - y1) - (y2 - y1) * (x3 - x1)
    | x3 y3 1       xy y1 0 |       | x3 - x1   y3 - y1      1 |

which is five subtractions and two multiplications instead of
five additions and subtractions and six multiplications
