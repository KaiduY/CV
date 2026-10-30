[Download the latest version of my CV (PDF)](out/main.pdf)

# Alexandru-Georgian Oprea — CV

This repository contains the LaTeX source for my curriculum vitae. The CV is
typeset with a customized version of the Russell CV class, using a clean,
single-column layout and Roboto fonts.

## For readers

Use the PDF link at the top of this page to view or download my CV.

## For editing the CV

### Build

The document is built with LuaLaTeX. With `latexmk` installed, run this from
the repository root:

```bash
latexmk -lualatex -outdir=out main.tex
```

The generated PDF will be written to `out/main.pdf`. In VS Code, the
repository's LaTeX Workshop configuration uses the same build command.

### Source and formatting

- `main.tex` configures the document and includes the CV sections.
- `cv/` contains the content, split into one `.tex` file per section.
- `russell.cls` and `style.sty` provide the CV class and custom styling.
- `fonts/` contains the fonts used by the document.

The page is A4 with an 11 pt base font. Page margins, accent color, header,
footer, and section order are configured in `main.tex`. Edit the relevant
section files in `cv/` to update the CV content, and adjust `main.tex` to
change the layout or which sections are included.
