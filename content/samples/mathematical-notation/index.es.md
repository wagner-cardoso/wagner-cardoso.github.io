---
title: Notación matemática
date: 2019-03-08
description: Una breve muestra de notación matemática en Congo.
tags: ["sample", "katex", "maths", "shortcodes"]
---

Una breve muestra de notación matemática en Congo.

<!--more-->

{{< katex >}}

Utilice la documentación en línea de [funciones TeX admitidas](https://katex.org/docs/supported.html) para conocer la sintaxis disponible.

## Notación en línea

La notación en línea se puede generar envolviendo la expresión en los delimitadores `\\(` y `\\)`.

**Ejemplo:**

```tex
% KaTeX notación en línea
Notación en línea: \\(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…\\)
```

Notación en línea: \\(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…\\)

## Notación en bloque

Alternativamente, la notación en bloque se puede generar usando delimitadores `$$`. Esto generará la expresión en su propio bloque HTML.

**Ejemplo:**

```tex
% KaTeX notación en bloque
$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$
```

$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$
