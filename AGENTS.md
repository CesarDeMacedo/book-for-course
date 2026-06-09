# Repository Guidelines

## Project Structure & Module Organization

This repository is a Markdown-based book project. The current source files are:

- `Vegan-Bodybuilding-Nutrition-Over-50-Manuscript.md`: full manuscript draft.
- `Vegan-Bodybuilding-Nutrition-Over-50-Outline.md`: planning outline and chapter blueprint.
- `AGENTS.md`: contributor and agent guidance.

Keep manuscript content in the manuscript file and planning notes in the outline file. If adding research notes, drafts, or assets later, prefer clear top-level folders such as `notes/`, `drafts/`, `sources/`, and `assets/`.

## Build, Test, and Development Commands

There is no build system or package manager configured. Work directly in Markdown.

Useful local checks:

- `Get-Content .\Vegan-Bodybuilding-Nutrition-Over-50-Manuscript.md | Measure-Object -Word`: count manuscript words.
- `Select-String -Path .\*.md -Pattern "TODO|TBD|placeholder"`: find unfinished markers.
- `git diff -- *.md`: review Markdown changes, if this folder is later initialized as a Git repository.

## Writing Style & Naming Conventions

Use clear Markdown headings with one `#` title per major document. Keep chapter headings consistent, for example `# Chapter 3: Protein After 50`. Use short paragraphs, direct instructional language, and plain English suitable for active beginners over 50.

Prefer ASCII punctuation unless editing existing non-ASCII text. Use descriptive file names in Title-Case or kebab-case, ending in `.md`.

## Testing & Review Guidelines

Before finalizing edits, check for:

- All chapter and appendix headings still present.
- No `TODO`, `TBD`, or placeholder text.
- Nutrition and medical claims remain cautious and do not promise diagnosis, treatment, or cures.
- Source notes are preserved for later citation review.

For substantial changes, re-read the affected chapter end to end for flow, repetition, and consistency with the outline.

## Commit & Pull Request Guidelines

No Git history is currently available in this folder. If Git is initialized later, use concise imperative commits such as `Add supplement appendix` or `Revise protein chapter`.

Pull requests should include a short summary, list of changed files, reason for the change, and any sections that need expert nutrition or medical review.

## Agent-Specific Instructions

Do not overwrite the manuscript with generated text unless explicitly requested. Preserve the outline as the planning source of truth. When making factual nutrition edits, keep claims conservative and flag items that require professional review before publication.
