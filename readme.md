## Theorem:
Given a single string of length \( L \), it's possible to create exactly 6 non-overlapping circles in a hexagonal packing arrangement such that the entire string is used without any leftover.

### Definitions:
- \( L \): Length of the string.
- \( r \): Radius of each circle.
- \( C \): Circumference of each circle \( = 2\\pi r \).

## Proof:

1. **String Length & Circumference**: To use the entire string, each circle's circumference must be \( \\frac{L}{6} \).
   \[
   C = \\frac{L}{6}
   \]

2. **Radius Calculation**: The radius \( r \) of each circle is then:
   \[
   r = \\frac{C}{2\\pi} = \\frac{L}{12\\pi}
   \]

3. **Hexagonal Packing**: In a hexagonal arrangement, each circle touches exactly two other circles, but does not overlap with them. This arrangement satisfies the condition of non-overlapping circles.

4. **String Utilization**: In this arrangement, the string will traverse the perimeter of each of the 6 circles exactly once. Therefore, the entire string is used:
   \[
   6 \\times C = 6 \\times \\frac{L}{6} = L
   \]

5. **No Leftover**: Since \( 6 \\times C = L \), the entire length of the string is used, meeting the theorem's conditions.
