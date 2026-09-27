# Using Limits to Describe End Behavior

For a rational function

$$
R(x)=\frac{N(x)}{D(x)},
$$

end behavior describes what the graph does far to the left and far to the right. In limit notation, we write $x\to-\infty$ for moving left and $x\to\infty$ for moving right.

## Read the Graph

Look at each end of the curve and ask: **As $x$ keeps moving in this direction, what value does $R(x)$ get closer to?** The graph may approach a horizontal or slant asymptote. The curve does not have to touch the asymptote for its values to get closer to it.

If the graph approaches the horizontal line $y=L$ at both ends, write

$$
\lim_{x\to-\infty}R(x)=L
\qquad\text{and}\qquad
\lim_{x\to\infty}R(x)=L.
$$

For example, if both ends approach $y=2$, then

$$
\lim_{x\to-\infty}R(x)=2
\qquad\text{and}\qquad
\lim_{x\to\infty}R(x)=2.
$$

The two ends do not always approach the same value. Read them separately. If the left end rises without bound and the right end falls without bound, write

$$
\lim_{x\to-\infty}R(x)=\infty
\qquad\text{and}\qquad
\lim_{x\to\infty}R(x)=-\infty.
$$

## If There Is a Slant Asymptote

If an end of the graph follows a slant line $y=mx+b$, describe that end by saying the **difference** between the function and the line approaches $0$:

$$
\lim_{x\to\infty}\bigl(R(x)-(mx+b)\bigr)=0.
$$

Use $x\to-\infty$ instead when describing the left end. This says the graph gets closer to the line; it does not say $R(x)$ approaches one fixed number.

## Quick Check

- Which end am I describing: $x\to-\infty$ or $x\to\infty$?
- What value or line does that end approach?
- Does my limit statement match that direction and behavior?
