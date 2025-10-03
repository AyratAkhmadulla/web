# Frontend Project Code Review Instructions

## ✅ Review Goals

### 1. BEM Naming
- Ensure CSS class names follow BEM (Block__Element--Modifier) methodology.
- Check for:
  - Only one block per component
  - Elements use `__`
  - Modifiers use `--`
  - No camelCase or snake_case

### 2. Flexbox Usage
- Layouts must use Flexbox wherever possible instead of floats or positioning.
- Look for:
  - `display: flex` or `display: inline-flex`
  - Proper use of `justify-content`, `align-items`, `gap`, etc.

### 3. HTML Best Practices
- Use semantic tags like `<header>`, `<main>`, `<section>`, `<footer>`, etc.
- Avoid excessive use of `<div>` and `<span>`
- Ensure valid HTML structure (one `<h1>`, proper nesting, alt attributes for `<img>`, etc.)

### 4. CSS Best Practices
- Group related styles together
- Avoid ID selectors (`#`)
- Use variables for colors if SCSS is used
- Check for DRY principle (Don’t Repeat Yourself)

### 5. Accessibility
- Use `alt` attributes
- Ensure color contrast is readable
- Use semantic HTML for screen readers

### 6. General Formatting
- Indentation (2 or 4 spaces consistently)
- Use lowercase for HTML tags and attributes
- No unused CSS classes
- No console logs or commented-out code in production

---

## 📋 Review Process

Please review the following files:
- `index.html`
- `style.css`

Return a list of:
- Detected issues
- Suggested improvements
- Lines where issues occur
