# Personal academic website

Plain HTML and CSS. No build step, no dependencies, no framework.
Hosted free on GitHub Pages.

## Files

| File | What it is |
|---|---|
| `index.html` | Home page: bio, headshot, contact. The only tab switched on right now. |
| `research.html` | Job market paper, working papers, work in progress. Hidden. |
| `teaching.html` | Courses, evaluations. Hidden. |
| `style.css` | All styling, shared by every page |
| `files/` | CV, papers, headshot |

## The nav

Only **Home** is switched on. Research, Teaching and CV sit commented out in the `<nav>`
block of all three HTML files. To switch a tab on, uncomment its line in **all three**
files so the nav is the same everywhere.

`research.html` and `teaching.html` are still in the repo while hidden, so their URLs work
if someone types them directly. Nothing sensitive is on them, but clear the `[BRACKETS]`
before switching them on.

## Filling it in

Anything in `[SQUARE BRACKETS]` is a placeholder. Search for `[` to find
what is left. Nothing breaks if you leave one in, it just shows up on the page,
so clear them out before you share the link.

## Checklist

- [ ] Add `files/cv.pdf`, then uncomment the CV line in the nav of all three pages
      and the download buttons in `index.html`
- [ ] Switch on the Research tab once its placeholders are cleared
- [ ] Switch on the Teaching tab once its placeholders are cleared
- [ ] Job market paper: uncomment the block in `research.html`, the sentence in
      `index.html`, and the PDF button in `index.html`
- [ ] Working papers and works in progress
- [ ] Conference presentations
- [ ] Teaching history
- [ ] Google Scholar and LinkedIn links, or delete that row
- [ ] Add `files/jmp.pdf` once the draft is ready to circulate

## Updating

Edit the HTML, commit, push. The live site updates in about a minute.

To change colors, fonts, or spacing site-wide, edit the `:root` variables at the
top of `style.css`. Dark mode colors are in the `@media (prefers-color-scheme: dark)`
block right below.

## One rule worth following

When you update a document, keep the same filename (`files/cv.pdf`, not
`files/cv_oct2026_v3.pdf`). Any link you have already put on an application,
a working paper, or the UGA directory page keeps working.
