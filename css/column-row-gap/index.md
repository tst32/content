---
title: "`column-gap`, `row-gap`"
authors:
  - solarrust
keywords:
  - отступы между грид-ячейками
tags:
  - doka
---

## Кратко

Задаёт отступы между колонками и рядами в грид-раскладке.

## Пример

```css
.container {
  display: grid;
  grid-template-columns: 1fr 200px 1fr;
  grid-template-rows: repeat(3, 150px);
  /* Отступы между колонками */
  column-gap: 10px;
  /* Отступы между рядами */
  row-gap: 50px;
}
```

![Пример реализации свойств column-gap / row-gap](images/1.png)

## Как пишется

Указывайте одно значение размера в любых единицах измерения.

## Подсказки

💡 В инспекторе Firefox отступы заштриховываются, так их можно отличить от грид-элементов.

💡 Существуют старые аналоги этих свойств, которые могут пригодиться вам, если вы вынуждены поддерживать браузеры старше чем Chrome 68+, Safari 11.2 50+ и Opera 54+: `grid-column-gap` и `grid-row-gap`. Можно писать сперва старые свойства, а за ними новые. Чтобы наверняка.

<aside>

📝 Полный список свойств гридов можно посмотреть в [гайде по grid](/css/grid-guide/).

</aside>
