# AOS (Animate On Scroll) Library

[AOS (Animate On Scroll)](https://michalsnik.github.io/aos/) is a lightweight JavaScript library that enables you to animate elements as you scroll down, up, or across a web page. It’s widely used to add engaging, attention-grabbing animations to websites with minimal setup.

## Key Features

- **Easy to Use:** Simple HTML data attributes to trigger animations.
- **Variety of Animations:** Fade, slide, zoom, flip, and more.
- **Highly Customizable:** Control animation duration, delay, offset, and easing.
- **Responsive:** Works seamlessly on desktop and mobile devices.
- **Performance Optimized:** Animations only trigger when elements enter the viewport.

## Installation

You can install AOS via CDN, npm, or yarn.

**CDN:**
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" />
<script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
```

**npm:**
```bash
npm install aos --save
```

## Usage

1. **Include AOS CSS and JS** in your project.
2. **Initialize AOS** in your JavaScript:
   ```js
   AOS.init();
   ```
3. **Add data attributes** to your HTML elements:
   ```html
   <div data-aos="fade-up">
     <!-- Content to animate -->
   </div>
   ```

## Customization

You can customize AOS globally:
```js
AOS.init({
  duration: 1200, // Animation duration in ms
  offset: 200,    // Offset (in px) from the original trigger point
  once: true,     // Whether animation should happen only once
});
```

## Useful Links

- [AOS Documentation & Demos](https://michalsnik.github.io/aos/)
- [GitHub Repository](https://github.com/michalsnik/aos)

