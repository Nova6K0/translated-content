---
title: ":local-link"
slug: Web/CSS/:local-link
page-type: css-pseudo-class
spec-urls: https://drafts.csswg.org/selectors/#local-link-pseudo
---

{{CSSRef}}

 La [pseudo-clase](/es/docs/Web/CSS/Pseudo-classes) [CSS](/es/docs/Web/CSS)  **`:local-link`** representa un enlace al mismo documento. 
 Es decir, cualquier enlace interno anclado. Siempre que la ruta URL absoluta de destino apunte al mismo punto de anclaje, al que se hace 
 referencia. Y no pertenezca a un documento distinto, sin importar si es o no del mismo dominio (enlace externo).
 
```css
/* Selecciona cualquier enlace interno dentro del elemento <a> */
a:local-link {
  color: green;
}
```

## Sintaxis

```css
:local-link {
  /* ... */
}
```

## Ejemplos

### HTML

```html
<a href="#target">Este es un enlace perteneciente a la actual página o documento.</a><br />
<a href="https://example.com">Este es un enlace externo</a><br />
```

### CSS

```css
a:local-link {
  color: green;
}
```

### Resultado

{{EmbedLiveSample("Examples")}}

## Especificaciones

{{Specifications}}

## Navegadores compatibles

Esto es una característica propuesta para su integración dentro de las especificaciones. Actualmente, ningún navegador es compatible.

## Ver también

- Link-related pseudo-classes: {{ cssxref(":link") }}, {{ cssxref(":visited") }}, {{ cssxref(":hover") }}, {{ cssxref(":active") }}, {{ cssxref(":any-link") }}
