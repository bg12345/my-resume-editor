# my-resume-editor

LaTeX source for my resume (`resume.tex` → `resume.pdf`).

## Requirements

- A LaTeX distribution with `pdflatex` (e.g. [MacTeX](https://tug.org/mactex/) on macOS, or TeX Live on Linux)
- Packages used (included in most full LaTeX distributions): `geometry`, `enumitem`, `hyperref`, `titlesec`, `parskip`, `tabularx`

## Build

```bash
pdflatex resume.tex
```

This generates `resume.pdf`. Auxiliary files (`.aux`, `.log`, `.out`, etc.) are build artifacts and can be deleted safely.
