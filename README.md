# Proyecto: Sitio estático de ejemplo

Este repositorio contiene archivos para un proyecto didáctico simple: una página HTML (`blog.html`) y carpetas relacionadas con imágenes y fotos. El objetivo del README es documentar la estructura, uso y pasos para probar localmente el proyecto.

## Resumen

- Nombre: Sitio estático de ejemplo
- Propósito: Proveer una base mínima para mostrar contenido estático (un blog simple), practicar servir archivos locales y organizar recursos multimedia.
- Fecha: 21-02-2026

## Contenido del repositorio

- `blog.html` — Página HTML principal del sitio (entrada del "blog").
- `notes.txt` — Notas relacionadas con la clase o desarrollo.
- `fotos/` — Carpeta con archivos relacionados a fotos.
  - `fotos/fotos.txt` — Lista o metadatos de fotos.
- `imagenes/` — Carpeta para imágenes (actualmente puede estar vacía o contener recursos adicionales).

(Revisa estas rutas en tu copia local para confirmar contenido adicional.)

## Estructura de archivos (desglose)

- `blog.html`: HTML estático. Úsalo como punto de partida para editar o extender el contenido del blog.
- `notes.txt`: Apuntes, tareas o recordatorios relacionados con la clase/ejercicio.
- `fotos/fotos.txt`: Podría contener nombres de archivos, descripciones o anotaciones sobre imágenes.
- `imagenes/`: Lugar destinado para imágenes que usa `blog.html` o futuras páginas.

## Requisitos

- Navegador web moderno (Chrome, Edge, Firefox, etc.).
- Python 3.x (opcional, para servir el sitio localmente)

Nota: No hay dependencias externas ni build tools en este proyecto; es un sitio estático.

## Cómo ejecutar / probar localmente

La forma más sencilla es abrir `blog.html` directamente en un navegador (doble clic). Para un comportamiento más realista (servidor HTTP local), usa Python:

PowerShell / Terminal (desde la carpeta del proyecto):

```powershell
cd "c:\Users\Leonardo\Desktop\clase_3"
python -m http.server 8000
```

Luego abre en el navegador:

http://localhost:8000/blog.html

Alternativa para Python 2 legacy (NO recomendado, solo por compatibilidad):

```powershell
python -m SimpleHTTPServer 8000
```

Estas opciones sirven archivos estáticos y permiten verificar rutas relativas y recursos (imágenes, CSS/JS si se añaden).

## Uso y desarrollo

- Edita `blog.html` para cambiar contenido, estructura o estilos.
- Añade imágenes a `imagenes/` y referencia su ruta relativa desde `blog.html`.
- Mantén cualquier lista o metadato en `fotos/fotos.txt` si necesitas documentar imágenes.

Sugerencias de mejoras:
- Añadir un archivo `styles.css` y enlace desde `blog.html` para separar estilos.
- Crear una carpeta `js/` si se va a añadir comportamiento interactivo.
- Organizar imágenes en subcarpetas por tema o tamaño.

## Contribución

Este proyecto parece personal/educativo. Si deseas colaborar o versionar:

- Crea un fork o clona el repositorio.
- Abre una rama por característica: `feature/nueva-pagina`.
- Envía un pull request con cambios claros y descripción.

Para cambios locales simples, mantener commits pequeños y mensajes claros (ej.: "Agrega estilos base a blog.html").

## Buenas prácticas recomendadas

- Mantener rutas relativas en HTML para facilitar pruebas locales.
- Optimizar imágenes antes de agregarlas a `imagenes/` para reducir tamaño.
- Añadir un `.gitignore` si empiezas a versionar y no quieres subir archivos grandes o temporales.

## Licencia

Si no hay una licencia definida en el repositorio, por defecto aplica la protección por derechos de autor del autor. Si quieres permitir uso y contribuciones abiertas, añade un archivo `LICENSE` con la licencia que prefieras (ej.: MIT, Apache-2.0).

## Metadatos y contacto

- Autor: (no especificado) — actualiza este README con tu nombre o contacto si lo deseas.
- Fecha de generación: 21-02-2026

## Notas finales

- Este repositorio está pensado como material didáctico: ligero, sin dependencias y fácil de servir localmente.
- Si quieres que amplíe el README con secciones adicionales (por ejemplo: ejemplos de HTML, snippets CSS básicos, checklist para producción o un archivo `package.json` y pipeline de build), dime qué prefieres y lo añado.
