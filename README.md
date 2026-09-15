# Bioinformatics Algorithms — HS 2026

Course materials for **Bioinformatics Algorithms**, University of Bern (HS 2026).

This repository is meant for **students**: clone it, open the Quarto slides, and add your own notes.

## Currently available

- **Week 1** — Algorithms, recursion, complexity (`Slides/01-complexity.qmd`)
- Lab notebook: `Slides/labs/01-fib.ipynb`

Later weeks will be added as the course progresses.

## How to use

1. Clone this repo (or download the ZIP from GitHub).
2. Open `Slides/01-complexity.qmd` in [VS Code](https://code.visualstudio.com/) / Cursor, or any editor.
3. Add your notes **in the `.qmd` file** as you follow the lecture, for example:
   - ordinary Markdown paragraphs or bullet lists
   - HTML comments that do not show when rendered: `<!-- your note -->`
   - Quarto speaker notes (visible in presenter mode):

     ```markdown
     ::: notes
     My reminder for the exam.
     :::
     ```
4. Optional: render the slides locally

   ```bash
   cd Slides
   quarto render 01-complexity.qmd
   ```

5. Open the lab in VS Code / Jupyter: `Slides/labs/01-fib.ipynb` (Select Kernel → Run All).

## Course

Instructor: Stephan Peischl · University of Bern  
Slides are also posted on ILIAS. This repo is the editable source for your notes.
