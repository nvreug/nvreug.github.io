# Project Notes for Claude

## CV Management

The single source of truth for the CV is in this repo:

**CV Source Path:** `/Users/nicholasvreugdenhil/Dropbox (Personal)/nvreug.github.io/cv/cv.tex`

### Workflow for CV Updates:

1. Edit `cv/cv.tex` in this repo
2. Compile the PDF: `cd cv && pdflatex cv.tex` (run twice for cross-references)
3. Copy to website: `cp cv/cv.pdf paper/cv.pdf` (the website links to `paper/cv.pdf`)
4. Commit `cv/cv.tex` and `paper/cv.pdf`, then push

**Note:** The old Overleaf copy (`/Users/nicholasvreugdenhil/Dropbox (Personal)/Apps/Overleaf/cv/cv.tex`) is DEPRECATED as of August 2026. Do not edit it. The two copies diverged in July–August 2026 and were merged on 2026-08-29; the repo has been the single source since.
