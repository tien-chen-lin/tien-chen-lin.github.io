# Website revision — 30 October 2026

*Updated 30 October 2026: reconciled the public research overview with the 27 October IMB plan and Constitution v0.5; redesigned the site around the independent biological question and documented contributions.*

## Scientific sources

- `Taiwan/AS-IMB_Application/AS_IMB_2026_10_16_Editable_MPRG_CV_MASTER/IMB_plan_clarity_revised_2026-10-27.docx`: current application realization, including the two restrictions, culture–tissue comparison, molecular route, and longer-term compartment reorganization.
- `Research_proposal/00_Programme_Governance/00_Master_Research_Programme_Constitution_CURRENT.md`: governing v0.5 scientific framing. Preserved its early tissue-compatibility track; the October application places the substantive tissue comparison in years 3–5.
- `Research_Accomplishments_and_Publications_AS-IMB_2026-10-20.docx` and `04_CV_AS-IMB_2026.docx` in the same application package: contribution statements, independent initiation of MOZART1, collaboration building, teaching dates, and supervision.
- Existing website data and links: preserved current appointment, email, ORCID, CV PDF, code repositories, and publication bibliography.

The public site is a selective overview. The application documents, referee details, institutional fit paragraphs, and internal strategy are not copied into the published assets.

## Changes that strengthen candidacy

1. Lead with a memorable biological question: “How does an axon keep its identity?”
2. Explain the conceptual step from initial selection to persistence and reassignment. The published oscillator is a foundation, rather than the independent program's headline.
3. Present three first-author contributions directly below the opening. Describe personal contributions with evidence from the application rather than journal names alone.
4. Show how spatial perturbation, longitudinal imaging, quantitative analysis, and biochemical reconstruction form a coherent route to mechanism. Keep future experiments in future tense.
5. Make project initiation, experimental leadership, supervision, and course coordination visible. Correct Bonn EM5 coordination to 2023–2025.
6. Describe group culture and project ownership with concrete mentoring experience. State clearly that group establishment and recruitment are prospective.
7. Keep the CV and research code one click away. Retain the existing CV PDF, which was already modified before this task.

## Visual direction

Warm paper, dark ink, teal for the selected axon, ochre for the competing neurite, a restrained serif paired with a readable sans serif, and a small amount of monospaced annotation. An original accessible SVG illustrates the scientific question and experimental sequence; it is explicitly schematic and presents no invented measurements.

The design reflects the style expressed in the application and working preferences: precise, mechanism-oriented, thoughtful, and direct. This is an editorial interpretation rather than a personality assessment. Ruled sections replace repeated rounded panels. The homepage progresses from question to evidence to future program to investigator and group culture. Dark mode, mobile navigation, keyboard focus, and reduced-motion support remain available. Research content is visible without JavaScript.

## Useful next additions when available

- An approved microscopy still or short movie from the published work, with a precise caption and permission to reuse. The current hero is a conceptual schematic; the research page retains a labeled schematic animation.
- An accepted independently led or corresponding-author output, when its publication status is confirmed. The 2015 first/co-corresponding review is already in the publication list; no prospective authorship is advertised as achieved.
- Confirmed group affiliation, recruitment details, and funding after appointment. Avoid advertising an existing laboratory or open posts prematurely.
- A public research-summary PDF only if an outward-facing version is prepared and approved; do not publish the full application plan by default.

## Delivery and checks

Retain Jekyll, Jekyll Scholar, existing URLs, and GitHub Pages deployment. Local revisions do not require registering a new hosted Site or migrating the repository. Build and inspect the rendered pages, relative links, responsive layout, navigation, theme toggle, search, and publication filter. Publishing continues through the repository's `source` branch workflow.

### Verification completed

- Local-preview and production-mode Jekyll builds passed.
- Checked all 9 rendered HTML pages: local asset/link targets and section fragments resolved, with no escaped HTML blocks or duplicate IDs.
- Browser review covered desktop and mobile breakpoints, light/dark themes, mobile menu, publication filtering, and search for the new research terminology. No browser console errors were reported in the reviewed session.
- Expanded the existing search index beyond its previous 200-word cutoff so later research sections are searchable; validated the generated JSON.
- Confirmed no private `.docx` application documents entered the built output. Internal revision notes remain excluded by the existing `docs` exclusion.
- `git diff --check` passed. The pre-existing modification to `papers/Tien-Chen-Lin-CV.pdf` was left intact.
- Changes remain local and uncommitted. No GitHub push or production deployment was performed.

### Publication authorization — 30 October 2026

The user subsequently authorized pushing the completed revision to the existing GitHub repository and its `source` branch. The local-only status above records the initial handoff. The pre-existing CV PDF modification is excluded from this website revision commit.

### Media and profile restoration — 30 October 2026

Restored the visibility lost during the initial redesign. Professional profiles (Google Scholar, ORCID, GitHub, LinkedIn, ResearchGate) now share one compact text-link component on the homepage biography and across site footers. The current hero, palette, typography, navigation structure, and research narrative are retained.

All four retained schematic animations are grouped in a responsive two-column gallery after the main Research narrative. The previous single embedded animation is moved into this gallery rather than duplicated. A clearly dated 2022 NYCU lecture follows, credited as co-presented with Frank Bradke, using the existing click-to-load YouTube facade. The player styling now uses the site's teal palette; keyboard activation loads the lecture once. No video autoplays on page load. Captions describe schematics without asserting permanent axonal identity. Research section navigation and homepage/footer links expose the media.

Restoration validation: local and production Jekyll builds passed; all rendered local links, media assets, and fragments resolved. Verified two gallery columns on desktop, one on mobile with no horizontal overflow, restored homepage/footer profile links, paused initial video state, keyboard-controlled local playback, and creation of the YouTube iframe through keyboard activation.
