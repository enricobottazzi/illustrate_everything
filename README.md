# Illustrate Everything

Interactive illustrations built with Claude, deployed via GitHub Pages.

**Live site**: [enricobottazzi.github.io/illustrate_everything](https://enricobottazzi.github.io/illustrate_everything)

## Structure

```
index.html          ← Gallery homepage (reads manifest.json)
manifest.json       ← List of all illustrations [{title, description, file, date}]
illustrations/      ← Each illustration is a self-contained HTML file
```

## Adding a new illustration

1. Drop the `.html` file into `illustrations/`
2. Add an entry to `manifest.json`
3. Push to `main` — GitHub Pages deploys automatically
