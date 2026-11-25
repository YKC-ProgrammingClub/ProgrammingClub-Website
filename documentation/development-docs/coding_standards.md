# Coding Standards

## General
- Use **2 spaces** for indentation (matching `.editorconfig`).
- Use clear, descriptive names in `kebab-case` for files and CSS classes, and `camelCase` for JS variables and functions.
- Keep changes scoped to your assigned files/task so you don't overwrite someone else's work.

## HTML
- Use semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<button>`).
- Include `alt` text on images (`alt=""` only for purely decorative images).
- Avoid inline styles (`style="..."`) unless strictly dynamic.

## CSS
- Reuse shared CSS variables and layout classes before writing duplicate rules.
- Test layouts at both desktop and mobile widths (avoid fixed widths that cause horizontal overflow).

## JavaScript
- Write clean, readable ES6+ (`const` by default, `let` when reassigned, avoid `var`).
- Never put private keys, passwords, or email credentials in client-side code.
- Handle empty/missing data gracefully so the page doesn't break.