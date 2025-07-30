# Skewed Hover Effect Button

## Overview

**Skewed-Hover-Effect-Button** is a lightweight front-end project that demonstrates a modern and visually engaging button design using CSS. The key feature is a skewed hover animation effect, ideal for use in web interfaces needing interactive, attention-grabbing buttons.

## Preview

![Skewed Hover Effect Button Preview](https://github.com/mihaiapostol14/Skewed-Hover-Effect-Button/blob/3fbc1a53b2e44f9ca593a3168e78899442721a32/assets/preview.gif)

## Features

- **Skewed Hover Animation:** The button displays a dynamic skewed color swipe when hovered, providing a modern UI feel.
- **Responsive Centering:** The demo centers the button using Flexbox, ensuring it’s always positioned attractively regardless of screen size.
- **Minimalist Design:** Clean, dark-themed button with simple styling, making it easily adaptable for various web projects.
- **Separation of Concerns:** HTML, CSS, and JavaScript are separated into their own files for best practices and maintainability.

## Technologies Used

- **HTML5:** Structure for the demo page and the button element.
- **CSS3:** Implements the core skew effect, transitions, and responsive layout.
- **JavaScript (placeholder):** Linked for potential future enhancements (currently empty in the provided code).

## Implementation Details

### CSS Highlights
- `.skew-button` class styles the button with padding, background color, borders, and transition effects.
- The pseudo-element `:before` creates a skewed, colored overlay that transitions from left to right on hover.
- The effect uses `transform: skewX(-30deg)` for the dynamic angle and `transition` for smooth animation.

### HTML Structure
- A single button is rendered in the body.
- The page links to the corresponding CSS and JS files, maintaining modularity.

### Example Usage
Simply hover over the button labeled "Hover Me" to see the skewed red color swipe across the button.

## Potential Use Cases

- Landing pages and hero sections needing eye-catching call-to-action buttons.
- Interactive elements in dashboards, portfolios, or product showcases.
- Component libraries or design systems for modern web applications.

## How to Use

1. Clone or download the repository.
2. Open `html/index.html` in any modern browser.
3. Customize the button text, colors, or transitions in `css/style.css` as desired.

## File Structure

```
Skewed-Hover-Effect-Button/
├── css/
│   └── style.css
├── html/
│   └── index.html
├── js/
│   └── script.js
└── README.md
```

## Customization

- **Color Scheme:** Adjust `background-color` in the `.skew-button:before` selector.
- **Skew Angle:** Change `skewX(-30deg)` for different visual effects.
- **Transition Timing:** Modify `transition` properties for slower or faster animation.

## License

No explicit license found. Please add a license file for open-source or commercial use.

---

Created by [mihaiapostol14](https://github.com/mihaiapostol14)