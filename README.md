# 🎨 Rotating Conic Gradient Box

This project demonstrates a smooth **rotating conic gradient animation** using pure **HTML and CSS**. It showcases modern CSS features like custom properties, the `@property` rule, and the `conic-gradient()` function — all without JavaScript.

Perfect for learning advanced CSS animations and visual effects!

---

## ✨ Features

- 🌀 Pure CSS conic gradient animation
- 💡 Uses `@property` to animate a CSS variable
- 🎯 Centered layout using CSS Grid
- 📐 Fully responsive with `vmin` sizing and `aspect-ratio`
- 🔥 No JavaScript needed!

---

## 📸 Preview

rotation.png 

---

## 🛠 Technologies

- HTML5
- CSS3 (`@property`, `conic-gradient`, `keyframes`, CSS Grid)

---

## 🧪 How It Works

- A CSS custom property `--gradient-angle` is animated from `0deg` to `360deg`
- `@property` is used to allow smooth animation of the angle
- The gradient background is defined using `conic-gradient(from var(--gradient-angle), ...)`
- The div spins forever using `@keyframes` and `animation`

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/kalsol17/CSS-Gradient-Rotation-Effect.git
