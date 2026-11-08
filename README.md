# BAIR at CoRL 2026

A standalone schedule webpage for Berkeley Artificial Intelligence Research participation at the Conference on Robot Learning, November 9–12, 2026, in Austin, Texas.

## Files

- `index.html`: complete webpage, including all content, CSS and JavaScript.
- `affiliation-audit.csv`: the prior 48 main-track/workshop paper decisions.
- `late-breaking-affiliation-audit.csv`: all 39 LBR entries, including pending verification.
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

Snapshot updated November 8, 2026: 33 main-track papers, 4 confirmed late-breaking-results posters, plus workshop appearances and papers. Confirmed session chairs include Ken Goldberg (Monday's Negar Mehr keynote), Koushil Sreenath (Tuesday Oral O7) and Negar Mehr (Wednesday Spotlight S6).

- Official program: https://www.corl.org/program
- BAIR faculty: https://bair.berkeley.edu/people/faculty
- Compiled paper and poster index (unofficial): https://jaywu109.github.io/papers/corl-2026/
- Individual paper and workshop sources are linked throughout the page.

Workshop schedules may change. Claire Tomlin's workshop block is explicitly marked approximate because it was inferred from the relative agenda. Claire Tomlin shares an approximately 2:55–3:25 PM block with Michael Lutter at Hilton Austin, Salon E, inferred from the workshop’s 2 PM start and relative agenda. Her individual slot is unspecified. Separate demo rosters remain unverified.

## Validation and handoff

Content counts, author-list inclusion, internal anchors and JavaScript syntax were checked during preparation. A full browser test was not available in the originating environment.

Before publication, check search, filters, day navigation, mobile layout, print layout and HTML download in a browser, and confirm any changed conference times.

No license has been assigned in this package. The repository owner should choose the appropriate licensing terms before adding a LICENSE file.

## Paper affiliation review (November 6, 2026)

Include a paper only when at least one author lists UC Berkeley on the paper. Joint affiliations qualify. BAIR membership alone does not establish eligibility. Faculty talks, chairs and other workshop participation remain listed separately.

The revised schedule contains 33 main-conference papers and 5 additional workshop papers (38 unique papers). Eight main-conference papers and one additional workshop paper were excluded for having no UC Berkeley affiliation; one workshop paper is withheld because its paper affiliations could not be verified. See `affiliation-audit.csv` for all 48 decisions and primary sources. The on-page paper affiliation links provide the evidence for retained entries.

This package updates the earlier source archive; it does not update a GitHub repository or deploy a website automatically.

## Late-breaking results review (updated November 8, 2026)

LBR posters run 12:00–1:30 PM CST in Griffin, Level 2, JW Marriott Austin: Agentic Robotics on Monday November 9; Real2Sim2Real on Tuesday November 10. Dates, boards and LBR numbers follow the conference roster supplied by the owner. The final roster entry did not include an LBR number.

Added confirmed Berkeley papers:
- Monday, board 119, LBR 15: Scaling Online Exploration for Robot Agents.
- Monday, board 120, LBR 19: Reconstruct, Practice, Go Real: Guided Self-Improvement for Embodied Agents.
- Monday, board 131, LBR 54: Flip Anything with Agentic Robotics Self-Learning.
- Tuesday, board 122, LBR 26: RoboSimStudio: An Interactive Toolkit for Rapid Real2Sim of Robot Manipulation Tasks.

All four include full author lists. Three have manuscript affiliation sources; Flip Anything is included on explicit schedule-owner confirmation, supported by its official project README listing all three authors at UC Berkeley. Its manuscript remains inaccessible. RPG was already listed in the Thursday workshop, so the updated schedule contains 41 unique papers across all tracks (38 previously listed plus 3 newly introduced titles).

This LBR update is partial: of 39 entries searched, 4 are included (3 manuscript-verified and 1 owner-confirmed with project affiliation evidence), 9 inspected reports have no Berkeley affiliation, and 26 remain pending manuscript verification. Pending does not mean non-Berkeley. Embodied First Exam has a project page naming Berkeley authors, but its manuscript affiliation block could not be retrieved, so it remains withheld. The owner supplied six OpenReview URLs; all six forum pages, PDFs and API records were inaccessible to the browsing tools. These URLs are retained in the LBR audit. The specific inclusion of Flip Anything does not change the inclusion rule for other papers. See the LBR audit for sources and individual limitations.

The schedule preview and this package do not automatically update https://github.com/SimeonOA/bair-at-corl-2026. Upload the source files to that repository to publish these changes.
