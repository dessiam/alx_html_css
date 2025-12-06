# Responsive HTML/CSS Web Page — From Scratch

This project consists of building a fully responsive, accessible, and pixel-perfect web page **from scratch**, based on the provided designer mockup. No external libraries, frameworks, or JavaScript are allowed. The goal is to accurately reproduce both the **desktop** and **mobile (≤ 480px)** designs using semantic HTML and modern CSS techniques.

---

## 🎯 Objectives

* Recreate the designer’s layout as closely as possible
* Implement the project using **only HTML and CSS**
* Apply accessibility best practices (semantic tags, alt attributes, labels, contrasts, etc.)
* Make the entire page responsive, including switching to the mobile design at **480px or less**
* Respect all visual specifications such as colors, spacing, icons, button behavior, and structure
* Keep the page content centered with a max width of **1000px**

---

## 🛑 Restrictions

To ensure the project strengthens core front-end skills, the following rules apply:

* ❌ **No external CSS frameworks** (e.g., Bootstrap, Tailwind)
* ❌ **No JavaScript** (interactive behavior must be CSS-only)
* ❌ **No CSS libraries** (e.g., Animate.css)
* ❌ **No preprocessors** unless allowed by your school (SCSS/SASS)

You must rely strictly on raw HTML and CSS.

---

## ✔️ Requirements & Specifications

### Layout & Styling

* The design must match the provided mockup as closely as possible
* All content must be centered with:

  * **max-width: 1000px**
  * automatic horizontal margins

### Interaction Styles

* **Hover/active states for links:**
  `color: #FF6565`
* **Hover/active states for buttons:**
  `opacity: 0.9`

### Responsiveness

* A complete mobile version must appear when the screen width is **480px or below**
* CSS media queries must be used
* Elements must stack or resize according to the mockup

### Accessibility

* Use semantic HTML (`header`, `main`, `section`, `nav`, `footer`, etc.)
* Provide `alt` text for images
* Link buttons must be actual `<a>` tags or `<button>` when appropriate
* Labels must be associated to form inputs
* Maintain readable contrast

---

## 📁 Project Structure (Recommended)

```
project/
│── index.html
│── README.md
└── css/
    └── style.css
└── images/
    └── (all assets from the mockup)
```

---

## 🧪 How to View

Simply open **index.html** in any modern browser (Chrome, Firefox, Edge, Safari).

No installation is needed since the project uses only static files.

---

## 💡 Tips for Implementation

* Use **Flexbox** and **CSS Grid** to reproduce the designer layout
* Use **media queries** for responsive transitions

  ```css
  @media screen and (max-width: 480px) {
      /* Mobile layout here */
  }
  ```
* Use a consistent spacing system to match the design
* Test the page at multiple widths (480px, 768px, 1000px, full desktop)

---

## 📸 Mockup

The project must look exactly like the provided desktop and mobile screenshots.


Just tell me!
