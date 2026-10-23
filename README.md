# Portal académico corregido

Esta versión incluye los estilos, datos de seis unidades de aprendizaje y lógica JavaScript **dentro de `index.html`**. No depende de carpetas `js/` o `css/`.

## Publicación en GitHub Pages
1. En tu repositorio abre `index.html` y selecciona **Edit this file** (icono lápiz); sustituye todo su contenido por el del nuevo `index.html` (o elimina el antiguo y sube el nuevo con el mismo nombre).
2. Sube la carpeta `materiales/` en la raíz del repositorio para conservar los enlaces a los PDF.
3. Confirma los cambios en la rama `main` y revisa **Settings > Pages** con rama `main` y `/(root)`.
4. Actualiza la página con Ctrl+F5 (o en una pestaña privada).

## Organización
- `index.html`: sitio completo (HTML, CSS y JavaScript)
- `materiales/ia/IA_clase_1_Introduccion_IA.pdf`: presentación real de IA incluida en el ZIP aportado
- `materiales/ejemplos/`: archivos de demostración

## Edición de cursos y recursos
En `index.html`, busca `window.PORTAL_DATA`. Agrega los cursos en `courses` y los archivos en `resources`.

**Privacidad:** evita publicar datos personales o calificaciones de estudiantes en un repositorio público.
