# 📸 Instagram Post — 4Geeks

> A visual recreation of an Instagram post using HTML5 and CSS3.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-local-000000?logo=flask&logoColor=white)

## 📌 Description

This project is part of the exercises from **4Geeks Academy**. The goal is to recreate an Instagram post interface from a visual reference while practicing semantic HTML structure and CSS fundamentals.

The project was started using the [official 4Geeks Academy template](https://github.com/4GeeksAcademy/html-hello), which includes a local Flask-based server.

## 🚀 How to run it

### Requirements

- Python 3
- Flask

### Installation

1. Create and activate a virtual environment if you do not already have one.
2. Install Flask:

```bash
pip install flask
```

3. Start the local server:

```bash
python server.py
```

4. Open [http://127.0.0.1:3000](http://127.0.0.1:3000) in your browser.

## 🛠️ Technologies used

| Technology | Use |
| --- | --- |
| HTML5 | Post structure |
| CSS3 | Design, spacing and layout |
| Python | Local server runtime |
| Flask | Development server |
| Google Fonts | Roboto typography |
| Font Awesome | Interface icons |
| Git and GitHub | Version control |

## 🧱 Project structure

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

> The `venv/` virtual environment is kept out of version control through `.gitignore`.

## 🧩 Post structure

The interface was divided into the following blocks:

```text
Post
├── Header
│   ├── HTML5 icon
│   ├── Name and username
│   └── Options menu
├── Image
├── Icon bar
│   ├── Like
│   ├── Comment
│   ├── Share
│   └── Save
└── Post body
  ├── Likes information
  └── Description
```

The HTML elements used include `div`, `strong`, `p`, `img`, `i` and `link`.

## 🎨 CSS concepts practiced

### Selectors and Box Model

Classes were used to apply specific styles to each component, for example:

```css
.post {
  width: 500px;
  margin: 50px auto;
  border: 1px solid #ddd;
  box-sizing: border-box;
}
```

The project also practices `margin`, `padding`, `border`, `width` and `box-sizing`.

### Flexbox

Flexbox was used to arrange the header, user information and icons horizontally:

```css
.post-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

### Typography and images

Roboto was added through Google Fonts, and the image was adapted to the available post width:

```css
.post-img img {
  width: 100%;
  display: block;
}
```

## ⭐ Icons and image

HTML5, like, comment, share, save and options menu icons were added through Font Awesome and its CDN.

During development, [Picsum Photos](https://picsum.photos/) was used as a temporary image source:

```html
<img
  src="https://picsum.photos/500/350"
  alt="Post photograph"
>
```

Since this is a random image service, the photograph may change when the page is reloaded.

## 📚 What I learned

- Build the basic structure of an HTML5 document.
- Connect HTML and CSS using classes and stylesheets.
- Apply the Box Model and organize components with Flexbox.
- Use Google Fonts and Font Awesome through a CDN.
- Adapt images to the size of a container.
- Preview a project with a local Flask server.
- Work with Python virtual environments.
- Use Git and GitHub during development.

## 🔄 Development process

1. Create a repository from the 4Geeks Academy template.
2. Clone the repository and open it in VS Code.
3. Create the virtual environment and install Flask.
4. Build the HTML structure for the post.
5. Connect `index.html` to `styles.css`.
6. Add Google Fonts and Font Awesome.
7. Apply styles and organize the components with Flexbox.
8. Run the local server and check the changes.
9. Track modifications with Git.

## 🎯 Result

A functional recreation of an Instagram post applying the fundamentals of structure, styling, typography, images, icons, Box Model and Flexbox.

## 👨‍💻 Author

**Gustavo A. Santoyo B.**

Project created as part of the Full Stack development learning path at 4Geeks Academy.

## 📖 Original template

The project was started with the [official 4Geeks Academy HTML template](https://github.com/4GeeksAcademy/html-hello).
