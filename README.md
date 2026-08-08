# h3pdesign.github.io

The creative developer portfolio for h3pdesign.

**[Visit the live portfolio →](https://h3pdesign.github.io/)**

> Software with a point of view.
>
> Apps, systems, and field notes made with care.

This site is the broader practice around a collection of independent Apple apps, field notes, photography, open-source tools, and developer infrastructure. It is intentionally an index rather than a duplicate of each project’s dedicated website.

## What is represented

- Native Apple software, including Neon Vision Editor, GitBird, Lingua Latina, and Metrics Data
- Writing, photography, and place-based notes through Voyages and other publishing channels
- Public repositories, data-quality tooling, and developer infrastructure
- Documentation, support, release links, and selected project context

## Design direction

The site is built around a quiet, editorial interface:

- Responsive light and dark modes
- Multiple color palettes with keyboard-visible focus states
- Responsive AVIF/WebP project imagery with explicit dimensions
- Automatic latest-release messaging sourced from GitHub Releases
- Asset files organized under [`assets/`](assets/)

## Local preview

This is a static site with no build step required. From the repository root, run any local HTTP server, for example:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Repository structure

```text
index.html          Portfolio page and interactive behavior
styles.css          Base layout and typography
portfolio-media.css Theme, media, responsive, and component styles
assets/             Icons, screenshots, previews, and responsive variants
```

## Related destinations

- [Creative portfolio](https://h3p.me)
- [App documentation and releases](https://apps-h3p.com/)
- [GitHub profile](https://github.com/h3pdesign)
- [Developer portfolio repository](https://github.com/h3pdesign/h3pdesign.github.io)

## License

The site content and visual assets are personal portfolio material. Refer to individual project repositories for their respective source and license terms.
