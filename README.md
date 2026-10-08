# Gestor de Juegos — Bootstrap

Proyecto de la materia Laboratorio de Programación - 6° G (IPET N° 249). Interfaz web de un gestor de juegos (biblioteca digital) hecha con HTML5 y Bootstrap 5.3.8, inspirada en plataformas como Steam o la Xbox App.

## Trabajo Práctico N° 13 - Construyendo un Gestor de Juegos Responsivo con Bootstrap

La página muestra un catálogo de 8 juegos retro y una tabla con la biblioteca del usuario. Toda la estructura visual está controlada por Bootstrap, sin CSS propio.

## Requisitos técnicos cumplidos

- Bootstrap 5.3.8 (la última versión) vinculado por CDN en el `<head>`; el JS se carga al final del `<body>` para el menú desplegable
- Modo oscuro global con `data-bs-theme="dark"` en la etiqueta `<html>`
- Contenido principal dentro de un `<div class="container">`
- Tabla HTML con `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>` y `<td>`, con las columnas ID, Nombre del Juego, Género, Año, Precio y Estado
- Clases utilitarias de Bootstrap:
  - Alineación: `text-center`
  - Colores de texto: `text-warning`, `text-primary`, `text-success`
  - Espaciado: `py-4`, `py-5`, `p-4`, `p-3`, `mb-4`
- Diseño responsivo: grilla de tarjetas con `row-cols-1 row-cols-sm-2 row-cols-lg-4`, navbar que se colapsa en pantallas chicas y tabla con `table-responsive`
- Código HTML ordenado y comentado, con comentarios de cierre de cada sección

## Estructura del proyecto

```
├── index.html
├── README.md
└── ficha-transparencia-IA.md
```

## Sobre el uso de Inteligencia Artificial

La IA se usó como asistente para generar una base de código y entender las clases de Bootstrap. El resultado se revisó en el navegador redimensionando la ventana. El detalle está en `ficha-transparencia-IA.md`.

## Tecnologías utilizadas

- HTML5
- Bootstrap 5.3.8 (CDN)

## Cómo verlo

Online (GitHub Pages): activar Pages en el repositorio (Settings > Pages > Branch: main) y abrir:
```
https://gera100101q.github.io/TU-REPOSITORIO/
```

Local: abrir index.html en el navegador (necesita internet para cargar Bootstrap desde el CDN).

## Datos de la entrega

- Trabajo Práctico: N° 13 - Construyendo un Gestor de Juegos Responsivo con Bootstrap
- Materia: Laboratorio de Programación
- Curso: 6° G - IPET N° 249
- Modalidad: Individual
- Fecha límite de entrega: 24-09-2026

## Autor

Gerardo Quiroga
