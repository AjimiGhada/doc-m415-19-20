# Compléments d'algorithmique

## Documents : tous les fichiers sont accessibles dans le dossier `M415` ci-dessus.

##### DS: vous avez droit à une feuille de notes manuscrites, recto-verso A4

## Supports

Supports du module de DUT INFO TDFT02 TDFM415 2019-2020
Ces fichiers sont mis à jour tout au long du semestre.

 - [x] Séance 1 : Introduction : correction et terminaison des algorithmes
 - [ ] Séance 2 : Complexité : notations et applications
 - [ ] Séance 3 : Algorithmes gloutons
 - [ ] Séance 4 : Suite TD gloutons
 - [ ] Séance 5 : Programmation dynamique
 - [ ] Séance 6 : Heuristiques générales
 - [ ] Séance 7 : Suite TD heuristiques générales
 - [ ] Devoir surveillé

Pour une meilleure lecture, téléchargez et visualisez les fichiers pdf
sur votre disque local, en particulier pour voir les animations des
demos..

| Cours et énoncés de TD/TP |
| :---         |
| [Cours d'introduction sur l'algorithmique](M415/IntroAlgo.pdf "Cours d'introduction sur l'algorithmique") |



| Ouvrages et auteurs reconnus |
| :---
| [Introduction à l'algorithmique, ou Introduction to algorithms en version originale, est un livre d'algorithmique écrit par Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, et Clifford Stein. Le livre est parfois appelé CLR ou CLRS, d'après les initiales des noms des auteurs.](https://fr.wikipedia.org/wiki/Introduction_%C3%A0_l'algorithmique) |
||
| Algorithmes - Notions de base, ou Algorithms Unlocked en version originale, est un livre d'algorithmique écrit par Thomas H. Cormen. Il est traduit en francais et disponible à la BU Fabron. |
||
| [Donald Knuth: ](https://fr.wikipedia.org/wiki/Donald_Knuth)[The Art of Computer Programming (TAOCP)](http://www-cs-faculty.stanford.edu/~knuth/taocp.html)|
||
| [Edsger Dijkstra](https://fr.wikipedia.org/wiki/Edsger_Dijkstra) |
||
| [J. Kleinberg, E. Tardos. Algorithm Design. Addison Wesley, 2005](https://www.pearsonhighered.com/program/Kleinberg-Algorithm-Design/PGM319216.html) |
||


| Complexité et collections |
| :---
| [This page documents the time-complexity (aka "Big O" or "Big Oh") of various operations in current CPython.](https://wiki.python.org/moin/TimeComplexity) |
||
| [bigocheatsheet.com](http://bigocheatsheet.com/) |

## Attention :heavy_exclamation_mark:
Ce serveur web n'est pas forcément toujours disponible en dehors des heures de TD/TP: pensez à synchroniser les fichiers sur votre poste de travail.

### Conseil pour les TD, utilisation basique de git

#### Configuration
Configurez votre environnement (fichier `.gitconfig` à la racine de votre compte)

Exemple sous Windows (fichier `C:\Users\login`):
```
[http]
	sslVerify = false

[user]
	name = Prenom NOM
	email = Prenom.NOM@unice.fr

[gui]
	encoding = utf-8

[core]
	autocrlf = false

[credential]
	helper = wincred
```

Exemple sous Linux (fichier `$HOME/.gitconfig`):
```
[user]
	name = Prenom NOM
	email = Prenom.NOM@unice.fr

[core]
        autocrlf = false
        safecrlf = true
        editor = emacs

[alias]
        co = checkout
        ci = commit
        st = status
        br = branch
        hist = log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short
        type = cat-file -t
        dump = cat-file -p

[http]
        sslverify = false

[credential]
        helper = cache --timeout=3600

```

#### Première utilisation sur un poste local ou sur votre portable

Dans un terminal (clic droit et `Git Bash Here` sous Windows), on récupère d'abord son dépôt:

```
git clone https://github.com/uns-iut-info/M415_Prenom_NOM.git GITHUB
```

et aussi le dépôt contenant les fichiers de cours/TD/TP:

```
git clone https://github.com/uns-iut-info/doc-m415-19-20.git Cours_TD_M415
```

Ensuite vous travaillez dans vos dossiers / workspace habituels. À la
fin de la séance vous recopiez les fichiers réponse dans le dossier
GITHUB/M415/TD_NOM_DU_TD, puis vous mettez à jour votre dépôt distant.

```
cd GITHUB/
git add .
git commit -m "TD nom du td"
git push origin master
```

#### Utilisations suivantes

Si vous travaillez sur la même machine, allez successivement dans les
dossiers GITHUB et Cours_TD_M415, et mettez les à jour avec la
commande:

```
git pull
```

En fin de TD, procédez comme décrit ci-dessus pour la mise à jour du dépôt distant.

---

![Travelling Salesman Problem](https://imgs.xkcd.com/comics/travelling_salesman_problem.png "XKCD")
