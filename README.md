# Elevate Animation

A clean SVG-based logo animation project that demonstrates advanced SVG techniques such as **custom paths**, **curved shapes**, **stroke drawing**, and **left-to-right fill reveal using masks**. The animation visually represents an *elevating* motion with a concave star, curved lines, and progressive fill.

---

## ✨ Features

* Custom **concave star** SVG path
* Symmetrical **left and right curved paths**
* Horizontal guide line
* **Mask-based fill animation** (left → right reveal)
* Scalable SVG (no image assets)
* Pure **HTML + CSS** (no JavaScript)

---

## 🧩 Project Structure

```text
├── index.html
├── style.css
└── README.md
```

---

## 📄 index.html (Overview)

* Contains a single SVG acting as the logo container
* SVG elements used:

  * `<path>` for star and curves
  * `<line>` for top divider
  * `<mask>` for left-to-right fill animation
  * `<text>` for the brand name **ELEVATE**

The SVG is scalable and animation-friendly.

---

## 🎨 Key SVG Elements

### Star Shape

* Custom concave star built using cubic Bézier curves
* Wrapped in a `<g>` element for easy scaling

### Curves

* Left and right curves are mirrored
* Direction reversed to animate bottom → top correctly

### Mask Reveal Fill

* Uses an animated `<rect>` inside an SVG `<mask>`
* Creates a smooth left-to-right fill effect

---

## 🎞️ Animation Concepts Used

* `transform: scale()` for resizing SVG elements
* `transform-box: fill-box` and `transform-origin: center`
* SVG `mask` for progressive fill
* CSS `@keyframes` for timing and easing

---

## 🚀 How to Run

1. Clone or download the project
2. Open `index.html` in any modern browser
3. No build steps or dependencies required

---

## 🛠️ Customization

* Adjust animation timing in `style.css`
* Change star size using `scale()`
* Modify mask width for faster/slower fill
* Update text spacing or font for branding

---

## 🧠 Best Practices Followed

* No layout-breaking animations (`top`, `margin`, etc.)
* GPU-accelerated transforms
* Clean SVG structure
* Animation-friendly paths

---

## 📌 Ideal Use Cases

* Logo intro animation
* Landing page hero animation
* Brand reveal
* Motion design practice

---

## 👤 Author

**Abinesh**

---

## 📄 License

This project is open for learning and personal use.
