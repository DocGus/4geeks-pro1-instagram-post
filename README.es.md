# 📸 Post de Instagram — 4Geeks

> Recreación visual de una publicación de Instagram con HTML5 y CSS3.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-local-000000?logo=flask&logoColor=white)

## 📌 Descripción

Este proyecto forma parte de los ejercicios de **4Geeks Academy**. El objetivo es recrear la interfaz de un post de Instagram a partir de una referencia visual, practicando la estructura semántica de HTML y los fundamentos de CSS.

El proyecto comenzó utilizando la [plantilla oficial de 4Geeks Academy](https://github.com/4GeeksAcademy/html-hello), que incluye un servidor local basado en Flask.

## 🚀 Cómo ejecutarlo

### Requisitos

- Python 3
- Flask

### Instalación

1. Crea y activa un entorno virtual si todavía no tienes uno.
2. Instala Flask:

```bash
pip install flask
```

3. Inicia el servidor local:

```bash
python server.py
```

4. Abre [http://127.0.0.1:3000](http://127.0.0.1:3000) en el navegador.

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
| --- | --- |
| HTML5 | Estructura del post |
| CSS3 | Diseño, espaciado y distribución |
| Python | Ejecución del servidor local |
| Flask | Servidor de desarrollo |
| Google Fonts | Tipografía Roboto |
| Font Awesome | Iconos de la interfaz |
| Git y GitHub | Control de versiones |

## 🧱 Estructura del proyecto

```text
4geeks-pro1-instagram-post/
├── index.html
├── styles.css
├── server.py
├── learn.json
├── README.md
├── README.es.md
├── README.cn.md
└── .gitignore
```

> El entorno virtual `venv/` se mantiene fuera del control de versiones mediante `.gitignore`.

## 🧩 Estructura del post

La interfaz se dividió en los siguientes bloques:

```text
Post
├── Cabecera
│   ├── Icono HTML5
│   ├── Nombre y usuario
│   └── Menú de opciones
├── Imagen
├── Barra de iconos
│   ├── Like
│   ├── Comentario
│   ├── Compartir
│   └── Guardar
└── Cuerpo del post
    ├── Información de likes
    └── Descripción
```

Entre los elementos HTML utilizados se encuentran `div`, `strong`, `p`, `img`, `i` y `link`.

## 🎨 Conceptos de CSS practicados

### Selectores y Box Model

Se utilizaron clases para aplicar estilos específicos a cada componente, por ejemplo:

```css
.post {
    width: 500px;
    margin: 50px auto;
    border: 1px solid #ddd;
    box-sizing: border-box;
}
```

También se practicaron `margin`, `padding`, `border`, `width` y `box-sizing`.

### Flexbox

Flexbox se utilizó para organizar horizontalmente la cabecera, la información del usuario y los iconos:

```css
.post-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```

### Tipografía e imágenes

Se utilizó Roboto mediante Google Fonts y se adaptó la imagen al ancho disponible del post:

```css
.post-img img {
    width: 100%;
    display: block;
}
```

## ⭐ Iconos e imagen

Los iconos de HTML5, like, comentarios, compartir, guardar y menú de opciones se incorporaron mediante Font Awesome y su CDN.

Durante el desarrollo se utilizó [Picsum Photos](https://picsum.photos/) como fuente provisional de imagen:

```html
<img
    src="https://picsum.photos/500/350"
    alt="Fotografía del post"
>
```

Al tratarse de un servicio de imágenes aleatorias, la fotografía puede cambiar al recargar la página.

## 📚 Lo que aprendí

- Crear la estructura básica de un documento HTML5.
- Relacionar HTML y CSS mediante clases y hojas de estilos.
- Aplicar el modelo de cajas y organizar componentes con Flexbox.
- Utilizar Google Fonts y Font Awesome mediante CDN.
- Adaptar imágenes al tamaño de un contenedor.
- Visualizar un proyecto con un servidor local de Flask.
- Trabajar con entornos virtuales de Python.
- Utilizar Git y GitHub durante el desarrollo.

## 🔄 Proceso de desarrollo

1. Crear un repositorio a partir de la plantilla de 4Geeks Academy.
2. Clonar el repositorio y abrirlo en VS Code.
3. Crear el entorno virtual e instalar Flask.
4. Construir la estructura HTML del post.
5. Conectar `index.html` con `styles.css`.
6. Incorporar Google Fonts y Font Awesome.
7. Aplicar estilos y organizar los componentes con Flexbox.
8. Ejecutar el servidor local y comprobar los cambios.
9. Controlar las modificaciones con Git.

## 🎯 Resultado

Una recreación funcional de un post de Instagram que aplica fundamentos de estructura, estilos, tipografía, imágenes, iconos, Box Model y Flexbox.

## 👨‍💻 Autor

**Gustavo A. Santoyo B.**

Proyecto realizado como parte del aprendizaje de desarrollo Full Stack en 4Geeks Academy.

## 📖 Plantilla original

El proyecto se inició con la [plantilla HTML oficial de 4Geeks Academy](https://github.com/4GeeksAcademy/html-hello).