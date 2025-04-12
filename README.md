# 🐉 404.css

404.css is an unknown modern CSS framework. Implementing issues gone 404. SMILING DX!

## QUICKSTART

### 1. Installation

Add 404.css to your project using npm or by downloading the files directly:

```bash
# Install via pnpm - COMING SOON!
npm install 404css --save
```

Then include it in your HTML:

```html
<!-- Include locally after download/install -->
<link rel="stylesheet" href="path/to/404.css" />
```

### 2. Basic Setup

Set up your HTML structure with 404.css:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>404.css Project</title>
    <link rel="stylesheet" href="path/to/404.css" />
  </head>
  <body>
    <header>
      <div class="container">
        <h1>Hello 404.css</h1>
      </div>
    </header>

    <main>
      <div class="container">
        <p>Your content here</p>
      </div>
    </main>

    <footer>
      <div class="container">
        <p>Footer content</p>
      </div>
    </footer>
  </body>
</html>
```

### 3. Container Layout

Use the container class for responsive layouts:

```html
<div class="container">
  <!-- Content is automatically centered and responsive -->
  <p>Container restricts width based on breakpoints</p>
</div>
```

### 4. Grid System

Create responsive grids using the built-in grid system:

```html
<div class="container">
  <div class="grid">
    <div>Column 1</div>
    <div>Column 2</div>
    <div>Column 3</div>
    <div>Column 4</div>
  </div>
</div>
```

### 5. Dark/Light Theming

404.css supports automatic dark/light mode based on user preferences. You can also manually set theme:

```html
<!-- Default follows user preference -->
<body>
  <p>Theme follows system preference</p>
</body>

<!-- Force light theme -->
<body data-theme="light">
  <p>Always light theme</p>
</body>

<!-- Force dark theme -->
<body data-theme="dark">
  <p>Always dark theme</p>
</body>
```

### 6. Typography

Basic typography is already styled:

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>

<p>Paragraph text with <strong>bold</strong> and <em>italic</em> elements.</p>

<blockquote cite="Author Name">This is a blockquote with automatic styling</blockquote>
```

### 7. Components

404.css includes basic components with minimal styling:

```html
<!-- Buttons -->
<button>Standard Button</button>
<a class="button">Link Button</a>

<!-- Form elements -->
<input type="text" placeholder="Text input" />
<textarea placeholder="Textarea"></textarea>

<!-- Navigation -->
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

### 8. Utility Classes

Some utility classes for common needs:

```html
<!-- Layout utilities -->
<div class="flex">Flex container</div>
<div class="flex_col">Flex column</div>
<div class="gap_md">With medium gap</div>

<!-- Text utilities -->
<p class="uppercase">UPPERCASE TEXT</p>
<p class="text_center">Centered text</p>
<p class="text_pretty">Text with pretty wrapping</p>

<!-- Visibility utilities -->
<div class="visually_hidden">Hidden from view but available to screen readers</div>
<div class="print_hidden">Hidden when printing</div>
```

### 9. Aspect Ratio System

Use the aspect ratio system for media:

```html
<div class="aspect ratio_16x9">
  <img src="image.jpg" alt="Description" />
</div>

<div class="aspect ratio_4x3">
  <img src="image.jpg" alt="Description" />
</div>

<div class="aspect ratio_1x1">
  <img src="image.jpg" alt="Description" />
</div>
```

## File Structure

404.css uses a layered approach for better organization:

```
404.css (main file)
├── omg/0reset.css (reset styles)
├── omg/1vars.css (CSS variables)
├── omg/2theme.css (theme customizations)
├── omg/3base.css (base element styles)
├── omg/4layout.css (layout systems)
├── omg/5components.css (UI components)
├── omg/6states.css (state styling)
└── omg/7utilities.css (utility classes)
```

## License

404.css is released under the MIT License.
