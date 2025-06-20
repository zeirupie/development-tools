# FontAwesome.com

[FontAwesome.com](https://fontawesome.com) is one of the most popular icon toolkits on the web, offering thousands of icons in a consistent and flexible design system. It supports both free and Pro icons, works with web fonts or SVGs, and is compatible with all major frontend frameworks.

## Key Features

- **Massive Icon Library:** Access to over 2,000 free icons and more than 20,000 icons with Font Awesome Pro.
- **Multiple Styles:** Includes **Solid**, **Regular**, **Light** (Pro), **Duotone** (Pro), and **Brands**.
- **Framework Friendly:** Integrates seamlessly with **React**, **Vue**, **Angular**, and standard HTML.
- **Web Fonts or SVGs:** Choose between traditional font-based icons or modern SVGs with JavaScript control.
- **Kits & CDN Support:** Use kits from the Font Awesome dashboard for flexible delivery and updates.
- **Custom Uploads (Pro):** Upload your own SVG icons when using Font Awesome Pro.

## Installation

You can use Font Awesome in a few different ways depending on your tech stack:

### 1. Use CDN (Quick Start)

Add this line to your HTML `<head>`:

```html
<!-- Free version -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
```

Then use icons in your HTML:

```html
<i class="fa-solid fa-camera"></i>
<i class="fa-brands fa-github"></i>
```

### 2. Install via NPM (SVG + JavaScript method)

Recommended for React, Vue, and other JavaScript-based frameworks.

#### Core Installation

```bash
npm install --save @fortawesome/fontawesome-svg-core
npm install --save @fortawesome/free-solid-svg-icons
```

#### For React

```bash
npm install --save @fortawesome/react-fontawesome
```

**React Example:**

```jsx
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome';
import { faCamera } from '@fortawesome/free-solid-svg-icons';

function MyComponent() {
  return <FontAwesomeIcon icon={faCamera} className="text-blue-600" />;
}
```

#### For Vue (Font Awesome 6)

```bash
npm install @fortawesome/vue-fontawesome
```

Then:

```js
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faCamera } from '@fortawesome/free-solid-svg-icons'
import { library } from '@fortawesome/fontawesome-svg-core'

library.add(faCamera)

app.component('font-awesome-icon', FontAwesomeIcon)
```

Use in Vue template:

```html
<font-awesome-icon :icon="['fas', 'camera']" />
```

### 3. Use Font Awesome Kit (CDN + Dashboard)

1. Create a free account at [fontawesome.com/start](https://fontawesome.com/start).
2. Create a Kit.
3. Copy the provided `<script>` tag and place it in your HTML:

```html
<script src="https://kit.fontawesome.com/your-kit-id.js" crossorigin="anonymous"></script>
```

This method automatically includes all your selected icons and styles, and allows for custom icon uploads (Pro).

## License

- **Free Icons:** Open-source under the **Creative Commons Attribution 4.0 License (CC BY 4.0)**.
- **Pro Icons:** Available with a paid subscription, licensed for commercial and extended use.

## Additional Features

- **Icon Search Tool:** Quickly find and preview icons at [fontawesome.com/icons](https://fontawesome.com/icons)
- **Figma Plugin:** Official Font Awesome plugin for designers.
- **Custom Styles & Themes:** Adjust icon sizes, colors, and animations with utility classes or CSS.
- **Official Kits & CDN Support:** Optimize loading by using kits personalized to your project.

---
