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

### LINK OFICIAL Y DEFINITIVO — NO CAMBIAR

```
https://htmlpreview.github.io/?https://raw.githubusercontent.com/alejo2202119-bot/CATALOGO-WHEINER/claude/moto-repuestos-wheiner-catalog-8nu166/index.html
```

Este es el único link que se comparte con los clientes. **Nunca debe
cambiarse**, ni siquiera al hacer modificaciones al catálogo.

Para que ese link siga funcionando siempre, hay tres reglas que no se pueden
romper al editar el proyecto:

1. **No renombrar ni borrar** la rama
   `claude/moto-repuestos-wheiner-catalog-8nu166`, el repositorio, ni el
   archivo `index.html`.
2. **Todo debe vivir en `index.html`** (portada y catálogo juntos). No añadir
   enlaces `<a href>` que apunten a otro archivo `.html` del repositorio:
   htmlpreview.github.io reescribe esos enlaces anteponiéndoles su propio
   prefijo, lo que los duplica y rompe la navegación.
3. Las imágenes se referencian con **ruta relativa** (`assets/...`), que
   htmlpreview resuelve correctamente mediante el `<base>` que inyecta.

Cada cambio subido a esa rama aparece solo en el link. GitHub sirve el archivo
con `max-age=300`, así que un cambio recién subido puede tardar **hasta 5
minutos** en verse; no es un error, solo hay que esperar ese momento.
