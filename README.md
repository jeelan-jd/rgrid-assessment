# Rgrid Assessment - Frontend Development

## 📖 Overview
This project is a frontend implementation of the **Rgrid Assessment** design provided in Figma.  
The goal of this task is to recreate the design with **pixel-perfect accuracy**, ensuring **responsiveness**, **scalability**, and following **modern frontend best practices**.

Figma Design: [Rgrid Assessment Figma](https://www.figma.com/design/UeSheSlrv7M4BhVYlH4c7K/Rgrid-Assessment?node-id=1-1238&t=DvAXn6JdBGF6uZMx-0)

---

## 🚀 Features
- Pixel-perfect implementation of the Figma design.
- Responsive across **desktop, tablet, and mobile**.
- Semantic **HTML5** structure with accessibility in mind.
- Built using **Bootstrap 5.3** utility classes and components.
- Integrated **Swiper.js** for sliders.
- Reusable design system (typography, spacing, and colors kept consistent).
- Clean and maintainable folder structure.

---

## 🛠️ Tech Stack
- **HTML5**
- **CSS3**
- **Bootstrap 5.3**
- **Swiper.js** (for sliders)
- **IcoMoon** (for custom icons)

# Rgrid Assessment - Frontend Development

## 📖 Overview
This project is a frontend implementation of the **Rgrid Assessment** design provided in Figma.  
The goal of this task is to recreate the design with **pixel-perfect accuracy**, ensuring **responsiveness**, **scalability**, and following **modern frontend best practices**.

🔗 Figma Design: [Rgrid Assessment Figma](https://www.figma.com/design/UeSheSlrv7M4BhVYlH4c7K/Rgrid-Assessment?node-id=1-1238&t=DvAXn6JdBGF6uZMx-0)

---

## 🚀 Features
- 🎯 Pixel-perfect implementation of the Figma design  
- 📱 Responsive across **desktop, tablet, and mobile**  
- ♿ Semantic **HTML5** structure with accessibility in mind  
- ⚡ Built using **Bootstrap 5.3** utility classes and components  
- 🎞️ Integrated **Swiper.js** for sliders  
- 🧩 Reusable design system (consistent typography, spacing, and colors)  
- 🗂️ Clean and maintainable folder structure  

---

## 🛠️ Tech Stack
- **HTML5**
- **CSS3**
- **Bootstrap 5.3**
- **Swiper.js** (for sliders)
- **IcoMoon** (for custom icons)

---

## 📂 Project Structure

```bash
html/
│── css/
│   ├── main.css              # Main stylesheet (imports other styles)
│   ├── swiper-bundle.min.css # Swiper slider styles
│   ├── bootstrap.min.css     # Bootstrap 5.3 styles
│   ├── icon.css              # Custom icons (IcoMoon)
│   ├── theme.css             # Theme-related styles
│   └── style.css             # Project-specific custom styles
│
│── fonts/    # Custom fonts (IcoMoon outputs here)
│── images/   # Images and assets
│── js/       # JavaScript (Swiper.js + custom scripts)
│── index.html # Main entry point


---

## 🎨 CSS Import Details
The **`main.css`** file is the entry point for styles.  
It imports all required stylesheets in the correct order:

```css
@import "../css/swiper-bundle.min.css";
@import "../css/bootstrap.min.css";
@import "../css/icon.css";
@import "../css/theme.css";
@import "../css/style.css";