# 🎨 Amazing AwCSS @0.0.03

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/mrawab/awcss?style=social)](https://github.com/mrawab/awcss-docs/stargazers)

### A lightweight, modern CSS utility framework  
**Clean • Minimal • Customizable**

Build fast, clean interfaces with simple utility classes and zero JavaScript.

[Getting Started](#-getting-started) •
[Utilities](#-utilities) •
[Buttons](#-buttons) •
[Forms](#forms) •
[Typography](#%EF%B8%8F-typography)

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

#### Html Local Use
```html
<link rel="stylesheet" href="awcss.css">
```

#### Html Online Use
```html
<link rel="stylesheet" href="[https://mrawab.github.io/awcss-docs/awcss/awcss.css](https://edyou-study.github.io/awcss-docs/awcss/awcss.css)">
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
<div class="primary-border">Box</div>
```

default to 2px solid

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

unit : px

``` css
.radius-0
.radius-5
.radius-10
.radius-12
.radius-15
.radius-50 /* 50% */
.radius-10-15
.radius-15-25
.radius-15-10
.radius-25-15
```

Example:
```html
<div class="bg-primary radius-15">Rounded Box</div>
```

---
## Forms
1/ Login Example copy and paste : 

```html
 <form class="login-form-basic">
      <h2>Login</h2>

      <!-- Username input example -->
      <div class="input-container validate">
        <div class="container-info">
          <label for="username">Username</label>
          <input
            type="text"
            id="username"
            minlength="3"
            maxlength="100"
            required
          />
          <i class="fa-solid fa-user"></i>
        </div>
        <p class="alert-text">invalid username</p>
      </div>

      <!-- Password input example -->
      <div class="input-container validate">
        <div class="container-info">
          <label for="password">Password</label>
          <input
            type="password"
            id="password"
            minlength="3"
            maxlength="20"
            required
          />
          <i class="fa-solid fa-key"></i>
        </div>
        <p class="alert-text">invalid password</p>
      </div>

      <!-- login button -->
      <input type="submit" value="Login" />
      <div class="text-helper">
        <a href="#">forgot password?</a>
        <a href="/examples/signup.html">create a new account</a>
      </div>
    </form>
```

---

2/ Signup Example copy and paste : 

```html
 <form class="signup-form-basic">
      <h2>Sign Up</h2>

      <!-- Username input example -->
      <div class="input-container validate">
        <div class="container-info">
          <label>Username</label>
          <input type="text" required minlength="3" maxlength="20" />
          <i class="fa-solid fa-user"></i>
          <p class="alert-text">invalid username</p>
        </div>

       <!-- Email input example -->
      </div>
      <div class="input-container validate">
        <div class="container-info">
          <label>Email</label>
          <input type="email" required />
          <p class="alert-text">invalid email</p>
          <i class="fa-solid fa-message"></i>
        </div>
      </div>

       <!-- Password input example -->
      <div class="input-container validate">
        <div class="container-info">
          <label>Password</label>
          <input type="password" required minlength="8" maxlength="20" />
          <i class="fa-solid fa-key"></i>
          <p class="alert-text">invalid password</p>
        </div>

       <!-- Password Confirm input example -->
      </div>
      <div class="input-container validate">
        <div class="container-info">
          <label>Conform Password</label>
          <input type="password" required minlength="8" maxlength="20" />
          <i class="fa-solid fa-key"></i>
          <p class="alert-text">invalid password</p>
        </div>
      </div>

      <!-- Button input example -->
      <input type="submit" value="Sign Up" />
      <div class="text-helper">
        <a href="/examples/login.html"
          >already have an account?<span> login</span></a
        >
      </div>
    </form>
```

additional info :
- You can use in body tag to center the form to view:
``` html
<body class="center-form">
```

``` css
body.center-form
```

- you add vaildation for input by using validate :
``` html
 <div class="input-container validate">
```

``` css
.input-container.validate
```

- all used awcss classes:

``` css
.center-form
.login-form-basic
.signup-form-basic
.input-container.validate
.alert-text
.text-helper
```

- for now icons are imported ffrom font awesome using:
```html
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet"/>
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
