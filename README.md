# sheshisheri-hi.github.io

Personal site for **Sheshi Sheri** — Director, Cloud Application Architecture.

- Live: [https://sheshisheri-hi.github.io/](https://sheshisheri-hi.github.io/)
- GitHub: [https://github.com/sheshisheri-hi](https://github.com/sheshisheri-hi)
- LinkedIn: [https://www.linkedin.com/in/sheshi-sheri-86406615](https://www.linkedin.com/in/sheshi-sheri-86406615)

## GitHub Pages

This is a user Pages site (`username.github.io`). Content is served from the `main` branch at the repository root (`/`).

GitHub typically auto-enables Pages for `*.github.io` repos after the first push. If the site does not appear within a few minutes:

```bash
gh api -X POST repos/sheshisheri-hi/sheshisheri-hi.github.io/pages \
  -f build_type=legacy \
  -f source[branch]=main \
  -f source[path]=/
```

Or in the repo **Settings → Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**.

## Files

| File | Role |
|------|------|
| `index.html` | Single-page site |
| `styles.css` | Dark modern tech styling |
| `README.md` | This file |
