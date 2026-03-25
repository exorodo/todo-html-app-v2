## html-skeleton
### Requirements
1. Valid HTML5: doctype, lang="en", charset, viewport meta, title
2. CSS reset: `*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }`
3. `:root` CSS variables: --bg, --text, --accent, --border, --radius
4. Body: system font stack, bg, color, min-height 100vh
5. `.app` container: max-width 600px, centered, padding
6. `<h1>Todo App</h1>` with accent color
7. Placeholders: `#input-area`, `#todo-list` (ul, list-style none), `#filters`
8. Empty `<script>` tag for future JS
### Scenarios
- Given a browser, When opening index.html, Then centered container with heading visible
- Given viewport under 600px, When viewing, Then container fills width with padding
