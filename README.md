# Shaders | An Introduction (inspired by XorDev)

A visually stunning, educational landing page for artists and beginners to explore the intersection of mathematics, code, and real-time shader art. Each section features a unique, animated "oily orb" and clear explanations of the math and art behind shaders.

---

## Features

- **Apple-inspired, responsive UI/UX**
- **Animated WebGL orbs** with unique parameters for each section
- **Educational content** for artists new to shaders
- **LaTeX/MathJax** for beautiful math rendering
- **Burger menu navigation** (always accessible, touch-friendly)
- **Hero section** with call-to-action
- **Dark mode** by default
- **Smooth scrolling** and premium spacing
- **Mobile-first design**

---

## Table of Contents
- [Features](#features)
- [Section Breakdown](#section-breakdown)
- [Key Definitions](#key-definitions)
- [How to Run](#how-to-run)
- [Technologies Used](#technologies-used)
- [Credits & Resources](#credits--resources)
- [Customization Tips](#customization-tips)

---

## Section Breakdown

### Hero Section
- Large headline: _Discover the Art & Math of Shaders_
- Subtitle and call-to-action button
- Large animated orb as a visual centerpiece

### 1. Introduction
- Welcome message
- Explains the purpose of the page and what shaders are

### 2. What is a Shader?
- Definition of shaders
- Difference between vertex and fragment shaders
- How shaders are used in art and graphics

### 3. Math Behind the Orb
- Introduction to Signed Distance Functions (SDF)
- LaTeX-rendered formula for a sphere SDF
- Explanation of raymarching

### 4. Color Theory & Palettes
- How color is generated in shaders
- Use of HSL (Hue, Saturation, Lightness)
- Tips for experimenting with color

### 5. Lighting & Highlights
- Phong reflection model
- Lighting parameters and their artistic impact
- LaTeX-rendered lighting formula

### 6. Animating the Orb
- Using time to animate parameters
- Example: pulsing the orb with a sine function
- Encouragement to experiment

### 7. Raymarching Explained
- Step-by-step explanation of raymarching
- How SDFs enable efficient rendering
- LaTeX-rendered raymarching formula

### 8. Performance & Optimization
- Tips for making shaders run smoothly
- Balancing quality and speed
- List of optimization strategies

### 9. Artistic Tips
- Creative advice for shader artists
- Encouragement to experiment and break the rules

### 10. Try It Yourself!
- How to experiment with the code or use online editors
- Challenge prompts for users

### 11. Resources
- Curated list of external links for further learning

---

## Key Definitions

- **Shader:** A small program that runs on the GPU to control the appearance of graphics (pixels, vertices, etc.).
- **Fragment Shader:** A shader that computes the color of each pixel.
- **Vertex Shader:** A shader that manipulates the position of points in 3D space.
- **Signed Distance Function (SDF):** A function that returns the shortest distance from a point to a surface; negative inside, positive outside.
- **Raymarching:** A rendering technique that steps along a ray using the SDF to find surfaces efficiently.
- **Phong Reflection Model:** A lighting model that simulates ambient, diffuse, and specular highlights.

---

## How to Run

1. **Clone or download this repository.**
2. **Open `index.html` in any modern web browser** (Chrome, Safari, Firefox, Edge).
3. **Enjoy the interactive orbs and educational content!**

_No build tools or server required._

---

## Technologies Used
- **HTML5 & CSS3** (modern, responsive, flexbox, media queries)
- **JavaScript (vanilla)**
- **WebGL** (for orb animation)
- **MathJax** (for LaTeX math rendering)

---

## Credits & Resources
- [XorDev](https://www.x.com/XorDev)
- [The Book of Shaders](https://thebookofshaders.com/)
- [Shadertoy](https://www.shadertoy.com/)
- [Inigo Quilez (iq)](https://iquilezles.org/)
- [Desmos Graphing Calculator](https://www.desmos.com/calculator)

---

## Customization Tips
- **Change orb parameters** in the JavaScript to create new visual styles.
- **Edit section content** in `index.html` to add your own explanations or challenges.
- **Add new sections** for more advanced topics or interactive demos.
- **Tweak the CSS** for different color palettes or layout styles.

---

Enjoy exploring the world of shaders and creative coding! 
