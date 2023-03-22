---
id: 5900f3f51000cf542c50ff08
title: 'Завдання 137: Золоті самородки Фібоначчі'
challengeType: 1
forumTopicId: 301765
dashedName: problem-137-fibonacci-golden-nuggets
---

# --description--

Розглянемо нескінченний поліноміальний ряд $A_{F}(x) = xF_1 + x^2F_2 + x^3F_3 + \ldots$, де $F_k$ — $k$й член послідовності Фібоначчі: $1, 2, 3, 5, 8, \ldots$; тобто, $F_k = F_{k - 1} + F_{k − 2}, F_1 = 1$ та $F_2 = 1$.

Нас цікавлять значення $x$, для яких $A_{F}(x)$ є додатнім цілим числом.

Дивовижно,

$$\begin{align} A_F(\frac{1}{2}) & = (\frac{1}{2}) × 1 + {(\frac{1}{2})}^2 × 1 + {(\frac{1}{2})}^3 × 2 + {(\frac{1}{2})}^4 × 3 + {(\frac{1}{2})}^5 × 5 + \cdots \\\\
                 & = \frac{1}{2} + \frac{1}{4} + \frac{2}{8} + \frac{3}{16} + \frac{5}{32} + \cdots \\\\ & = 2 \end{align}$$

Відповідні значення $x$ для перших п'яти натуральних чисел наведено нижче.

| $x$                         | $A_F(x)$ |
| --------------------------- | -------- |
| $\sqrt{2} - 1$             | $1$      |
| $\frac{1}{2}$              | $2$      |
| $\frac{\sqrt{13} − 2}{3}$ | $3$      |
| $\frac{\sqrt{89} − 5}{8}$ | $4$      |
| $\frac{\sqrt{34} − 3}{5}$ | $5$      |

Назвемо $A_F(x)$ золотим самородком, якщо $x$ раціональне, оскільки вони трапляються дедалі рідше; наприклад, 10-й золотий самородок - 74049690.

Знайдіть 15-й золотий самородок.

# --hints--

`goldenNugget()` має повернути число `1120149658760`.

```js
assert.strictEqual(goldenNugget(), 1120149658760);
```

# --seed--

## --seed-contents--

```js
function goldenNugget() {

  return true;
}

goldenNugget();
```

# --solutions--

```js
// solution required
```