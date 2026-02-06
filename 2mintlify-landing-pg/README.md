# Mintlify Landing Page Clone

A responsive front-end clone of the Mintlify landing page built using **HTML5** and **CSS3**.
This project focuses on recreating the layout, typography, spacing, and visual hierarchy of the original site for learning and practice purposes.

> ⚠️ This project is for educational use only and is not affiliated with Mintlify.

---

## 🚀 Features

- Sticky blurred navigation bar
- Hero section with gradient background and CTA form
- Testimonial logo grid
- Feature highlight cards
- Enterprise section with call-to-action
- Customer stories cards
- Final CTA section
- Fully structured footer with multiple columns
- Uses modern CSS techniques:
  - CSS variables
  - Flexbox & Grid
  - Backdrop filter blur
  - Custom fonts (Inter & Geist Mono)

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- Google Fonts (Inter, Geist Mono)
- Font Awesome Icons

---

## 📂 Folder Structure

```
mintlify-clone/
│
├── index.html
├── styles1.css
├── imgs/
│   ├── feature-img-left.png
│   ├── feature-img-right.png
│   ├── ui-mockup-img.png
│   ├── user-story.png
│   ├── story-logos.png
│   ├── perplexity-card.png
│   ├── x-card.png
│   └── kalshi-card.png
│
└── README.md
```

---

## 🎨 Customization

### Change Colors

Inside `styles1.css`:

```css
:root {
  --color-green: #18e299;
  --color-black: #08090b;
  --color-white: #ffffff;
}
```

Modify these values to apply a new theme.

---

### Change Background Image

```css
.bg-img-1 {
  background-image:
    linear-gradient(...), url("https://www.mintlify.com/hero/bg-light.svg");
}
```

Replace the URL with your own image.

---

### Replace Images

Put new images inside the `imgs/` folder and update the `src` paths in HTML.

---

## 📱 Responsiveness

Currently optimized for desktop layouts.
You can enhance mobile responsiveness by adding:

- Media queries
- Hamburger menu
- Stack layouts for cards and grids

---

## 📚 Learning Outcomes

- Building complex landing page layouts
- Using CSS variables for theming
- Structuring large HTML projects
- Creating reusable UI sections
- Practicing real-world cloning techniques

---

## ❗ Disclaimer

This project is a **visual clone** created strictly for educational purposes.
All product names, logos, and assets belong to their respective owners.

---

## ⭐ Future Improvements

- Add mobile responsive breakpoints
- Add animations & transitions
- Dark / light theme toggle with JS
- Convert to React / Next.js
- Deploy on GitHub Pages / Netlify

---

## 👤 Author

**Nitin**
