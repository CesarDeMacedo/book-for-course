# Repository Guidelines

## Project Structure & Module Organization

Markdown book project files:

- `Vegan-Bodybuilding-Nutrition-Over-50-Manuscript.md`: full manuscript draft.
- `Vegan-Bodybuilding-Nutrition-Over-50-Outline.md`: planning outline and chapter blueprint.
- `AGENTS.md`: contributor and agent guidance.

Keep manuscript content in the manuscript file and planning notes in the outline. Put future research or assets in `notes/`, `sources/`, or `assets/`.

## Build, Test, and Development Commands

There is no build system. Work directly in Markdown.

Useful checks:

- `Get-Content .\Vegan-Bodybuilding-Nutrition-Over-50-Manuscript.md | Measure-Object -Word`: count words.
- `Select-String -Path .\*.md -Pattern "unfinished|draft marker"`: find drafting notes.
- `git diff -- *.md`: review Markdown changes.

## Writing Style & Naming Conventions

Use clear Markdown headings with one `#` title per major document. Keep chapter headings consistent, for example `# Chapter 3: Protein After 50`. Use short paragraphs and direct English for active beginners over 50.

Prefer ASCII punctuation. Use descriptive `.md` file names.

## Content Scope Requirements

Preserve the expanded scope. When editing protein sources, recipes, grocery lists, or meal templates, keep traditional vegan options such as seitan where appropriate and add gluten-free alternatives such as tofu, tempeh, edamame, pea protein, soy protein, lentils, beans, quinoa, amaranth, buckwheat, and certified gluten-free oats.

Maintain the anti-inflammatory layer: omega-3 sources, flax, chia, walnuts, algae EPA/DHA, berries, greens, ginger, turmeric, garlic, and colorful plants. Treat exercise as a health pillar covering resistance training, myokines, insulin sensitivity, joint stiffness, bone density, and cautious hormone context.

## Testing & Review Guidelines

Before finalizing edits, check:

- All chapter and appendix headings still present.
- No temporary drafting markers or unfinished notes.
- Nutrition and medical claims remain cautious and do not promise diagnosis, treatment, or cures.
- Gluten-free alternatives remain paired with wheat/seitan-based options.
- Anti-inflammatory nutrition, myokines, arthritis-aware movement, and hormonal health are preserved where relevant.
- Source notes are preserved for later citation review.

For substantial changes, re-read the affected chapter for flow, repetition, and outline consistency.

## Commit & Pull Request Guidelines

Use concise imperative commits such as `Add supplement appendix`. PRs should include a summary, changed files, rationale, and sections needing expert review.

## Agent-Specific Instructions

Do not overwrite the manuscript unless explicitly requested. Preserve the outline as the planning source of truth. Keep nutrition, exercise, inflammation, gluten-free, and hormone claims conservative, and flag items needing professional review.
