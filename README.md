# CB Web App

A modern holding page hosted on GitHub Pages, featuring a filterable link list and a light/dark theme toggle.

**Live site:** [bearduk.github.io/cb-web-app](https://bearduk.github.io/cb-web-app/)

## Features

- **Theme switcher** — toggle between light and dark mode; preference is saved to localStorage and respects `prefers-color-scheme`
- **Filterable links** — real-time text filtering over a list of placeholder link cards
- **Responsive layout** — sticky blurred header, hero section, and card grid that adapts to mobile and desktop
- **No dependencies** — pure HTML, CSS, and vanilla ES5 JavaScript

## Project Structure

```
cb-web-app/
├── index.html          — single-page markup
├── css/style.css       — theming, layout, and responsive styles
├── js/main.js          — theme toggle and link filter (ES5)
├── images/hero.png     — hero banner image
├── favicon.png         — site icon
└── README.md
```

## Running Locally

Open `index.html` directly in a browser, or serve it with any static file server:

```bash
# Python 3
python3 -m http.server 8000

# Node (npx)
npx serve .
```

## Deployment

The site is deployed via GitHub Pages from the `main` branch root. Any push to `main` triggers a rebuild automatically.

## License

MIT
