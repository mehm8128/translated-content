---
title: grayscale()
slug: Web/CSS/filter-function/grayscale
---

{{cssref}}

O **`grayscale()`** é uma função do [CSS](/pt-BR/docs/Web/CSS) que modifica a imagem adicionada para as cores branco e preto . Esse resultado é um efeito "filtro". {{cssxref("&lt;filter-function&gt;")}}.

{{InteractiveExample("CSS Demo: grayscale()")}}

```css interactive-example-choice
filter: grayscale(0);
```

```css interactive-example-choice
filter: grayscale(0.2);
```

```css interactive-example-choice
filter: grayscale(60%);
```

```css interactive-example-choice
filter: grayscale(1);
```

```html interactive-example
<section id="default-example">
  <img
    class="transition-all"
    id="example-element"
    src="/shared-assets/images/examples/firefox-logo.svg"
    width="200" />
</section>
```

## Sintaxe

```
grayscale(quantidade)
```

### Parâmetros

- `quantidade`
  - : A quantia da conversão é especificada em {{cssxref ("&lt;number&gt;")}} (número) ou {{cssxref ("&lt;percentage&gt;")}} (porcentagem). Um valor de `100%` indica que a cor está compeltamente dentro da escala de cinza. Um valor de `0%` não altera as cores da imagem, que permanecerá igual a original. Valores entre `0%` e `100%` são multiplicadores lineares no efeito cinza, modificando a escala de cores conforme a quantidade determinada. A quantia em número é equivalente a em porcentagem.

```css
grayscale(0)     /* Não afeta a imagem */
grayscale(.7)    /* .7 => 70% de branco&preto */
grayscale(100%)  /* Completamente em branco&preto */
```

## Veja também

- {{cssxref("&lt;filter-function&gt;")}}
