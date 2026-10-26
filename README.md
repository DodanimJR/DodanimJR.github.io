# Portafolio · Patrick Dodanim Castillo Flores

Customer Success Engineer / Software Developer. Sitio estático (HTML + CSS + JS sin dependencias) publicado con GitHub Pages.

## Estructura

```
index.html   Página completa (ES/EN)
cv/          CV en PDF, español e inglés
shots/       Capturas de los proyectos
favicon.svg
```

## Editar

Todo vive en `index.html`. Los textos en inglés están en el objeto `EN` dentro del `<script>` al final; los textos en español son el HTML mismo (atributos `data-i18n`).

## Publicar

Cada push a `main` se publica solo en GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).
