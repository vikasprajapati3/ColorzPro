
## 🎨 ColorzPro

A modern and responsive color palette generator built with **Tailwind CSS**.

## 🚀 Live Demo

**[Open ColorzPro](https://colorz-pro.vercel.app/)**


## ✨ Features

-   🎨 Generate random color palettes
-   🔒 Lock colors while generating
-   📋 Copy HEX values
-   🌈 Generate shades and tints
-   ⌨️ Press `Space` to generate a new palette
-   📤 Export palettes as CSS
-   📱 Responsive UI
-   ⚡ Fast and lightweight

## 🛠️ Tech Stack

-   **Tailwind CSS** — Primary styling framework
-   **JavaScript** — Color generation and application logic
-   **HTML5** — Application structure
-   **Vite** — Development and build tooling

## 🎨 Tailwind CSS Setup

### 1. Create a Vite project

```bash
npm create vite@latest my-project
cd my-project
npm install

```

Select:

-   **Framework:** Vanilla
-   **Variant:** JavaScript

### 2. Install Tailwind CSS

```bash
npm install tailwindcss @tailwindcss/vite

```

### 3. Configure Vite

Update `vite.config.js`:

```js
import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'

export default defineConfig({
  plugins: [
    tailwindcss(),
  ],
})

```

### 4. Import Tailwind CSS

In your CSS file:

```css
@import "tailwindcss";

```

### 5. Use Tailwind classes

```html
<h1 class="text-4xl font-bold text-blue-600">
  Hello Tailwind CSS
</h1>

```

### 6. Start the development server

```bash
npm run dev

```

### 7. Build for production

```bash
npm run build

```

## 📦 Run ColorzPro Locally

Clone the repository:

```bash
git clone https://github.com/vikasprajapati3/ColorzPro.git
cd ColorzPro

```

Install dependencies:

```bash
npm install

```

Start the development server:

```bash
npm run dev

```

Build the project:

```bash
npm run build

```

## 📤 CSS Export

Export your generated palette as CSS variables:

```css
:root {
  --color-1: #7c3aed;
  --color-2: #2563eb;
  --color-3: #14b8a6;
}

```

## 👨‍💻 Author

**Vikas Prajapati**

GitHub

----------

⭐ **If you like ColorzPro, please consider giving the repository a star!**
