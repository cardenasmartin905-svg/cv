# CV — Martín Contreras Cárdenas

Página de currículum con GitHub Pages.
Sitio publicado: https://cardenasmartin905-svg.github.io/cv/

## Cómo actualizar los archivos

### Opción A — Editar directo en GitHub (la más fácil)

Para cambios pequeños de texto (sin instalar nada):

1. Entra a https://github.com/cardenasmartin905-svg/cv
2. Abre el archivo que quieras cambiar (`index.html`, `style.css`, etc.)
3. Da clic en el ícono de lápiz (✏️) arriba a la derecha
4. Haz tus cambios
5. Abajo escribe un mensaje corto (p. ej. "Actualizo teléfono") y pulsa **Commit changes**

La página se publica sola en unos minutos.

### Opción B — GitHub Desktop (para editar desde tu editor)

1. Descarga e instala GitHub Desktop: https://desktop.github.com
2. Abre la app → **File → Clone repository** → elige `cardenasmartin905-svg/cv`
3. Edita los archivos localmente (`index.html` está en la carpeta que elijas)
4. En GitHub Desktop:
   - Verás los cambios en la pestaña **Changes**
   - Escribe un mensaje abajo a la izquierda
   - Pulsa **Commit to main**
   - Pulsa **Push origin** (botón arriba)

### Opción C — Terminal (git ya instalado)

Desde la carpeta del proyecto:

```bash
git add -A
git commit -m "Describe el cambio"
git push
```

Si la página que publica GitHub se ve vieja, actualiza con el navegador:
**Ctrl + Shift + R** (recarga forzada) o ventana de incógnito.

## Estructura del proyecto

```
index.html              Página principal
style.css               Estilos
Assets/icons8-sun.json  Animación Lottie del botón (sol/luna)
Assets/Logo.svg         Logo del masthead
```

## Notas

- El toggle de tema guarda la preferencia en `localStorage`.
- El botón de tema usa `lottie-web` vía CDN (requiere internet).
- El CTA de Behance, teléfono (`tel:`) y correo (`mailto:`) están en el footer y en el kicker del masthead.