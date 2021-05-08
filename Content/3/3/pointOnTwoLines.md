Point on two lines
==================

Consider the matrix:

    c1   a1   b1
    
    c2   a2   b2
    
Define the matrices (which are submatrices of the above matrix):

            b1   c1              a1   c1              a1   b1
    A   =                B   =                C   =
            b2   c2              a2   c2              a2   b2
            
And define the determinants `DA = det(A)`, `DB = det(B)`, `DC = det(C)`

If `det(C) != 0` then we may write the point on the two lines `(c1, a1, b1)`, `(c2, a2, b2)` as
`(DA/DC , DB/DC)`.

See also "Point on two lines", in DP Section 3.3.
