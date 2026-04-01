# Math Equations (LaTeX / KaTeX)

GitHub supports LaTeX-style math rendering using `$` for inline and `$$` for block equations.

---

## Inline Math

Wrap an expression in single `$` signs:

```markdown
The quadratic formula is $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$.
```

**Rendered:**

The quadratic formula is $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$.

---

## Block (Display) Math

Wrap in `$$` on its own lines:

```markdown
$$
E = mc^2
$$
```

$$
E = mc^2
$$

---

## More Examples

**Sum notation:**

$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

**Integral:**

$$
\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$

**Matrix:**

$$
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
\begin{pmatrix}
x \\
y
\end{pmatrix}
=
\begin{pmatrix}
ax + by \\
cx + dy
\end{pmatrix}
$$

---

## Common LaTeX Symbols

| Symbol | Code |
| :----- | :--- |
| $\alpha, \beta, \gamma$ | `\alpha`, `\beta`, `\gamma` |
| $\pi$ | `\pi` |
| $\infty$ | `\infty` |
| $\leq, \geq, \neq$ | `\leq`, `\geq`, `\neq` |
| $\sqrt{x}$ | `\sqrt{x}` |
| $\frac{a}{b}$ | `\frac{a}{b}` |
| $x^2$ | `x^2` |
| $x_i$ | `x_i` |

> ✅ Supported natively on GitHub. For other renderers, check if KaTeX or MathJax is enabled.
