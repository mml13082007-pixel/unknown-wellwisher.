# Portfolio Template

## Folder structure

portfolio-template/
- index.html
- css/
  - style.css
- js/
  - script.js
- images/
  - (put your images here)

## How to use

1. Put your HTML code inside `index.html`.
2. Put your CSS code inside `css/style.css`.
3. Put your JavaScript code inside `js/script.js`.
4. Put your images inside `images/`.

## Correct linking

In `index.html`:
```html
<link rel="stylesheet" href="css/style.css">
<script src="js/script.js" defer></script>
```

In `css/style.css` for images:
```css
background-image: url("../images/your-image.jpg");
```

Or in HTML:
```html
<img src="images/your-image.jpg" alt="My image">
```

## Notes

- Use only relative links (no leading `/`).
- Do not use spaces in folder names if possible, but this template uses a folder name without spaces.
- Open `index.html` in the browser after saving changes.
