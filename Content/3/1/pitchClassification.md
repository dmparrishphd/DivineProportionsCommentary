Classification of Pitch of a Line
=================================

_For a definition of pitch, see [Lines](./pointsAndLines1.md)._

Given a line `(c, a, b)`, `0 < a * a + b * b` with pitch `(a, b)`:

The pitch `(a, b)` may be classified according to:---

|       Condition | Classification |
| --------------: | :------------- |
|        `a == 0` | horizontal     |
|        `b == 0` | vertical       |
| `a * a < b * b` | gradual        |
| `b * b < a * a` | steep          |

|                              Condition | Classification |
| -------------------------------------: | :------------- |
| `a != 0`, `b != 0`, `sgn(a) == sgn(b)` | downward       |
| `a != 0`, `b != 0`, `sgn(a) != sgn(b)` | upward         |
