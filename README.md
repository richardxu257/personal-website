# Personal portfolio

A responsive, dependency-free portfolio with About, Research, Projects, and Writings tabs and persistent light/dark mode. The sections intentionally contain no content beyond their headings. No external fonts, analytics, or network dependencies.

## Preview locally

Open `index.html` directly in your browser, or run this command from this folder:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Visit http://127.0.0.1:8000. Press Ctrl+C to stop the server. This server is bound to your own computer.

## Fill in your content

Edit `index.html`. Each section contains a clearly marked comment, for example:

```html
<div class="section-content"><!-- Add your About content here. --></div>
```

Replace the comment with your own HTML. Use paragraphs, headings, lists, images, and links as needed. The other tabs follow the same pattern. Change the header's “Portfolio” wordmark, footer, description, and page title to personalize the site. Update the title in `script.js` as well. Colors and layout are in `styles.css`.

Tab links support direct URLs such as `index.html#research`, browser back/forward, and keyboard navigation with Left/Right arrows, Home, and End. Theme initially follows your system setting, then remembers a manual choice in your browser.

## GitHub storage — without publishing

The source is stored in the private repository https://github.com/richardxu257/personal-website. Keep GitHub Pages disabled while drafting. No deployment workflow is included.

The website has not been deployed.

## Publish later, only when ready

The static files work with GitHub Pages as-is and use relative asset paths, so they support a project repository or a username repository. When you decide to publish, select the repository's branch and root directory in its Pages settings. Check GitHub's current repository visibility and plan requirements before enabling Pages. Enabling Pages makes the website available at its assigned URL; do not enable it while drafting.
