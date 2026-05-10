# 🎨 Color Generator

A minimal browser-based random color generator that changes the entire page background to a new hex color on every button click — and displays the generated hex code on screen. Built with HTML, CSS, and JavaScript.

---

## 📌 Overview

This is a single-purpose web app that generates a random hexadecimal color code every time the user clicks the button. The generated color is immediately applied as the background of the entire page, and its hex code (e.g., `#A3F2B1`) is displayed prominently on screen. The design is intentionally minimal — the app has exactly 1 button and 1 text display, keeping the experience focused and distraction-free.

---

## ✨ Features

- **Random Hex Color Generation** — On every click, JavaScript generates a new random 6-character hexadecimal color code from the full `#000000`–`#FFFFFF` color space.
- **Live Background Update** — The generated color is instantly applied as the background color of the entire page, giving an immediate full-screen visual effect.
- **Hex Code Display (`#colorCode`)** — The hex value of the currently displayed color is shown as a heading on screen. It starts with `#fff` and updates with every click to reflect the new color.
- **Single Click Button (`#btn`)** — One "Click me" button is all it takes. No forms, no inputs, no dropdowns — purely click-driven.
- **No Dependencies** — The HTML is only 21 lines. Pure HTML, CSS, and JavaScript with nothing else required.
- **Responsive Layout** — CSS ensures the button and color code display are properly centered and visible across desktop, tablet, and mobile screen sizes.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Minimal structure — color code display heading + single click button (21 lines total) |
| CSS3 | Layout centering, styling, responsive design |
| JavaScript (ES6+) | Random hex code generation, background color update, DOM text update |

---

## 📁 Project Structure

```
Color-Generator/
├── Index.html    # Main HTML — color code h2 display + "Click me" button
├── Style.css     # Styling — centered layout, typography, responsive design
├── Script.js     # Logic — random hex generation, background update, text display
└── README.md     # Project documentation
```

---

## 🚀 Getting Started

No setup needed. Just 3 steps:

**1. Clone the repository**
```bash
git clone https://github.com/tripathipawan/Color-Generator.git
```

**2. Navigate into the project folder**
```bash
cd Color-Generator
```

**3. Open in browser**
```
Open Index.html directly in any modern browser
— or use VS Code Live Server
```

---

## 🖱️ How to Use

1. Open the app — page loads with a white (`#fff`) background.
2. Click the **"Click me"** button.
3. The entire page background changes to a new random color.
4. The hex code of that color is displayed on screen.
5. Keep clicking to generate more colors.

---

## 🧠 How It Works

| Step | What Happens |
|---|---|
| 1 | User clicks the `#btn` button |
| 2 | JavaScript builds a random 6-character hex string using `Math.random()` and a hex character set |
| 3 | The hex value is prefixed with `#` to form a valid CSS color |
| 4 | The page background is updated to the new color via JavaScript |
| 5 | The `#colorCode` element's text is updated to display the new hex value on screen |

---

## 🌱 What I Learned

- Generating random hexadecimal color codes using `Math.random()` and string manipulation
- Applying dynamic CSS property changes to the full page background via JavaScript
- Building a fully functional interactive tool in under 25 total lines of HTML
- Keeping UI intentionally minimal while delivering a genuinely useful result

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m 'Add: your feature description'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Pawan Tripathi**
- GitHub: [@tripathipawan](https://github.com/tripathipawan)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
