# Ordinary Thursday

Ordinary Thursday is a simple, durable personal website for preserving and
organizing Keith Scholfield's writing, photographs, and personal record. The
site is intended as an archive rather than a commercial, marketing, or
audience-building project.

The repository deliberately starts without a framework, CMS, database, build
system, or third-party dependencies. Future pages should use straightforward
HTML and CSS with minimal JavaScript where it is genuinely useful.

## Repository organization

- `assets/` — shared styles, scripts, and site-wide images
- `essays/` — essays and their images
- `books/` — book-related pages and images
- `freedom-is-not-the-finish-line/` — draft chapters and images for the book in
  development
- `thursdays/` — the chronological visual journal and its photographs
- `travel/` — trip summaries and photographs
- `about/` — biographical material and images

Content categories keep archival source images in `images/originals/` and
web-ready derivatives in `images/web/`. Draft book text belongs in
`freedom-is-not-the-finish-line/chapters/`.

See `AGENTS.md` before making changes. It contains the project's durable
editorial, design, technical, and preservation rules.

## Prototype site

The initial static prototype begins at `index.html`, with section indexes in
`essays/`, `books/`, `thursdays/`, `travel/`, and `about/`. Shared presentation
styles live in `assets/css/site.css`; neutral demonstration images live in
`assets/images/placeholders/` and do not represent archival photographs.

Photographs are displayed with `max-width: 100%` and `height: auto`, without
fixed-height wrappers or forced crops. New archival photographs should retain
explicit intrinsic width and height attributes and follow the originals/web
folder convention above.
