# 🎨 Amazing AwCSS @0.0.0

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/mrawab/awcss?style=social)](https://github.com/mrawab/awcss/stargazers)

### A lightweight, modern CSS utility framework  
**Clean • Minimal • Customizable**

Build fast, clean interfaces with simple utility classes and zero JavaScript.

[Getting Started](#-getting-started) •
[Utilities](#-utilities) •
[Buttons](#-buttons) •
[Typography](#-typography)

</div>

---

## ✨ Why AwCSS?

- ⚡ Lightweight & fast  
- 🎯 Utility-first but flexible  
- 🎨 Powered by CSS variables  
- 🧩 No build tools, no JS  
- 📱 Mobile-friendly by default  

---

## 📦 Getting Started

### Include AwCSS

#### Local
```html
<link rel="stylesheet" href="awcss.css">
```

#### GitHub Pages
```html
<link rel="stylesheet" href="https://mrawab.github.io/awcss/awcss.css">
```

---

## 🎨 CSS Variables

Customize the entire theme from one place:

```css
:root {
  --primary-color: #3878c3;
  --secondary-color: #ff5722;
  --success-color: #28a745;
  --warning-color: #ffc107;
  --danger-color: #dc3545;
}
```

---

## ✍️ Typography

### Headings
```html
<h1 class="heading-large">Large Heading</h1>
<h2 class="heading-medium">Medium Heading</h2>
<h3 class="heading-small">Small Heading</h3>
```

| Class | Description |
|-----|------------|
| `.heading-large` | Big titles |
| `.heading-medium` | Section headers |
| `.heading-small` | Sub headings |

### Text Helpers
```
.body-text
.muted-text
.highlight-text
.center-text
```

---

## ✨ Text Effects

### Gradient & Image Text
```html
<h1 class="text-clip">Gradient Text</h1>
<h1 class="text-clip-image">Image Text</h1>
<h1 class="text-clip-image-animated">Animated Text</h1>
```

---

## 🖍 Text Decorations

```
.text-shadow
.text-shadow-dark
.text-shadow-light
.bold
.italic
.underline
.upper
.lower
.caps
```

---

## 🛠 Utilities

### Interaction
```
.no-user-select
```

### Text Colors
```
.text-primary
.text-secondary
.text-success
.text-warning
.text-danger
.text-info
.text-highlight
.text-highlight-alt
```

---

## 🧱 Borders

```html
<div class="border border-primary">Box</div>
```

```
.border
.border-primary
.border-secondary
.border-success
.border-warning
.border-danger
.border-info
```

---

## 🖌 Backgrounds

```
.bg-primary
.bg-secondary
.bg-success
.bg-warning
.bg-danger
.bg-info
.bg-muted
.bg-highlight
```

---

## 🔘 Buttons

### Base Button
```html
<button class="button">Button</button>
```

### Variants
```html
<button class="button primary-button">Primary</button>
<button class="button dangerous-button">Danger</button>
<button class="button warning-button">Warning</button>
<button class="button awcss-button">Outline</button>
```

```
.primary-button
.dangerous-button
.warning-button
.awcss-button
.disable-box-shadow
```

---

## 🛒 Cart Button

```html
<button class="cart-button">Add to Cart</button>
```

✔ Responsive padding  
✔ Icon animation  
✔ Hover & focus effects  

Resize easily:
```css
.cart-button {
  --font-size: 1.2rem;
}
```

---

## 🔵 Border Radius

```
.bd-rd-0
.bd-rd-5
.bd-rd-10
.bd-rd-12
.bd-rd-15
.bd-rd-50
```

Example:
```html
<div class="bg-primary bd-rd-15">Rounded Box</div>
```

---

## 🧠 Design Philosophy

- Minimal defaults  
- Strong foundations  
- Easy overrides  
- Readable class names  

AwCSS stays out of your way.

---

## 📄 License

MIT License

---

## 👤 Author

**Awab**  
GitHub: [mrawab](https://github.com/mrawab)  
@Awab Azhari CSS Framework

---

<div align="center">

⭐ Star the repo if you like it  
🚀 Built with passion & clean CSS  

</div>