# Catálogo digital — Moto Repuestos Wheiner SAS

Catálogo web con buscador, carrito y pedido directo por WhatsApp, más un modo
de edición para actualizar el catálogo sin tocar código.

## Datos de la empresa

- **Empresa:** Moto Repuestos Wheiner SAS
- **NIT:** 900862610-6
- **Dirección:** Av. 0 #8-05, Barrio Latino, Cúcuta, Norte de Santander
- **WhatsApp de pedidos:** +57 315 326 6522
- **Categorías:** Motor, Frenos, Eléctrico, Transmisión, Suspensión, Accesorios

## Páginas

- `index.html` — portada de bienvenida con el banner de la empresa; el botón
  "Ver catálogo" entra al catálogo.
- `catalogo.html` — catálogo con banner, buscador, categorías, carrito y modo
  edición.

Solo se comparte el link de la portada: desde ahí, un toque en "Ver catálogo"
lleva al catálogo completo.

## Modo edición

1. En `catalogo.html`, toca el punto **●** al final del pie de página.
2. Escribe la clave: **W-2026** (puedes cambiarla editando `ADMIN_CODES`
   en `catalogo.html`).
3. Dentro del modo edición puedes: cambiar estado (Disponible/Agotado), precio,
   nombre o foto de cada producto tocándolos directamente, o agregar productos
   nuevos con el botón "＋ Producto".
4. Al terminar, toca **Descargar** para bajar el archivo `catalogo.html`
   actualizado y súbelo al repositorio para que el cambio quede publicado para
   todos (si no se sube, el cambio solo se ve en ese dispositivo).

## Banner principal

La imagen oficial ya está puesta en `assets/banner-wheiner.webp` y se usa en
`index.html` y `catalogo.html`. Para cambiarla, reemplaza ese archivo (mismo
nombre) o actualiza el `src` de los `<img>` correspondientes.

## Publicación

El catálogo se ve en el navegador a través de [htmlpreview.github.io](https://htmlpreview.github.io),
que muestra en vivo el contenido de este repositorio — no requiere GitHub
Pages ni ningún paso de publicación aparte. Cada vez que se sube un cambio a
la rama `claude/moto-repuestos-wheiner-catalog-8nu166`, el link se actualiza
solo en segundos.

**Link único (portada):** https://htmlpreview.github.io/?https://raw.githubusercontent.com/alejo2202119-bot/CATALOGO-WHEINER/claude/moto-repuestos-wheiner-catalog-8nu166/index.html

Este link es estable mientras la rama exista con ese nombre.
