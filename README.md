<div align="right">

**[English](README.md)** · [简体中文](README.zh-CN.md)

</div>

# zhuxin

A résumé and portfolio site in a single HTML file.

<sub>HTML · no build step</sub>

---

## What it is

One self-contained page: profile, projects and contact. No framework, no bundler, no dependencies — open the file and it works.

## What is in the file

- Responsive layout, with a narrow-screen reflow for phones
- Project entries with links and short descriptions
- Dark and light mode via CSS variables, remembered in `localStorage`
- Contact details and links

## Running

Open `index.html`. To serve it:

```bash
python -m http.server
```

## Note

The page was built to be readable on a phone as well as a desktop, which is why the layout reflows to a single column and the long text fields wrap rather than clip.

## License

MIT
