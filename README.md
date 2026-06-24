# TUSK Clothing 🖤

A premium dark-themed clothing e-commerce website built with pure HTML, Tailwind CSS, and vanilla JavaScript. Designed for modern city style — sharp, minimal, and fast.

![Tusk Clothing Preview](preview.png)

---



## ✨ Features

- **Hero section** with full editorial layout and seasonal campaign copy
- **Brand story panel** ("Read Me") with product identity tags — Premium Fabrics, Minimal Design, Everyday Luxury
- **Featured products grid** — Signature Jacket, Linen Shirt, Utility Trousers with hover zoom effect
- **City Collection banner** — Limited release spotlight with best sellers
- Sticky navigation with blur backdrop
- Smooth scroll between sections
- Fully responsive across mobile, tablet, and desktop
- Zero JavaScript frameworks — pure vanilla JS

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic page structure |
| Tailwind CSS (CDN) | Utility-first styling & responsive layout |
| Google Fonts | Playfair Display (display) + Inter (body) |
| Vanilla JavaScript | Lightweight interactivity |
| Unsplash | Editorial fashion imagery |

---

## 📁 Project Structure

```
tusk-clothing/
└── index.html        # Single-file site — all markup, styles & scripts
```

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/tusk-clothing.git

cd tusk-clothing

# Open directly in browser
open index.html

# Or serve locally
python -m http.server 8000
# → http://localhost:8000
```

No build step. No dependencies to install. Just open and go.

---

## 🗂️ Sections

| Section | Description |
|---|---|
| **Hero** | Seasonal campaign headline + Signature Drop editorial card |
| **Read Me** | Brand story with identity tags |
| **Featured Apparel** | 3-column product grid with hover effects |
| **City Collection** | Limited release banner + best seller highlights |
| **Footer** | Social links (Instagram, Email) |

---

## 🎨 Design Tokens

| Token | Value |
|---|---|
| Background | `#050505` |
| Surface | `stone-900` |
| Text primary | `#f4efe8` |
| Text muted | `stone-400` |
| Display font | Playfair Display |
| Body font | Inter |
| Border | `white/10` |
| Border radius | `2rem` (cards), `9999px` (buttons) |

---

## 🧭 How to Use

### 🔁 Customize the Brand Name
The brand name **TUSK** appears in the `<header>` and footer. Replace it with your own brand:
```html
<!-- In <header> -->
<a href="#" class="font-display text-2xl tracking-[0.3em]">YOUR BRAND</a>

<!-- In <footer> -->
<p>© 2026 Your Brand. Crafted for everyday confidence.</p>
```

---

### 🖼️ Swap Product Images
Each product card uses an Unsplash image URL. Replace the `src` with your own image:
```html
<img src="YOUR_IMAGE_URL" alt="Product name" class="h-full w-full object-cover" />
```

---

### 🛍️ Add or Edit Products
Each product is an `<article class="card ...">` block inside the `#products` section. Copy and paste this template to add a new one:
```html
<article class="card overflow-hidden rounded-[1.5rem] border border-white/10 bg-stone-900">
  <div class="aspect-[3/4] overflow-hidden bg-stone-800">
    <img src="YOUR_IMAGE" alt="Product name" class="h-full w-full object-cover" />
  </div>
  <div class="p-6">
    <h3 class="text-lg font-semibold uppercase tracking-[0.25em]">PRODUCT NAME</h3>
    <p class="mt-2 text-sm text-stone-400">Short product description.</p>
    <div class="mt-4 flex items-center justify-between">
      <span class="text-sm text-stone-300">$00</span>
      <button class="text-sm uppercase tracking-[0.25em] text-white/90 hover:text-white">Add</button>
    </div>
  </div>
</article>
```

---

### ✏️ Update Hero Copy
The hero headline and subtext are in the first `<section>` tag:
```html
<h1 class="font-display text-5xl ...">Your headline here.</h1>
<p class="mt-6 ...">Your subtext here.</p>
```

---

### 🔗 Update Social Links
Social links are in the `<footer>`. Replace `href="#"` with your real URLs:
```html
<a href="https://instagram.com/yourbrand">Instagram</a>
<a href="mailto:hello@yourbrand.com">Email</a>
```

---

### 🎨 Change the Accent Colors
Colors are controlled via Tailwind classes throughout the file. The key ones to swap:

| Element | Current Class | Change to |
|---|---|---|
| Muted text | `text-stone-400` | e.g. `text-zinc-400` |
| Card background | `bg-stone-900` | e.g. `bg-neutral-900` |
| Primary button | `bg-white text-black` | Any color combo |



---

> © 2026 Tusk Clothing. *Crafted for everyday confidence.*
