# BAIR at CoRL 2026

A standalone schedule webpage for Berkeley Artificial Intelligence Research participation at the Conference on Robot Learning, November 9–12, 2026, in Austin, Texas.

## Files

- `index.html`: complete webpage, including all content, CSS and JavaScript.
- `.nojekyll`: serves the files directly if GitHub Pages is used.
- `.gitignore`: excludes common local editor and operating-system files.

There are no dependencies, package installs, build commands, environment variables, credentials, or backend services.

## Preview

Open `index.html` in a modern browser. The schedule content is present in the HTML and remains readable without JavaScript. JavaScript adds search, session filters, printing and HTML download. External links open paper/project and conference pages.

## Publish

Serve `index.html` from the website root, or put it in the desired directory on an existing static website. No build step is required. For a static hosting service, use this directory as the publish directory.

This source package does not configure automatic deployment. Creating or uploading the repository does not itself publish the website. A hosting maintainer may enable GitHub Pages or another static host separately.

## Update the schedule

Edit `index.html` directly:
- The introduction is in `p.intro`.
- Day sections use `day-1` through `day-4`.
- Each session has a `session` class and a session-type `data-kind` attribute.
- Each paper has a `paper` class and a `data-paper` identifier.
- Full author lists are in `p.authors`.
- Papers presented in multiple sessions appear more than once. Update every matching occurrence.
- Update the displayed revision date and aggregate counts when appropriate.

The introduction intentionally retains the owner's wording, including "next week." Review that relative date before publication.

All displayed times are Austin local time, CST (UTC−6). Oral and spotlight times are session windows, not individual presentation times.

## Content and sources

Snapshot reviewed November 6, 2026: 41 main-conference papers, plus workshop appearances and papers. Confirmed session chairs include Ken Goldberg (Monday's Negar Mehr keynote), Koushil Sreenath (Tuesday Oral O7) and Negar Mehr (Wednesday Spotlight S6).

- Official program: https://www.corl.org/program
- BAIR faculty: https://bair.berkeley.edu/people/faculty
- Compiled paper and poster index (unofficial): https://jaywu109.github.io/papers/corl-2026/
- Individual paper and workshop sources are linked throughout the page.

Workshop schedules may change. Claire Tomlin's workshop block is explicitly marked approximate because it was inferred from the relative agenda. Detailed late-breaking-results and separate demo rosters remain unverified.

## Validation and handoff

Content counts, author-list inclusion, internal anchors and JavaScript syntax were checked during preparation. A full browser test was not available in the originating environment.

Before publication, check search, filters, day navigation, mobile layout, print layout and HTML download in a browser, and confirm any changed conference times.

No license has been assigned in this package. The repository owner should choose the appropriate licensing terms before adding a LICENSE file.
