# AI Science Editor — Scientific Copy-Editor Skill

A Claude skill for expert copy-editing of scientific writing in life sciences, biology, medicine, and adjacent fields such as public health.

## What it does

The skill lightly polishes scientific text, fixing genuine problems while preserving the author's voice and style. It covers:

- Research papers and journal articles
- Abstracts and conference posters
- Grant proposals
- Technical reports and guidelines
- Figure captions and table titles

## Editing modes

Users can choose from four modes:

1. **Preserve voice** — fix errors only, leave style untouched
2. **Light polish** — fix errors, smooth awkward phrasing, keep voice intact
3. **Moderate edit** — fix errors, restructure sentences, tighten prose
4. **Assertive rewrite** — prioritise clarity above all; rewrite freely

Default is **Light polish**.

## Output format

Returns the edited text followed by an Editing Notes section, grouped by category (Grammar and Clarity, Scientific Terminology, Structure and Flow, Style Notes). Each change is labelled as fixed (✓) or flagged (⚑).

## Language conventions

- British English throughout
- No em-dashes

## Domain coverage

- Life sciences and biology: nomenclature, quantitative language, taxonomy
- Medicine and clinical: causation claims, patient language, abbreviations, dosing
- Abstracts and posters: structure checking, text density
- Figure captions and tables: self-contained descriptions, undefined abbreviations
- References: citation placement and consistency
