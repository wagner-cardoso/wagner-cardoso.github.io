---
title: "Gráfico de funções"
date: 2024-10-12
description: "EJAEM - Gráfico de funções."
cover: "thumb-geometry.jpg"
tags: ["matemática", "EJAEM"]
---

Este artigo oferece um tutorial de como elaborar um gráfico de uma função

{{< alert "twitter" >}}
Não esqueça de me [seguir](https://twitter.com/jpanther) no Twitter.
{{< /alert >}}

{{< icon "check" >}}


{{< button href="/" target="_self" >}}
Enviar
{{< /button >}}

## Grafico de exemplo

{{< chart >}}
type: 'bar',
data: {
  labels: ['Tomato', 'Blueberry', 'Banana', 'Lime', 'Orange'],
  datasets: [{
    label: '# of votes',
    data: [12, 19, 3, 5, 3],
  }]
}
{{< /chart >}}

{{< profile align="start" >}}

## 
Gráfico da função do 1o grau

{{< chart >}}
type: 'line',
data: {
  labels: ['-1', '2', '3', '4', '5', '6', '7'],
  datasets: [{
    label: 'Função do 1o grau',
    data: [0, 5, 10, 15, 20, 25, 30],
    tension: 0.2
  }]
}
{{< /chart >}}
