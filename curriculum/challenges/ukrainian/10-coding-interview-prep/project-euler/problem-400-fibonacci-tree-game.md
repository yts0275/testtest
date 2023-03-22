---
id: 5900f4fe1000cf542c510010
title: 'Завдання 400: Гра з деревом Фібоначчі'
challengeType: 1
forumTopicId: 302067
dashedName: problem-400-fibonacci-tree-game
---

# --description--

Дерево Фібоначчі - це двійкове дерево, рекурсивно визначене як:

- $T(0)$ - це порожнє дерево.
- $T(1)$ - це двійкове дерево лише з одним вузлом.
- $T(k)$ складається з кореневого вузла, який має $T(k - 1)$ і $T(k - 2)$ як дочірній.

Два гравці грають на вибування на такому дереві. Під час кожного ходу гравець вибирає вузол і видаляє цей вузол разом із залежним деревом, що прив'язане до цього вузла. Гравець, якого змушують взяти кореневий вузол усього дерева, програє.

Ось виграшні ходи першого гравця на першому ході за $T(k)$ від $k = 1$ до $k = 6$.

<img class="img-responsive center-block" alt="виграшні ходи першого гравця, на першому ході за k = 1 до k = 6" src="https://cdn.freecodecamp.org/curriculum/project-euler/fibonacci-tree-game.png" style="background-color: white; padding: 10px;" />

Нехай $f(k)$ - це кількість виграшних ходів першого гравця (тобто ходів, для яких другий гравець не має стратегії виграшу) на першому ході гри, коли ця гра проводиться $T(k)$.

Наприклад, $f(5) = 1$ і $f(10) = 17$.

Знайдіть $f(10000)$. Вкажіть останні 18 цифр своєї відповіді.

# --hints--

`fibonacciTreeGame()` повинен повернути `438505383468410600`.

```js
assert.strictEqual(fibonacciTreeGame(), 438505383468410600);
```

# --seed--

## --seed-contents--

```js
function fibonacciTreeGame() {

  return true;
}

fibonacciTreeGame();
```

# --solutions--

```js
// solution required
```