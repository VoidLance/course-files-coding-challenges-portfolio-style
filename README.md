# Nova Creative Portfolio

A static, five-page portfolio website for Nova, a fictional web application designer. The project recreates a portfolio concept using HTML, CSS, JavaScript, and locally stored images.

## Why this project is useful

- Provides a complete example of a multi-page portfolio, with Home, About, Portfolio, Services, and Contact pages.
- Includes responsive styling, shared navigation, portfolio project cards, and a contact form interface.
- Keeps the site simple to explore and modify: there is no build step or package installation.

The contact form is a front-end demonstration only; it does not send messages to a server.

## Project contents

- [`Style/Website-recreated/`](Style/Website-recreated/) — the five HTML pages, stylesheet, and JavaScript.
- [`Style/Images/`](Style/Images/) — the logo, hero, contact, and portfolio images used by the site.
- [`Style/Designs/`](Style/Designs/) — page design references.
- [Design summary](Style/Documentation/Summary%20of%20page%20design.txt) — the original page requirements and design notes.
- [`Style/Fonts/`](Style/Fonts/) — a bundled Roboto font archive; the pages currently use Inter from Google Fonts.

## Get started

You only need a web browser. To serve the site locally with Python 3, run this command from the repository root:

```bash
python3 -m http.server 8000 --directory Style/Website-recreated
```

Then open [http://localhost:8000](http://localhost:8000). The home page is `index.html`; use the navigation to visit the other pages. Press `Ctrl+C` in the terminal to stop the server.

Google Fonts and Font Awesome are loaded from external services, so an internet connection is needed for those fonts and icons. The website's images and CSS are stored in the repository.

## Get help

For questions or to report a problem, [open an issue](https://github.com/VoidLance/course-files-coding-challenges-portfolio-style/issues). The [design summary](Style/Documentation/Summary%20of%20page%20design.txt) also explains the intended page structure.

## Maintainers and contributions

The website credits its designer as Nova. For repository ownership and current contributors, see the [GitHub contributors page](https://github.com/VoidLance/course-files-coding-challenges-portfolio-style/graphs/contributors).

Contributions are welcome. Open an issue to discuss a proposed change, or submit a pull request with a clear description of what it updates. There is no separate `CONTRIBUTING.md` file at this time.
