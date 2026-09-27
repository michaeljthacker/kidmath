# Math Tools

A collection of small, simple math tools published with GitHub Pages.

Each tool lives in its own folder and can be opened directly in the browser. No framework, build process, or package manager required.

## Tools

- [Partial Quotients](./Partial-Quotients/) — Works through long division using the partial quotients method.

## Structure

```text
/
├── index.html
├── README.md
└── Partial-Quotients/
    └── index.html
```

The root `index.html` is the homepage.

Each tool lives in its own directory with an `index.html` file, so a tool at:

```text
Partial-Quotients/index.html
```

is available at:

```text
/Partial-Quotients/
```

## Adding a Tool

1. Create a new folder.
2. Add the tool as `index.html` inside that folder.
3. Add a link to the root `index.html`.

For example:

```text
Fractions/
└── index.html
```

Then add:

```html
<li><a href="./Fractions/">Fractions</a></li>
```

to the homepage.

## Publishing

The site is designed to be served directly by GitHub Pages.

In the GitHub repository:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the appropriate branch, usually `main`.
4. Select `/ (root)` as the folder.
5. Save.

That's it. No build script required.
