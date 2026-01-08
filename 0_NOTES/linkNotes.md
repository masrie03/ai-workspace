1. Link Notes to Notebooks (Clean & Practical)
Goal

From a concept note → you can immediately jump to the code where you applied it.

How to Do It (Exact Method)
A. In the note file, add a “Related Notebooks” section

Example in
2_Machine_Learning/notes/supervised_learning.md

## Related Notebooks
- ../notebooks/01_linear_regression.ipynb
- ../notebooks/02_logistic_regression.ipynb


This works because:

Markdown supports relative paths

GitHub makes them clickable

VS Code opens them directly

B. In the notebook, add a reference back to the note

At the top markdown cell of the notebook:

**Concept Notes:**  
See `../notes/supervised_learning.md`


Now:

Notes → Notebook

Notebook → Notes

Two-way linking. No duplication.