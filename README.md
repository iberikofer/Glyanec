# 🚀 Glyanec (Test Project)

## 📖 Overview
This is a test project built using **Vanilla HTML and CSS**, with a minimal amount of JavaScript added solely to handle necessary logic and interactive animations. The focus was on writing clean, semantic markup and well-structured, best-practice CSS.

## 🎨 Design Reference
The project was developed based on the following Figma mockup:  
🔗 [Figma Design Link](https://www.figma.com/file/UBkIfuekqFDAJBdq44UzVS)

## ⚠️ Implementation Details & Limitations
Please note that the provided Figma mockup was **incomplete**:
- 🖥️ It contained only the desktop version of the site.
- 🖼️ Several images, icons, and graphical assets were either missing, broken, or not fully exportable.

Because of these limitations:
- **📱 Responsive Design:** I had to independently design and implement the tablet and mobile (phone) versions from scratch. As a result, the responsive layouts and mobile user experience may differ from what the original designer might have envisioned and are my own interpretation of how the site should adapt.
- **✨ Custom Enhancements:** I took the liberty to add various features, animations, and structural changes that were not present in the original mockup to create a more polished, modern, and engaging user experience.

## 💻 Technologies Used
- 🏗️ **HTML5:** Semantic structure, accessibility best practices (ARIA attributes, semantic tags), and responsive meta configuration.
- 💅 **CSS3:**
  - **Layouts:** Advanced **CSS Grid** (multi-column grids, grid tracks, spanning) and **Flexbox** for responsive alignments.
  - **Modern CSS Features:** CSS Custom Properties (Variables), linear gradients, and fluid sizing via `clamp()`, `calc()`, and `minmax()`.
  - **Responsive Web Design:** Mobile-first approach, custom media queries across mobile, tablet, laptop, and Full HD (1920px) desktop breakpoints.
  - **Transitions & Micro-interactions:** Smooth transforms (`scale`, `translate`), cubic-bezier easings, and interactive hover states.
  - **Architecture:** Styles meticulously organized following `rational-order` best practices.
- 📐 **SVG / Vector Graphics:** Scalable vector graphics and optimized SVG sprite composition for pixel-perfect rendering across all screen densities.
- ⚡ **Vanilla JavaScript (ES6+):** Zero external libraries/frameworks; minimal, performant event listeners (with `{ passive: true }`), debounced resize handlers, click-outside detection, and DOM state management for mobile navigation and interactive dropdowns.
- 🔤 **Web Typography:** Google Fonts (`Lato`) with resource preconnection (`preconnect`) and `Proxima Nova` custom font integration.
- 🌿 **Git:** Version control and commit history management.
