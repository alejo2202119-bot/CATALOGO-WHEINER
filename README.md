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

- `index.html` — **archivo único** que contiene todo: la portada de bienvenida
  como capa a pantalla completa y, debajo, el catálogo con banner, buscador,
  categorías, carrito y modo edición. El botón "Ver catálogo" solo oculta la
  portada; no navega a otro archivo.
- `catalogo.html` — el catálogo por separado; se conserva como respaldo, pero
  el link público apunta a `index.html`.

## Modo edición

1. Toca el punto **●** al final del pie de página.
2. Escribe la clave: **W-2026** (puedes cambiarla editando `ADMIN_CODES`
   en `index.html`).
3. Dentro del modo edición puedes: cambiar estado (Disponible/Agotado), precio,
   nombre o foto de cada producto tocándolos directamente, o agregar productos
   nuevos con el botón "＋ Producto".
4. Al terminar, toca **Descargar** para bajar el archivo actualizado y súbelo
   al repositorio para que el cambio quede publicado para todos (si no se sube,
   el cambio solo se ve en ese dispositivo).

Mientras no haya ningún producto cargado, el catálogo muestra un aviso de
"¡Muy pronto!"; ese aviso desaparece solo en cuanto se agrega el primer
producto.

## Banner principal

La imagen oficial está en `assets/banner-wheiner.webp`. Para cambiarla,
reemplaza ese archivo conservando el mismo nombre.

## Publicación

El catálogo se sirve con [raw.githack.com](https://raw.githack.com), que
entrega el archivo del repositorio directamente como página web, con
cabeceras `no-cache`. Eso significa que **el link siempre muestra la última
versión**, sin caché intermedia y sin ningún paso de publicación aparte: basta
con subir el cambio a la rama `claude/moto-repuestos-wheiner-catalog-8nu166`.

**Link único y permanente:**

https://raw.githack.com/alejo2202119-bot/CATALOGO-WHEINER/claude/moto-repuestos-wheiner-catalog-8nu166/index.html

Este link no cambia nunca mientras la rama conserve ese nombre.
