# Bioinformatics Algorithms — HS 2026

Course materials for **Bioinformatics Algorithms**, University of Bern (HS 2026).

This repository is meant for **students**: clone it, open the Quarto slides, and add your own notes.

## Currently available

- **Week 1** — Algorithms, recursion, complexity (`Slides/01-complexity.qmd`, [PDF](Slides/01-complexity.pdf))
  - Lab: `Slides/labs/01-fib.ipynb`
- **Week 2** — Hard problems and greedy ideas (`Slides/02-hard-problems.qmd`, [PDF](Slides/02-hard-problems.pdf))
  - Lab: `Slides/labs/02-tsp.ipynb` (TSP + genetic algorithm + interval scheduling)
- **Week 3** — Dynamic programming: tourist + alignment (`Slides/03-dynamic-programming.qmd`, [PDF](Slides/03-dynamic-programming.pdf))
  - Labs: `Slides/labs/03-tourist.ipynb`, `Slides/labs/04-nw.ipynb`

Later weeks will be added as the course progresses.

## How to use

1. Clone this repo (or download the ZIP from GitHub).
2. Open the week's `.qmd` in [VS Code](https://code.visualstudio.com/) / Cursor, or any editor.
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
   quarto render 03-dynamic-programming.qmd
   ```

5. Open the lab notebooks in VS Code / Jupyter (Select Kernel → Run All):
   - Week 1: `Slides/labs/01-fib.ipynb`
   - Week 2: `Slides/labs/02-tsp.ipynb` (needs `matplotlib` for the genetic-algorithm animation)
   - Week 3: `Slides/labs/03-tourist.ipynb` and `Slides/labs/04-nw.ipynb`

## Course

Instructor: Stephan Peischl · University of Bern  
Slides are also posted on ILIAS. This repo is the editable source for your notes.
