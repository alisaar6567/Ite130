# Vibe — Task Manager (static)

A small, accessible task manager built with semantic HTML, modern CSS, and vanilla JavaScript.

Features
- Add tasks
- Mark tasks as completed
- Delete tasks
- Persisted in `localStorage`
- Responsive and accessible (aria-live, keyboard-friendly, focus styles)

How to open
1. Open `index.html` in your browser (double-click or use a local dev server).

Optional: run a local static server (recommended for some browsers):

```bash
# Python 3
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

Notes on accessibility
- Add/remove/complete actions announce updates via `aria-live` regions.
- Controls are keyboard focusable; `Enter`/`Space` toggles tasks when focused on the text.
- Buttons have descriptive `aria-label`s.

Files
- `index.html` — semantic markup and app shell
- `styles.css` — styling and responsive layout
- `script.js` — app behavior and persistence

- `mdu-ite130.html` — informationssida för studenter på MDU (ITE130) med länk till Vibe-appen

Theme
- The app includes a Dark/Light toggle. The site defaults to Dark mode. The toggle state is saved in localStorage (key `vibe.theme.v1`).

You're all set — open `index.html` in a browser to try it.