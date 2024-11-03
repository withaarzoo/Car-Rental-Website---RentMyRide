# Style Guide

This style guide provides the foundational styles and design elements for your project, including the primary fonts and global color variables.

## Font

The project uses **Poppins** as the primary font, which offers a clean and modern appearance suitable for various content types, and **Squada One** for accent text.

To incorporate these fonts into your project, add the following CSS import to your stylesheet:

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Squada+One&display=swap');
```

### Font Variables

```css
--poppins-font: "Poppins", sans-serif;
--font-family-2: "Squada One", sans-serif;
```

## Global Colors

To maintain a cohesive and visually appealing design, we’ve defined a palette of global color variables. These colors ensure consistency across your project, improving both readability and accessibility.

Add these color variables to the `:root` selector in your CSS file:

```css
:root {
    --main-color: #5a6d8c;          /* Primary color used for branding and main UI elements */
    --second-color: #3f4c65;        /* Secondary color, complements the primary color */
    --text-color: #313949;          /* Main text color, optimized for readability */
    --container-color: #ebeef3;     /* Container background color for sections and cards */
    --bg-color: #f6f7f9;            /* General background color for pages */
    --text-alter-color: #8092b0;    /* Accent text color for muted or secondary information */
}
```

Each color has been carefully selected to ensure visual harmony and legibility:

- **Main Color** (`--main-color`): Primary brand color, used for key components and highlights.
- **Secondary Color** (`--second-color`): Complements the main color, suitable for backgrounds and accents.
- **Text Color** (`--text-color`): Optimized for body text, ensuring high contrast and readability.
- **Container Color** (`--container-color`): Light background color for card-style elements and sections.
- **Background Color** (`--bg-color`): Base background color for overall page structure.
- **Text Accent Color** (`--text-alter-color`): Softer color for secondary text, labels, and less prominent content.

This style guide serves as a reference for creating a consistent and professional user experience across your project. Ensure these styles are applied uniformly for the best results.

---
