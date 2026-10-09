# Visor BIM · Alumbrado ornamental de las murallas de Dalt Vila

Visor 3D interactivo de la propuesta de renovación del alumbrado ornamental del recinto amurallado de Dalt Vila (Eivissa), elaborado por **Artecoin Consultoría Sostenible** para el Ajuntament d'Eivissa.

Permite comparar el estado actual con la propuesta y ver las escenas de iluminación (blanco cálido, blanco neutro, bandera balear, colores) desde cualquier punto de vista. Funciona en ordenador, tablet y móvil (iPhone y Android), sin instalar nada.

## Contenido del paquete

| Archivo | Para qué sirve |
|---|---|
| `index.html` | El visor completo, en un único archivo (modelo, texturas y código incluidos) |
| `preview.jpg` | Imagen de vista previa al compartir el enlace (WhatsApp, correo, Teams) |
| `icon.png` | Icono de la pestaña y del acceso directo en la pantalla de inicio del móvil |
| `robots.txt` | Evita que buscadores como Google indexen la página |
| `.nojekyll` | Indica a GitHub Pages que publique los archivos tal cual |

## Publicar en GitHub Pages (unos 5 minutos)

1. Entra en [github.com](https://github.com) con la cuenta de Artecoin (o crea una gratuita).
2. Pulsa **New repository**.
   - Nombre: `dalt-vila-visor` (el nombre forma parte del enlace).
   - Visibilidad: **Public** (necesario en cuentas gratuitas para GitHub Pages).
   - Pulsa **Create repository**.
3. En el repositorio vacío, pulsa **uploading an existing file**.
4. Arrastra **todos los archivos de esta carpeta** (incluido `.nojekyll`; si no se ve, activa "mostrar archivos ocultos" en el explorador). Pulsa **Commit changes**.
5. Ve a **Settings → Pages**.
   - En *Source* elige **Deploy from a branch**.
   - *Branch*: **main** y carpeta **/ (root)**. Pulsa **Save**.
6. Espera 1–2 minutos y recarga la página de Settings → Pages. Aparecerá el enlace:

   `https://<usuario-de-github>.github.io/dalt-vila-visor/`

Ese enlace se abre directamente en Safari o Chrome del móvil, sin iniciar sesión.

## Vista previa al compartir el enlace

WhatsApp y otras apps necesitan la dirección completa de la imagen de vista previa. Una vez tengas el enlace definitivo, edita `index.html` en GitHub (icono del lápiz) y cambia:

```html
<meta property="og:image" content="preview.jpg">
```

por:

```html
<meta property="og:image" content="https://<usuario-de-github>.github.io/dalt-vila-visor/preview.jpg">
```

## Uso en el móvil

- **Un dedo**: girar · **pellizcar**: acercar/alejar · **dos dedos**: desplazar.
- Los botones de vista (Puerto, Santa Tecla, Catedral…) se deslizan en horizontal.
- En horizontal el modelo ocupa toda la pantalla.
- En iPhone: botón Compartir → **Añadir a pantalla de inicio** para abrirlo como una app.
- La primera carga descarga unos 5 MB; con 4G tarda pocos segundos.

## Actualizar el visor

Sustituye `index.html` en el repositorio (Add file → Upload files, con el mismo nombre). GitHub Pages publica el cambio en 1–2 minutos con el mismo enlace.

## Privacidad

El enlace es público: cualquiera que lo tenga puede verlo, pero no aparece en buscadores. Si en algún momento debe dejar de estar accesible, en Settings → Pages pulsa **Unpublish site** o elimina el repositorio.

---

© 2026 Artecoin Consultoría Sostenible · Valores de ahorro estimados, supeditados a la realización de estudios luminotécnicos detallados.
