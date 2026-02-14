# Project Notes for Claude

## CV Management

The authoritative CV source is maintained in Overleaf and synced via Dropbox:

**CV Source Path:** `/Users/nicholasvreugdenhil/Dropbox (Personal)/Apps/Overleaf/cv/cv.tex`

### Workflow for CV Updates:

1. Edit the CV at the Overleaf path above
2. Compile the PDF: `cd /Users/nicholasvreugdenhil/Dropbox\ \(Personal\)/Apps/Overleaf/cv && pdflatex cv.tex`
3. Copy to website: `cp /Users/nicholasvreugdenhil/Dropbox\ \(Personal\)/Apps/Overleaf/cv/cv.pdf /Users/nicholasvreugdenhil/Dropbox\ \(Personal\)/nvreug.github.io/paper/cv.pdf`
4. Commit and push the updated PDF in the website repository

**Note:** The CV in `/Users/nicholasvreugdenhil/Dropbox (Personal)/nvreug.github.io/cv/` is NOT the source of truth - always use the Overleaf version.
