# README Replacement Notes

<p align="center">
  <a href="./README.md">Main README</a> ·
  <a href="./README_REWRITE_PROMPT.md">Rewrite Prompt</a> ·
  <a href="./README_REPLACEMENT_NOTES.md">Replacement Notes</a>
</p>


---

## Document Role

This file explains how to deploy and maintain the linked README system.

- Main profile file: [README.md](./README.md)
- Rewrite engine prompt: [README_REWRITE_PROMPT.md](./README_REWRITE_PROMPT.md)
- This deployment guide: [README_REPLACEMENT_NOTES.md](./README_REPLACEMENT_NOTES.md)

---

## Why this rewrite is stronger

The old README creates visual impact, but it overuses decorative language and repeated animated/stat components. That weakens technical credibility for recruiters, maintainers, and engineering communities.

The new README shifts the signal from:

```text
Decoration -> Claims -> Effects
```

to:

```text
Positioning -> Projects -> Evidence -> Improvement path
```

## How the 3 Files Connect

```text
README.md
  -> public-facing profile
  -> links to rewrite prompt
  -> links to replacement notes

README_REWRITE_PROMPT.md
  -> reusable AI prompt
  -> regenerates README.md
  -> points back to README.md and notes

README_REPLACEMENT_NOTES.md
  -> deployment checklist
  -> explains why and how to replace the old README
  -> points back to README.md and prompt
```

## Required Repository Layout

Put all three files in the root of the public profile repository:

```text
haooah01/
├── README.md
├── README_REWRITE_PROMPT.md
└── README_REPLACEMENT_NOTES.md
```

Do not put the prompt and notes in another folder unless you also update the links.

## What to do after replacing README.md

1. Put these files in the public repository named exactly `haooah01`.
2. Make sure the main file is named `README.md`.
3. Keep `README_REWRITE_PROMPT.md` and `README_REPLACEMENT_NOTES.md` in the same root folder.
4. Open `README.md` on GitHub and click each navigation link.
5. Pin up to 6 repositories on your GitHub profile.
6. For each pinned repo, add a strong project README with:
   - Problem
   - Features
   - Tech stack
   - Architecture
   - Setup
   - Screenshots
   - Known limitations
   - Roadmap
7. Remove or move unrelated images into a separate archive/docs repo.
8. Keep the profile README short enough that a visitor can scan it quickly.

## Suggested pinned repositories

1. `All-in-python-project`
2. `PDF-Word-Translation-Tools-Over-500-Pages`
3. `Fetch-weather-webapp`
4. `AI-Research-Application`
5. `Sales-Data-Analysis-and-Visualization`
6. `Hill-Cipher-Implementation-in-Python` or `My-skyline-models`

## Link Test Checklist

| Test | Pass Condition |
|---|---|
| `README.md -> README_REWRITE_PROMPT.md` | Prompt file opens |
| `README.md -> README_REPLACEMENT_NOTES.md` | Notes file opens |
| `README_REWRITE_PROMPT.md -> README.md` | Main profile README opens |
| `README_REWRITE_PROMPT.md -> README_REPLACEMENT_NOTES.md` | Notes file opens |
| `README_REPLACEMENT_NOTES.md -> README.md` | Main profile README opens |
| `README_REPLACEMENT_NOTES.md -> README_REWRITE_PROMPT.md` | Prompt file opens |

If one link fails, check whether all three files are in the same folder and whether the file names match exactly.
