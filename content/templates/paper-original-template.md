---
title: "Paper template (original sample)"
draft: true
build:
  render: never
  list: never
---

## About

This file keeps an **original sample paper page** as a reference template.
It is **not rendered** to the website.

---

## Front matter tips (for this site)

We use `paperStatus` to categorize papers on `/papers/` (not necessarily shown as a badge):

- `paperStatus: published` (Published papers)
- `paperStatus: working` (Working papers)
- `paperStatus: wip` (Work in progress)

`summary` is for a short one-line description that shows up in list views.
If you don't want to show it yet, set `hideSummary: true` and leave `summary: ""`.

For the **paper detail page header**, you can also set:

- `publication`: one-line journal/citation info (optional). You can italicize the journal name with markdown, e.g. `*Journal Name*. 2026. Vol. 1.`
- `externalLink.url` + `externalLink.text`: external link shown as a button (for published papers, button text defaults to `Link`)
- `previousTitle`: previous working title (optional)
- `mediaCoverage`: list of external coverage links (optional)

---

## Download

- [Paper](paper.pdf)
- [Online appendix](appendix.pdf)
- [Presentation slides](slides.pdf)

---

## Abstract

Write your abstract here.

---

## Figure

![Figure preview](paper.png)

---

## Citation

```latex
@article{KEY,
author = {Last, First and Last, First},
year = {2026},
title = {Title},
journal = {Journal},
volume = {1},
number = {1},
pages = {1--10}}
```

---

## Related material

- [Link 1](https://example.com)
