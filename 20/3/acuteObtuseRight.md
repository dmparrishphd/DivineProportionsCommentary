# Alternative Definitions of Acute, Obtuse, Right

Define `A1`, `A2`, `A3` to be distinct points.

Define `Q3 = Q(A1, A2`), `Q2 = Q(A1, A3)`, `Q3 = Q(A2, A3)`

Define `S1 = sector(A2, A1, A3)`

Wildberger has

if `Q3 + Q2 >= Q1` then `S1` is acute type

if `Q3 + Q2 <= Q1` then `S1` is obtuse type

if `S1` is acute and obtuse 

We might instead define "acute," "obtuse," and "right" (distinguishing "right" from both "acute" and "obtuse") as follows:

    let k = compar(Q1, Q2 + Q3)
    
    S1 is acute  type, k = -1
    S1 is right  type, k =  0
    S1 is obtuse type, k = +1

# Signed Cross

Recall the Cross Law (p10, S1.2):

    (Q1 + Q2 - Q3) ^2 = 4 Q1 Q2 c3
    
Equivalently,

    (Q3 + Q2 - Q1) ^2 = 4 Q3 Q2 c1

or, as the Cross Law is defined for Q > 0:

    c1 = (Q3 + Q2 - Q1) ^2 / (4 Q3 Q2)

Rather than writing "acute spread" or "obtuse spread," we might define the "signed cross:"

For three numbers; Q1, Q2, Q3; 0 < Q3, 0 < Q2, 0 <= Q1

    c3^{+/-} = -k (Q3 + Q2 - Q1) ^2 / (4 Q3 Q2)

where `k = compar(Q1, Q2 + Q3)`

Thus, rather than encoding the "type" of sector as, e.g., the text "(ac)" or "(ob)", that information is encoded in the sign of the signed cross.

The definition of the signed cross allows for at least two special cases beyond the definition of cross:

## Special Case: Q1 = 0, Q2 = Q3

Suppose `Q1 = 0, Q2 = Q3 = Q`.
This is equivalent to the case where A2 and A3 are coincident, and A1 is distinct from A2 and A3.

    c3^{+/-} = (Q + Q) ^2 / (4 Q Q) = (2 Q) ^ 2 / ( 4 Q Q ) = 1
    
## Special Case: Q2 = Q3 = Q, Q1 = 4Q

Suppose `Q2 = Q3 = Q, Q1 = 4Q`.
This is equivalent to the case where A1 is at the midpoint between A2 and A3.

    c3^{+/-} = - (Q + Q - 4Q) ^2 / (4 Q Q) = - (-2 Q) ^ 2 / ( 4 Q Q ) = -1
