# Machine Learning
En 2018-2019, ce cours s'appelait Big Data Analytics I.

## Formulaire/synthèse donné
La synthèse donnée ici n'a pas pour vocation d'expliquer le cours mais plutôt de servir comme notes de cours pour l'examen théorique. Cependant, les preuves ont été étendues pour être plus claires et les notations ont été uniformisées (plus ou moins). Pour compiler (avec l'index, la liste des abbréviations et les références), il faut exécuter :
```
xelatex formulaire.tex && makeindex formulaire && makeindex -s nomencl.ist -o formulaire.nls formulaire.nlo && biber formulaire && xelatex formulaire.tex && xelatex formulaire.tex
```

## Description
	* Apprentisage machine
		* Régression
			* Linéaire
			* Ridge
			* Lasso
			* Arbres
		* Classification
			* Régression logistique
			* Linear et Quadratic Discriminant Analysis
			* k-NN
			* Arbres
			* Forêts aléatoires
	* Bagging
	* Cross-validation, bootstrap
	* Analyse en composantes principales (PCA)
	* Sélection de modèles
	* Langage R

Ce cours a une approche orientée probabilités et statistiques.

## Horaire
	* 30 heures théoriques
	* 15 heures de TP

## ECTS
	* 5 crédits
	* Examen écrit (à cahier ouvert) pour 60%
	* Projet pour 20%
		* En 2018-2019, le projet consistait à utiliser les algorithmes vus en cours (et d'autres) sur un problème de classification.
	* 4 devoirs pour 20%

[Lien vers la fiche ECTS](http://applications.umons.ac.be/web/fr/pde/2018-2019/ue/US-MC-SCINFO-050-M.htm)

## Professeur
	Souhaib Ben Taieb
