# M/J Comprehensive Science 2 (2002070) — Interactive Lesson Pages

GitHub-hosted interactive lesson pages for Optima Academy Online's 7th Grade Integrated Science course (M/J Comprehensive Science 2, CPALMS 2002070). These pages are embedded into the Canvas course shell (course id 111) via iframe/link; all graded items (quizzes, assignments, discussions, module wrappers) live natively in Canvas instead, per the `optima-canvas-assignments` deployment split.

## Pages

Live at: https://optimaondemand.github.io/mj-science2-lessons/

## Folder convention

```
weeks/
  wk01/   Week 1 lesson page(s)
  wk02/   Week 2 lesson page(s)
  ...
  wk18/   Week 18 lesson page(s)
```

Each week folder holds that week's interactive lesson HTML file(s). Widget CSS/JS is **inlined directly in each lesson HTML file** rather than split into a per-week `widgets/` subfolder — decided in Stage 2 for simplicity (per `optima-lesson-format`, either is acceptable; inline avoids extra fetch round-trips for a single-page lesson and keeps each week self-contained as one file to review). Applied consistently across all 18 weeks.

## Source of truth

Build content is planned from `04_Handoff/BUILD_MAP.md` and the corrected fragments in `03_Build/fragments/` (see the course project's `00_MASTER_PLAN.md`), not re-derived per lesson.

## Platform note

No ENGAGE-specific terminology appears anywhere in this course's content — VR activities are described in platform-neutral language (session, location, note card, etc.) per a standing project instruction.
