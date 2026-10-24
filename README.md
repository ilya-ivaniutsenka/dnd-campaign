# dnd-campaign

This is my dnd-campaign project. It is a template for building a D&D story.

## Structure

```
docs/                  ← the site itself
├── index.html         ← root: redirects straight to en/
├── style.css          ← one shared stylesheet for every page and every language
├── en/                ← English (default language)
│   ├── index.html
│   ├── high.city.html
│   ├── lower.city.html
│   ├── directory.html
│   ├── races.html
│   ├── elements.html
│   └── mechanics.html
├── ru/                ← Russian, the same 7 files under the same names
└── de/                ← German, the same 7 files under the same names
```

The file names are **identical** in all three folders — the language switcher relies
on it: from `en/races.html` the link `../de/races.html` leads to the same page in
German. If you rename a file, rename it in all three languages at once.
