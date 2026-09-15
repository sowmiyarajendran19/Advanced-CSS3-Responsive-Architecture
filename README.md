# Personal Portfolio Website

A modern, responsive personal portfolio website developed as part of my **Web Development Internship at Thiranex**.

This project builds upon the semantic HTML5 portfolio from Task 1 and enhances it using advanced CSS3 techniques, responsive layouts, CSS Grid, Flexbox, CSS custom properties, and a dynamic light/dark theme.

---

## 📌 Task 2: Advanced CSS3 & Responsive Architecture

### Objective

Transform the semantic portfolio website into a visually appealing, fully responsive website that adapts smoothly across mobile, tablet, and desktop screen sizes.

---

## 🎯 Key Objectives

* Implement CSS Grid for two-dimensional layouts.
* Use Flexbox for component-level alignment.
* Follow a mobile-first responsive design approach.
* Create reusable CSS custom properties.
* Implement a dynamic light/dark mode.
* Create responsive layouts for different screen sizes.
* Improve the overall visual appearance and user experience.

---

## ✨ Key Features

### 🧩 CSS Grid

CSS Grid is used for the project section to create a responsive two-dimensional layout.

The project cards automatically adjust based on the viewport:

* Mobile → 1 column
* Tablet → 2 columns
* Desktop → 3 columns

---

### ↔️ Flexbox

Flexbox is used for localized component alignment, including:

* Navigation
* Skill badges
* Button alignment
* Flexible content arrangement

The `flex-wrap` property allows components to adapt to smaller screen sizes without overflowing.

---

### 📱 Mobile-First Responsive Design

The website follows a mobile-first approach.

The base styles are designed for mobile devices and are progressively enhanced using CSS media queries.

Responsive breakpoints include:

```text
600px  → Tablet
900px  → Desktop
1200px → Large Desktop
```

The website has been designed to work across:

* Mobile phones
* Tablets
* Laptops
* Desktop monitors

---

## 🎨 CSS Custom Properties

CSS variables are used to create a consistent and maintainable design system.

Example:

```css
:root {
    --background: #f8fafc;
    --surface: #ffffff;
    --text: #172033;
    --primary: #6366f1;
}
```

Variables are used for:

* Background colors
* Text colors
* Primary colors
* Borders
* Shadows
* Border radius
* Transitions
* Container sizes

This makes it easier to modify the overall design without c
