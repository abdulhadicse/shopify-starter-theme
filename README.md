# 🛒 Shopify Starter Theme with Tailwind CSS

A modern Shopify Online Store 2.0 theme scaffolded with Tailwind CSS. Lightweight, customizable, and built for speed.

---

## 🚀 Features

- Shopify Online Store 2.0 compliant (JSON templates, dynamic sections)
- Tailwind CSS integrated
- Modular folder structure
- Minimal layout with a clean homepage hero section
- Ready for Theme Editor customization
- Shopify CLI compatible

---

## 🧰 Tech Stack

- **Shopify Liquid**
- **Tailwind CSS** (via PostCSS or CLI)
- **Theme Editor v2** (section-based editing)
- **Shopify CLI** for local development

---

## 🛠️ Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/abdulhadicse/shopify-starter-theme.git
cd shopify-starter-theme
```

2. **Install Dependencies**
```bash
npm install
```

3. **Then build your CSS**
```bash
npx tailwindcss -i ./tailwind/input.css -o ./assets/tailwind.css --watch
```

4. **Connect to Shopify Store and Start Local Development Server**
```bash
shopify login --store your-store.myshopify.com
shopify theme dev
```

---

Let me know if you want to include a `package.json`, `tailwind.config.js`, or example section data too — I can help set that up!


## ✨ Credits

Made with 💙 by [@abdulhadicse](https://github.com/abdulhadicse)  
Powered by Shopify & Tailwind CSS
