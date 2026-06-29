# README Replacement Notes

<p align="center">
  <a href="./README.md">Main Visual README</a> ·
  <a href="./README_PROOF_BASED_IT_PRESENCE.md">Proof-Based README</a> ·
  <a href="./README_REWRITE_PROMPT.md">Rewrite Prompt</a> ·
  <a href="./README_REPLACEMENT_NOTES.md">Replacement Notes</a>
</p>


---

## Document Role

This file explains how to deploy and maintain the linked README system.

- Main profile file: [README.md](./README.md)
- Professional proof-based companion: [README_PROOF_BASED_IT_PRESENCE.md](./README_PROOF_BASED_IT_PRESENCE.md)
- Rewrite engine prompt: [README_REWRITE_PROMPT.md](./README_REWRITE_PROMPT.md)
- This deployment guide: [README_REPLACEMENT_NOTES.md](./README_REPLACEMENT_NOTES.md)

---

## Why this rewrite is stronger

The main README keeps the original visual impact as the head file. The proof-based companion file exists to provide a cleaner technical signal for recruiters, maintainers, and engineering communities.

The companion README shifts the signal from:

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
  -> main visual public-facing profile
  -> links to all three companion files

README_PROOF_BASED_IT_PRESENCE.md
  -> professional proof-based companion README
  -> links back to the main README, prompt, and notes

README_REWRITE_PROMPT.md
  -> reusable AI prompt
  -> regenerates README_PROOF_BASED_IT_PRESENCE.md
  -> points back to README.md and notes

README_REPLACEMENT_NOTES.md
  -> deployment checklist
  -> explains why and how to replace the old README
  -> points back to README.md and prompt
```

## Required Repository Layout

Put all four files in the root of the public profile repository:

```text
haooah01/
├── README.md
├── README_PROOF_BASED_IT_PRESENCE.md
├── README_REWRITE_PROMPT.md
└── README_REPLACEMENT_NOTES.md
```

Do not put any of the three companion files in another folder unless you also update the links.

## What to do after replacing README.md

1. Put these four files in the public repository named exactly `haooah01`.
2. Make sure the main file is named `README.md`.
3. Keep `README_PROOF_BASED_IT_PRESENCE.md`, `README_REWRITE_PROMPT.md`, and `README_REPLACEMENT_NOTES.md` in the same root folder.
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
| `README.md -> README_PROOF_BASED_IT_PRESENCE.md` | Proof-based file opens |
| `README.md -> README_REWRITE_PROMPT.md` | Prompt file opens |
| `README.md -> README_REPLACEMENT_NOTES.md` | Notes file opens |
| `README_PROOF_BASED_IT_PRESENCE.md -> README.md` | Main visual README opens |
| `README_PROOF_BASED_IT_PRESENCE.md -> README_REWRITE_PROMPT.md` | Prompt file opens |
| `README_PROOF_BASED_IT_PRESENCE.md -> README_REPLACEMENT_NOTES.md` | Notes file opens |
| `README_REWRITE_PROMPT.md -> README.md` | Main visual README opens |
| `README_REWRITE_PROMPT.md -> README_PROOF_BASED_IT_PRESENCE.md` | Proof-based file opens |
| `README_REWRITE_PROMPT.md -> README_REPLACEMENT_NOTES.md` | Notes file opens |
| `README_REPLACEMENT_NOTES.md -> README.md` | Main visual README opens |
| `README_REPLACEMENT_NOTES.md -> README_PROOF_BASED_IT_PRESENCE.md` | Proof-based file opens |
| `README_REPLACEMENT_NOTES.md -> README_REWRITE_PROMPT.md` | Prompt file opens |

If one link fails, check whether all four files are in the same folder and whether the file names match exactly.
