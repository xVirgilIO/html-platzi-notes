# Día 01 — Listas y enlaces

## Resumen de la clase (hasta 6/17)

### Listas
- **`<ul>`** para listas sin orden.
- **`<ol>`** para listas ordenadas.
- **`<li>`** para cada ítem.
- **`<dl>`**, **`<dt>`**, **`<dd>`** para listas de definición (término + descripción).

**Snippet básico:**
```html
<ul>
  <li>HTML semántico</li>
  <li>Estructura base</li>
  <li>Listas y enlaces</li>
</ul>

<ol>
  <li>Descargar editor</li>
  <li>Crear archivo index.html</li>
  <li>Escribir estructura base</li>
</ol>

<dl>
  <dt>HTML</dt>
  <dd>Lenguaje de marcado para estructurar contenido.</dd>
  <dt>CSS</dt>
  <dd>Lenguaje de estilos para presentar contenido.</dd>
</dl>
```

### Enlaces
- **`<a>`** crea un enlace.
- El atributo **`href`** define el destino.
- **Enlaces internos**: apuntan a secciones usando `#id`.
- **Enlaces externos**: apuntan a una URL completa.
- **`target="_blank"`** abre en nueva pestaña.
- **`rel="noopener noreferrer"`** es buena práctica al usar `_blank`.

**Snippet básico:**
```html
<a href="https://platzi.com" target="_blank" rel="noopener noreferrer">
  Ir a Platzi
</a>

<a href="#contacto">Ir a Contacto</a>

<section id="contacto">
  <h2>Contacto</h2>
</section>
```

## Buenas prácticas
- Usa listas solo cuando el contenido realmente es una lista.
- Evita listas con un solo ítem (normalmente es mejor un párrafo).
- No uses `<br>` para simular listas.
- Siempre agrega `rel="noopener noreferrer"` con `target="_blank"`.
- Los enlaces deben describir el destino (evita “click aquí”).

## Mini ejercicios
1. Crea una lista ordenada con 3 pasos para “publicar un sitio estático”.
2. Crea una lista de definición con 2 términos técnicos.
3. Agrega un índice con enlaces internos a dos secciones distintas.

## Enlaces útiles
- [MDN: Listas en HTML](https://developer.mozilla.org/es/docs/Web/HTML/Element/ul)
- [MDN: Elemento a](https://developer.mozilla.org/es/docs/Web/HTML/Element/a)

