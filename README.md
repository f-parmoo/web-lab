## 🌙 Dark Mode Toggle

This project includes a dark mode feature.

### How it works

- A button in the header toggles between light and dark themes
- JavaScript listens for button clicks
- It adds/removes a `data-theme="dark"` attribute on the `<body>`

### Styling

- Default styles = light theme
- Dark theme styles are applied using:

```css
body[data-theme="dark"] {
  /* dark styles */
}