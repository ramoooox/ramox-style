````markdown
<div align="center">

  <img src="./rx.png" alt="Ramox UI Logo" width="180" />

  # Ramox UI v5.1

  **The Ultra-Flat, Precision Design System for Next.js**

  <p>
    <a href="#">
      <img src="https://img.shields.io/badge/VERSION-5.1.1-black?style=for-the-badge&logo=npm" alt="Version" />
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/LICENSE-MIT-blue?style=for-the-badge" alt="License" />
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/STYLE-PILL%20SHAPE-success?style=for-the-badge" alt="Style" />
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/SIZE-LIGHTWEIGHT-orange?style=for-the-badge" alt="Size" />
    </a>
  </p>

  <p>
    Ramox UI is a zero-runtime React component library designed for <b>Cloudflare Pages</b>.<br/>
    It features a <b>"Flat Precision"</b> aesthetic with matte finishes and fully rounded corners.
  </p>

  <br/>

</div>

---

## ✨ Features at a Glance

| Feature | Description |
| :--- | :--- |
| **🚀 Zero Runtime** | Styles are injected efficiently without heavy CSS-in-JS overhead. |
| **💊 Pill Shaped** | Every element (Buttons, Inputs, Modals) features smooth `9999px` corners. |
| **🌑 Auto Theme** | Automatically syncs with OS Dark/Light mode preferences. |
| **🎨 Flat Precision** | Zero shadows. Zero 3D effects. Just pure, precise borders. |
| **🔤 Font Agnostic** | Inherits your app's font family automatically. |
| **📱 Mobile First** | Optimized touch targets and removed Webkit tap highlights. |

<br/>

## 📦 Installation

Get started instantly via NPM:

```bash
npm install @ramox/rx-style
````

*(Optional) Install icons for full compatibility:*

```bash
npm install lucide-react
```

<br>

## 🔨 Quick Usage

Import components directly. No CSS import required.

```tsx
import React from 'react';
import { Button, Card, Input, Note, Tag } from '@ramox/rx-style';
import { Zap } from 'lucide-react';

export default function App() {
  return (
    <div style={{ padding: 40, fontFamily: 'sans-serif' }}>
      <Card>
        <div style={{ display: 'flex', justifyContent: 'space-between', marginBottom: 20 }}>
           <h2>Welcome</h2>
           <Tag icon={<Zap size={12}/>}>v5.1</Tag>
        </div>

        <Note>This is a completely flat design system.</Note>
        
        <div style={{ margin: '20px 0' }}>
          <Input placeholder="Enter your email..." />
        </div>

        <Button variant="solid" fullWidth onClick={() => alert('Clicked!')}>
          Get Started
        </Button>
      </Card>
    </div>
  );
}
```

<br>

## 🧩 Components Catalog

\<div align="center"\>

| **General** | **Data Entry** | **Feedback** | **Display & Media** |
| :--- | :--- | :--- | :--- |
| `Button` | `Input` | `Modal` | `Card` |
| `Tag` | `Textarea` | `Drawer` | `Table` |
| `Badge` | `Select` | `Alert` | `Timeline` |
| `StatusDot` | `Switch` | `Toast` | `Chart` |
| `Note` | `Checkbox` | `Skeleton` | `Glass` |
| | `Radio` | `Loading` | `VideoPlayer` |
| | `Slider` | `Tooltip` | `Avatar` |
| | `Rating` | | `ImageBox` |
| | `FileUploader` | | `CodeSnippet` |
| | `DatePicker` | | |

\</div\>

<br>

## 🎨 Theming & Customization

### 🔤 Typography

Ramox UI is **font-agnostic**. It does not load any fonts to keep the bundle size small. It inherits `font-family` from your body tag.

```css
/* globals.css */
body {
  font-family: 'Inter', 'Vazirmatn', sans-serif;
  -webkit-font-smoothing: antialiased;
}
```

### 🌗 Dark Mode

Dark mode works **out of the box** using CSS `@media (prefers-color-scheme: dark)`.

  * **Light Mode:** White backgrounds, black accents, `#f4f4f5` surfaces.
  * **Dark Mode:** Black backgrounds, white accents, `#18181b` surfaces.

<br>

-----

\<div align="center"\>

**Ramox UI** is open source software licensed as MIT.

\<a href="https://www.google.com/search?q=https://github.com/ramoooox/ramox-style"\>
\<img src="https://www.google.com/search?q=https://img.shields.io/badge/View\_on-GitHub-black%3Fstyle%3Dflat-square%26logo%3Dgithub" alt="GitHub" /\>
\</a\>

\</div\>
