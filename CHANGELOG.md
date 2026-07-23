# Changelog

## 0.6.7

- My Plans: gap panel in Refine tab uses section tabs instead of vertical list

## 0.6.6

- My Plans: remove Gaps tab -- gaps live in Refine tab only
- My Plans: Fill this gap shows instruction above feedback textarea, not pre-fills it

## 0.6.5

- My Plans: rename at top of View tab, Edit in Discovery removed, better section matching in Refine pills
- My Plans: gaps column handles old plans without gaps key

## 0.6.4


- My Plans: Gaps tab with section sub-tabs and Fill this gap button (loads gap into Refine tab)

## 0.6.3

- Refine tab: gap panel capped at 200px with scroll so pills and form are always visible

## 0.6.2

- Generate cell: save dialog moved to top of card (above plan content)

## 0.6.1

- Profile cell note: starter/pro options on separate lines for readability

## 0.6.0

- Gap detection: sections.yaml required_evidence converted to structured dicts (sba_loan)
- Gap UX: generate cell shows section-grouped summary, Refine tab groups gaps by section with Fill this gap button
- Plans table gap column shows "N gaps" label
- Profile cell note corrected: starter can set name and description

## 0.5.0

- Profiles: pro users can create multiple named profiles, each with its own locked topics and Drive folder
- Starter users see profile upsell
- Plans scoped to active profile (Drive path: plans/{profile_id}/)
- Auto-save to profiles/{id}.json on topic lock

## 0.4.0

- Plan management rewrite: HTML rendering, explicit save with editable name, full provenance in .meta.json
- My Plans hub: view, export, refine, pivot, re-run from any saved plan
- Plan detail view with rename
- Export and refine cells use plan selector (no longer assume latest)

## 0.3.0

- Header cell changed to markdown (no execution needed)
- Template version aligned to base v0.4.0

## 0.1.0

- Initial release
- Setup, authentication, and basic API usage
