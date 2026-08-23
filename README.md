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

- `index.html` — portada de bienvenida con el banner de la empresa.
- `catalogo.html` — catálogo con buscador, categorías, carrito y modo edición.

## Modo edición

1. En `catalogo.html`, toca el punto **●** al final del pie de página.
2. Escribe la clave: **Wheiner2026** (puedes cambiarla editando `ADMIN_CODES`
   en `catalogo.html`).
3. Dentro del modo edición puedes: cambiar estado (Disponible/Agotado), precio,
   nombre o foto de cada producto tocándolos directamente, o agregar productos
   nuevos con el botón "＋ Producto".
4. Al terminar, toca **Descargar** para bajar el archivo `catalogo.html`
   actualizado y súbelo al repositorio para que el cambio quede publicado para
   todos (si no se sube, el cambio solo se ve en ese dispositivo).

## Banner principal

Mientras no se suba la foto real del banner, se muestra un banner de
reemplazo con los colores de la marca. Para usar la foto real:

1. Sube la imagen a la carpeta `assets/` (por ejemplo `assets/banner.jpg`).
2. En `index.html` y `catalogo.html`, reemplaza el bloque marcado con el
   comentario `BANNER-PRINCIPAL` por:
   ```html
   <img src="assets/banner.jpg" alt="Moto Repuestos Wheiner">
   ```

## Publicación

El sitio se publica automáticamente con GitHub Pages en cada cambio que se
sube a este repositorio (workflow en `.github/workflows/pages.yml`).
