# Academic CV – Maximus Watkins

LaTeX source for my academic CV. The latest compiled version is [`Maximus_Watkins_CV.pdf`](Maximus_Watkins_CV.pdf).

## Building

```
pdflatex main.tex
```

Requires the `roboto`, `fontawesome`, `tgheros`, `enumitem` and `ragged2e` packages (all included in TeX Live / Overleaf).
Each CV section lives in `Sections/` and is pulled in by `main.tex`; layout is defined in `resume.cls`.

Template based on the *Medium Length Professional CV* by LaTeXTemplates.com (CC BY-NC-SA 4.0).
