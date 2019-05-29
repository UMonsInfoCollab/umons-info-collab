# FormulaireML
Formulaire pour le cours de BIg Data Analytics I

## Compilation
```bash
xelatex formulaire.tex && xelatex formulaire.tex && makeindex formulaire && makeindex formulaire.nlo -o formulaire.nls && xelatex formulaire.tex && xelatex formulaire.tex
```

Sous certains systèmes, `makeindex` est appelé `makeidx`.