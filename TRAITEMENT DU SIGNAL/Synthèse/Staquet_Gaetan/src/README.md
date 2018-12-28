# FormulaireTraitementSignal
Formulaire pour le cours de Traitement du Signal de l'UMONS (année académique 2018-2019)

Pour compiler, il faut :
  * Que Tikz soit installé (avec toutes ses dépendances)
  * Créer un dossier `figures` à la racine
  * Ajouter `-shell-escape` à l'invocation de pdflatex. L'appel devrait donc ressembler à : `pdflatex -shell-escape formulaire.tex`

Si vous voulez également compiler l'index et la liste des symboles (ce que je vous recommande), il faut appeler `makeindex`. Veuillez vous référer au [Wikibooks](https://en.wikibooks.org/wiki/LaTeX/Indexing) pour les instructions exactes.