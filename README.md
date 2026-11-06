# GTU Maths 2 3110015 Green's theorem checker

Green's theorem came in all 9 official GTU Maths 2 (3110015) papers in GTU Hero's count (Summer 2022 to Summer 2026), and sat in Q.1(c) in 8 of those 9. Q.1 has no choice. Jab (∂Q/∂x − ∂P/∂y) constant ho, double integral = constant × area.

Live page: https://princeadvant.github.io/gtu-green-theorem-checker/

## Formulas

- ∮ P dx + Q dy = ∬ (∂Q/∂x − ∂P/∂y) dA
- If integrand is constant C: value = C × area(R)
- For P=−y, Q=x on rectangle [0,a]×[0,b]: value = 2ab

## Test

`node test.js` checks the formulas against hand-worked values and prints `All checks passed`.

## Tips

- Confirm anticlockwise orientation on the outer boundary.
- Compute ∂Q/∂x − ∂P/∂y before integrating. Often it is a constant.
- Also revise div/curl checks: they were in all 9 papers for 3 to 4 marks.

Repeat counts and old papers: [GTU Maths 2 PYQs and repeated sums on GTU Hero](https://gtuhero.com/blogs/gtu-maths-2-papers-pyqs-repeated-sums) (GTU Hero is my project).
