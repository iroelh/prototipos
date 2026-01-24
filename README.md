# Proyectos IV: Generación de Prototipos — Sitio de presentación (EDINBA–INBAL)

Sitio web ligero (HTML/CSS) para presentar el curso **Proyectos IV: Generación de Prototipos** (MCD · EDINBA–INBAL), con estética de “burbujas” sobre fondo blanco, navegación por secciones y una tabla guía del documento/proyecto (con **Prototipado** resaltado).

Incluye crédito en el pie de página: **© [año] Dr. Iroel Heredia · EDINBA–INBAL** (el año se calcula automáticamente en el navegador).

---

## Estructura del proyecto

- `index.html`  
  Página única con secciones:
  - Encuadre
  - Unidades
  - Estructura guía (tabla)
  - Evaluación
  - Recursos
  - Accesos (correo + Classroom)

- `styles.css`  
  Estilos, layout, “burbujas” y paleta inspirada en EDINBA (rojo institucional + acentos cálidos).

---

## Cómo publicarlo en GitHub Pages (rápido)

1. Crea un repositorio en GitHub (por ejemplo: `proyectos-iv-prototipos`).
2. Sube `index.html` y `styles.css` a la raíz del repositorio.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` / root
5. Guarda. GitHub te dará la URL publicada.

---

## Personalización rápida

### 1) Cambiar datos del curso (título, semestre, etc.)
Edita `index.html`:
- Título principal: en el `<h1>`
- Subtítulo: clase `.subtitle`
- Secciones: texto dentro de cada `<section>`

### 2) Ajustar unidades y entregas
En `index.html`, sección:
- `id="unidades"` → tarjetas/burbujas de Unidades 1–6

### 3) Ajustar la tabla guía (estructura)
En `index.html`, sección:
- `id="estructura"` → tabla `.guideTable`

La fila resaltada de **Prototipado** está marcada como:
- `<tr class="hiProto"> ... </tr>`

### 4) Ajustar paleta EDINBA
En `styles.css`, bloque `:root`:
- `--p1` a `--p6` controlan acentos principales (rojo, ámbar, magenta, violeta, etc.).

---

## Accesos incluidos

- Correo: `mailto:dis.erickheredia@inba.edu.mx`
- Classroom: `https://classroom.google.com/c/ODQxMTU1MzEzOTE0?cjc=qjvij6il`

---

## Notas de uso

- Es un sitio estático: no requiere servidor, base de datos ni dependencias.
- Ideal para proyectarse en clase o dejarlo como “home” del curso.
- Si lo deseas, se puede extender con:
  - Calendario por fechas del semestre
  - Rúbrica de evaluación
  - Sección de entregables por sesión/unidad
  - Botones para descargar formatos (cuando aplique)

---

## Autoría / crédito

**Dr. Iroel Heredia · EDINBA–INBAL**  
2026
