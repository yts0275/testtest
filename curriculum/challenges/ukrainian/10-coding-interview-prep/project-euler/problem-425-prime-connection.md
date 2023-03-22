---
id: 5900f5151000cf542c510028
title: 'Завдання 425: З’єднання простих чисел'
challengeType: 1
forumTopicId: 302095
dashedName: problem-425-prime-connection
---

# --description--

Два додатних числа $A$ та $B$ вважаються з’єднаними (позначаються "$A ↔ B$"), якщо виконується одна з цих умов:

1. $A$ та $B$ мають однакову довжину і відрізняються тільки однією цифрою; наприклад, $123 ↔ 173$.
2. Додавання однієї цифри зліва від $A$ (або $B$) утворює $B$ (або $A$); наприклад, $23 ≈ 223$ і $123 ≈ 23$.

Назвемо просте число $P$ родичем 2, якщо між 2 і $P$ існує ланцюжок зі з'єднаних простих чисел і жодне число в ланцюжку не перевищує $P$.

Наприклад, число 127 – родич 2. Один з можливих ланцюжків показаний нижче:

$$2 ↔ 3 ↔ 13 ↔ 113 ↔ 103 ↔ 107 ↔ 127$$

Однак 11 та 103 не є родичами 2.

Припустимо, $F(N)$ - сума простих чисел $≤ N$, які не є родичами 2. Можемо переконатися, що $F({10}^3) = 431$ та $F({10}^4) = 78\\,728$.

Знайдіть $F({10}^7)$.

# --hints--

`primeConnection()` має повернути `46479497324`.

```js
assert.strictEqual(primeConnection(), 46479497324);
```

# --seed--

## --seed-contents--

```js
function primeConnection() {

  return true;
}

primeConnection();
```

# --solutions--

```js
// solution required
```