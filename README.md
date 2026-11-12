# LP Select

A responsive, vinyl-inspired website for LP Select, a barbershop quartet in
Albuquerque, New Mexico. Built with plain HTML and CSS, without a build step,
third-party scripts, or external fonts.

## Preview locally

From the repository directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000. Stop the server with Ctrl+C.

## Publish on GitHub Pages

1. In the repository's **Settings > Pages**, choose **GitHub Actions** as the source.
2. Merge the website into `main`. The **Deploy to GitHub Pages** workflow publishes
   the site automatically; it can also be run manually from the Actions tab.
3. Find the published URL in the workflow's deployment environment or Pages settings.

All asset paths are relative, so the site works at the repository's Pages path
(`/webpage-lp-select/`) as well as a custom domain. The workflow publishes only
`index.html`, `styles.css`, and `assets/`.

## Update content

- Edit text, navigation, and booking links in `index.html`.
- Update palette, typography, and responsive layouts in `styles.css`.
- The supplied quartet logo is at `assets/lp-select-logo.jpg`.
- Booking links open the visitor's email application and send inquiries to
  `lpselectquartet@gmail.com`; the site does not collect or store submissions.
- Quartet members and voice parts are listed in the about section.
- Add recordings and performance dates when those details are available.
