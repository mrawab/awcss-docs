# 🎨 Amazing AwCSS @0.0.02

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

#### Html Use
```html
<link rel="stylesheet" href="https://mrawab.github.io/awcss/awcss/awcss.css">
```

---
## Start Pain free

Awcss do the resets for you

```css
*,
::after,
::before {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  line-height: 1.6;
  -webkit-tap-highlight-color: transparent;
  -moz-tap-highlight-color: transparent;
  -ms-tap-highlight-color: transparent;
  scroll-behavior: smooth;
  outline: none;
  border: none;
}
```

---
## 🎨 CSS Variables

Customize the entire theme from one place:

```css
:root {
  --primary-color: #3878c3;
  --secondary-color: #ff5722;
  --text-color: #0d0c0c;
  --text-color-white: rgb(246, 246, 246);
  --text-muted: #666;
  --bg-color: #fefefe;
  --bg-muted: #666;
  --border-color: #ddd;
  --success-color: #28a745;
  --warning-color: #ffc107;
  --danger-color: #dc3545;
  --info-color: #17a2b8;
  --highlight-color: #184476;
  --highlight-alt: #3878c3;
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
.normal-text
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

allow you to disable users select

```
.no-user-select
```
allow you to disable box shadow

```
.disable-box-shadow
```

### Text Colors
```
.primary-text
.secondary-text
.success-text
.warning-text
.danger-text
.info-text
.highlight-text
.highlight-text-alt
```

---

## 🧱 Borders

```html
<div class="border border-primary">Box</div>
```

```
.primary-border
.secondary-border
.success-border
.warning-border
.danger-border
.info-border
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
<button class="button primary">Primary</button>
<button class="button dangerous">Danger</button>
<button class="button warning">Warning</button>
<button class="button awcss">Outline</button>
```

```
.button.primary
.button.dangerous
.button.warning
.button.awcss
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

## ➤ Send Button

```html
<button class="send-button"></button>
```

✔ Responsive padding  
✔ Icon animation  
✔ Hover & focus effects  

Resize easily:
```css
.send-button {
  --font-size: 1.2rem;
}
```
Change text easily:
```css
.send-button::before {
  content: "My Button before click";
}
.send-button::after {
  content: "My Button after click";
}
```
---

## 🔵 Border Radius

```
.radius-0
.radius-5
.radius-10
.radius-12
.radius-15
.radius-50
.radius-10-15
.radius-15-25
.radius-15-10
.radius-25-15
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
Repository: [AwCss](https://github.com/mrawab/awcss)  
@Awab Azhari CSS Framework

---

<div align="center">

⭐ Star the repo if you like it  
🚀 Built with passion & clean CSS  

</div>
