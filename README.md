# Useful HTML Code Snippets ✂️

A curated collection of **clean, modern, and practical HTML snippets** (often with minimal CSS or JavaScript) that you can copy-paste into your projects. Great for quick UI elements, layouts, forms, effects, and more.

Perfect for developers, designers, and beginners who want fast, reusable code without reinventing the wheel.

## ✨ Features

- Pure HTML (or HTML + minimal CSS/JS)
- Responsive & accessible where possible
- Well-commented code
- Easy to understand & modify
- Real-world use cases

## 📑 Table of Contents

- [Buttons](#buttons)
- [Cards](#cards)
- [Forms](#forms)
- [Loading / Spinners](#loading--spinners)
- [Tooltips & Popovers](#tooltips--popovers)
- [Navigation / Menus](#navigation--menus)
- [Text Effects](#text-effects)
- [Miscellaneous](#miscellaneous)
- [Contributing](#contributing)
- [License](#license)

## How to Use

1. Browse the snippets below or in the `/snippets` folder
2. Copy the code block you like
3. Paste it into your project
4. Customize colors, sizes, content as needed

All snippets are in individual `.html` files (or `.md` with code blocks) inside the repository for easy preview.

## Buttons

### Simple Modern Button

```html
<button class="modern-btn">Click Me</button>

<style>
  .modern-btn {
    padding: 12px 24px;
    font-size: 16px;
    font-weight: 500;
    color: white;
    background: linear-gradient(45deg, #6b48ff, #00ddeb);
    border: none;
    border-radius: 50px;
    cursor: pointer;
    transition: all 0.3s ease;
    box-shadow: 0 4px 15px rgba(107, 72, 255, 0.3);
  }

  .modern-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 25px rgba(107, 72, 255, 0.4);
  }

  .modern-btn:active {
    transform: translateY(1px);
  }
</style>
