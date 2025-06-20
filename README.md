# Laboratorio 04: Markdown y Github Pages

Este laboratorio nos permite entender el proceso de despliegue, desde un entorno privado hacia un entorno público. No solo vamos a compartir nuestro catálogo web con el mundo usando GitHub Pages, sino que también vamos a documentarlo como verdaderos desarrolladores usando Markdown. Esta etapa nos conecta con prácticas reales de la industria como la documentación y el despliegue continuo.

## 🎯 Objetivos de aprendizaje

- Publicar un sitio web estático usando GitHub Pages.
- Documentar un proyecto usando Markdown en el archivo `README.md`.
- Integrar el catálogo web dentro de una estructura profesional de repositorio.

## 🔑 Conceptos Clave

- **GitHub Pages**: Servicio gratuito que permite alojar sitios web estáticos directamente desde un repositorio de GitHub.
- **README.md**: Archivo de texto escrito en Markdown que explica el propósito, estructura y uso de un proyecto.
- **Markdown**: Lenguaje de marcado ligero usado para dar formato a texto (títulos, listas, enlaces, imágenes).
- **Repositorio**: Espacio donde se guarda y organiza el código fuente y los archivos de un proyecto.
- **Despliegue**: Proceso de poner un proyecto en línea para que otros puedan verlo y usarlo.

## ⚙️ Setup inicial

- Este laboratorio requiere que ya tengas una cuenta gratuita en Github.

---

## 💻 Actividades paso a paso

### 1. Crea el Repositorio en GitHub
- Nombre sugerido: `catalogo-web`
- Descripción: `Mi primer sitio web para el mundo`
- Marca la opción **"Add a README file"**
- Crea el repo

### 2. Entra en modo desarrollo
- Dentro del repositorio, presiona la tecla `.` (dot) para activar el editor web (modo VS Code).
- Espera a que cargue el modo Editor Web.
- Modifica el contenido de tu archivo `README.md`
    - Encabezado principal: **Catálogo web - Documentación básica**
    - Párrafo: **Este proyecto es un pequeño catálogo web para el nivel Code 101 - Elementals.**
    - Encabezado secundario: **Lenguajes aprendidos**
    - Lista sin orden los 3 elementos: **HTML**, **CSS**, **Markdown**
    - Confirma tus cambios:
        - En el menú lateral izquierdo, entra a la opción `Control de código fuente`.
        - Agrega un mensaje: **Primer commit**
        - Presiona `Confirmar y enviar cambios`

### 3. Publica tu web
- Ahora, sal del modo desarrollo:
    - Modifica la URL y cambia el `.dev` por el `.com` solamente
    - El resto déjalo tal cual.
    - Presiona Enter
- Ya en el repositorio, dirigete hacia `Settings`
- Ahora, en el menu lateral izquierdo, ve hacia `Pages`
- Ahora, en el contenido principal, ubica el selector `Branch` y cámbialo de `none` hacia **`main`**
- Finalmente, guarda tus cambios y espera al menos 1 minuto.
- Refresca esta misma página y verás que en la parte superior aparecerá un cuadro que dice:
    - **Your site is live at ...**
    - Dale clic y verifica que tu sitio ha sido desplegado.
- Comparte el link de tu sitio web por el canal de Slack de tu sección.

- **Checkpoint 1 [20']**: Tu sitio web hecho con Markdown publicado en internet.

---

## 🏆 Retos

> 👀 Vuelve a entrar en **Modo Desarrollo** (presionando el `.`) para trabajar estos retos.

### 1. Bitácora técnica en Markdown
- Agrega al final de tu archivo `README.md` una sección con encabezado y lista:
```md
## Bitácora Técnica

Documentaré las etiquetas HTML y propiedades CSS que más han servido o gustado:

### Etiquetas HTML semánticas:
- (etiqueta 1)
- (etiqueta 2)
- (etiqueta ...)

### Propiedades de CSS:
- (propiedad 1: valor 1)
- (propiedad 2: valor 2)
- (propiedad ...)
```
- Realiza un nuevo commit: **Bitácora técnica**
- Espera a que tu sitio web haya sido actualizado (Compruébalo en tu navegador).

- **Checkpoint 2 [40']**: Tu sitio web desplegado, ahora muestra una bitácora técnica con al menos 6 elementos.

### 3. Agrega tu proyecto HTML
- Crea una carpeta llamada `demo/`
- Dentro de `demo/` sube tus archivos trabajados:
    - `index.html`
    - `styles.css`
    - Imágenes si tuvieras, sino, sigue trabajando con imágenes externas.
- Realiza un nuevo commit: **Demo del catálogo web**
- Espera a que tu sitio web haya sido actualizado y comprueba que se puede acceder a tu catálogo web: `https://tu-usuario.github.io/catalogo-web/demo`

- **Checkpoint 3 [60']**: Tu sitio web desplegado ahora incluye el demo de tu catálogo web en `/demo`


## ⭐️ Logros Adicionales

### 1. Captura de pantalla
- Toma un pantallazo de tu catálogo funcionando (versión desplegada).
- Agrégalo a tu `README.md` usando Markdown. Puedes subir la imagen al repositorio y luego insertarla.

## 📝 Instrucciones de Entrega
- Responde a esta actividad en Canvas.
- Agrega el link de tu Repositorio de Github.
- Agrega el link de tu Sitio Publicado en Github Pages.
- Agrega en tu respuesta:
    1. ¿Por qué es importante documentar lo que haces?
    2. ¿Qué impacto tiene poder mostrar tu trabajo públicamente?
    3. ¿Qué más te gustaría publicar ahora que conoces Github Pages?
