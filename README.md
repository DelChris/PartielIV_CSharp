# PartielIV
Repository for exam

Question 1 et 2 :
- Création à la main d'un fichier README.md

- cd C:... (Chemin du projet)

- git init

- git add JeSuisUnProjetCSharp
- git add JeSuisUnProjetCSharp.sln
- git add README.md

- git commit -m "First commit"

- git remote add origin https://github.com/TheSora06/PartielIV_CSharp.git

- git push -u origin master

- Je me suis identifié

Question 3 :
- git checkout -b "dev"
- git checkout dev

Question 4 :
	Premier commit :
	- git add JeSuisUnProjetCSharp
	- git add JeSuisUnProjetCSharp.sln
	- git commit -m "First commit in dev branch"
	- git push -u origin dev

	Deuxième commit:
	- git add README.md
	- git commit -m "Second commit in dev branch"
	- git push -u origin dev

	Troisième commit (comme j'ai oublié de remplir le README.md) :
	- git add README.md
	- git commit -m "Third commit in dev branch"
	- git push -u origin dev

Question 5 :
- git checkout master
- git merge dev