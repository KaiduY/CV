# LaTeX Paper Template

A clean, lightweight LaTeX template for writing **mathematics and physics papers**.

## 📁 Structure

```text
.
├── main.tex        # Main LaTeX document
├── style.sty       # Custom commands and formatting
├── ref.bib         # Bibliography
├── papers/         # Paper source files / drafts
├── private/        # Private or local files
├── out/            # Generated output
└── .vscode/        # VS Code configuration
```

## 🚀 Getting Started

Clone the repository and open `main.tex` in your preferred LaTeX editor.

```bash
git clone https://github.com/KaiduY/paper-template.git
cd paper-template
```

Compile with your preferred LaTeX toolchain, e.g.

```bash
latexmk -pdf main.tex
```

Alternatively, the project can be opened directly in **VS Code** with the LaTeX Workshop extension.

## ✏️ Writing

Most of the paper should be written in `main.tex` or in files included from it.

Custom notation, commands, and formatting should be placed in:

```text
style.sty
```

References should be added to:

```text
ref.bib
```

and cited normally in LaTeX:

```latex
\cite{Author2026}
```

## 📚 Recommended Workflow

1. Copy the template for a new paper.
2. Update the title, authors, and metadata in `main.tex`.
3. Write the paper and add figures as needed.
4. Add references to `ref.bib`.
5. Keep reusable mathematical notation in `style.sty`.
6. Compile with `latexmk`.
7. Keep generated files in `out/` rather than committing them unnecessarily.

## 📝 Notes

The template is intentionally kept general so that it can be adapted to different mathematics and physics projects.

**Repository:** [KaiduY/paper-template](https://github.com/KaiduY/paper-template?utm_source=chatgpt.com)
