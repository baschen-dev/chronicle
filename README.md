# Chronicle

A journal for Android whose **data model is data**. You create a notebook, define what kinds of
thing it keeps track of and what fields each of them carries, then write. Mentioning something in a
note creates its codex entry; the codex filters on the fields you defined.

Nothing in the app knows what a *race*, a *due date* or a *quest* is. An Earthdawn campaign, a D&D
table and a work log with projects and tasks are three vocabularies, and the app holds all three
because it holds none of them.

Website: <https://chronicle.dev.baschen.is>

## This repository

The website and the **public issue tracker**. The app's source is not here.

- **Something is broken, or missing** — [open an issue](https://github.com/abaschen/chronicle/issues).
  Say which version you are on (Settings shows it) and what you expected instead.
- **Privacy** — [English](https://chronicle.dev.baschen.is/privacy.html) ·
  [Français](https://chronicle.dev.baschen.is/confidentialite.html)

## The site

Four static files and an `img/` directory, served by GitHub Pages from `master`. No build step, no
dependencies: edit the HTML, push, done. `style.css` is shared by the two landing pages; the two
policy pages inline their own copy of the same variables so that they stay standalone documents.

Screenshots are downscaled from real emulator captures — see `img/` and the generator noted in the
app repository's `docs/PLAY.md`.
