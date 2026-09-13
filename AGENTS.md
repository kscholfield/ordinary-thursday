# Ordinary Thursday: Instructions for AI Agents

## Project purpose

Ordinary Thursday is Keith Scholfield's personal website and durable archive. Its
primary purpose is to preserve and organize Keith's writing, photographs, and
personal record. It is not primarily a commercial, marketing, or
audience-building project.

## Technical principles

- Build a simple static site with straightforward HTML and CSS and only the
  minimum JavaScript needed for a requested feature.
- Prefer boring, durable web technology over technical complexity.
- Do not introduce a framework, database, CMS, build system, package manager,
  or third-party dependency unless Keith explicitly requests it.
- Keep the repository self-contained so that GitHub remains the durable source
  of truth. Do not make essential content or functionality depend on an
  external service.
- Use semantic HTML, progressive enhancement, and accessible interactions.

## Editorial and archival care

- Preserve Keith's writing voice. Do not substantially rewrite his prose unless
  explicitly requested. When only formatting or publishing a piece, limit
  edits to clearly necessary corrections and call them out.
- Never delete existing writing or photographs without explicit instruction.
  If content must be superseded, retain the source material and add the new
  version alongside it unless directed otherwise.
- Treat dates, locations, titles, captions, and bylines as part of the archival
  record; do not invent missing details.
- Keep the distinction between published pieces and drafts clear. Material in
  `freedom-is-not-the-finish-line/chapters/` should be treated as draft work
  unless Keith says otherwise.

## Design and experience

- Keep the design restrained, readable, timeless, and photography-friendly.
- Prioritize comfortable typography, clear hierarchy, generous space, useful
  alt text, keyboard access, and good behavior across screen sizes.
- Do not add social-media-style engagement features, advertising, tracking,
  popups, newsletter nags, or algorithmic content features unless specifically
  requested.
- Optimize images appropriately for web use while preserving high visual
  quality. Never overwrite the only original: keep source images in the
  category's `images/originals/` directory and derived web-ready files in its
  `images/web/` directory.

## Content and navigation

- Keep navigation labels and destinations consistent throughout the site.
- When adding, moving, or renaming content, update the relevant category index,
  chronological index, navigation, and cross-links in the same change.
- Thursdays form a chronological visual journal. Preserve each entry's
  photograph, date, location, and optional reflection without filling in
  absent information.
- Keep files within the most relevant content directory described in
  `README.md`; shared presentation assets belong in `assets/`.

## Completion checklist

- Verify all changed internal links and image paths.
- Check basic site functionality and keyboard navigation at narrow and wide
  viewport sizes before completing a website change.
- Confirm that no existing prose or photographs were removed unintentionally.
- Keep changes focused, understandable without special tooling, and documented
  when they alter the repository organization.
