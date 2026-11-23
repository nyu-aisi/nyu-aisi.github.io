# nyu-aisi.github.io
Website for NYU AI Safety Initiative

## Pages

- `index.html`: the homepage.
- `seminar/index.html`: the seminar page, published at `/seminar/`.

To list a talk, edit `seminar/index.html`. Add a row to the semester's table
and an article below it containing the title, speaker, and description or
abstract. Give each article a unique `id`, point the row's talk link to that
`#id`, and use matching unique heading IDs for `aria-labelledby`. Update the
visible date/time and the `<time datetime>` value; times are local to New York.

The Fall 2026 schedule and descriptions are grouped in the `fall-2026`
section. When adding another semester, this whole section can be moved to an
archive page and linked from the seminar page.

Both pages use embedded CSS and need no build step.
