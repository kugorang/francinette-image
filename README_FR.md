![GitHub](https://img.shields.io/github/license/WaRtrO89/francinette-image) ![GitHub top language](https://img.shields.io/github/languages/top/WaRtrO89/francinette-image) ![GitHub repo size](https://img.shields.io/github/repo-size/WaRtrO89/francinette-image) ![GitHub Repo stars](https://img.shields.io/github/stars/WaRtrO89/francinette-image) ![GitHub repo directory count](https://img.shields.io/github/directory-file-count/WaRtrO89/francinette-image) ![GitHub watchers](https://img.shields.io/github/watchers/WaRtrO89/francinette-image) ![GitHub followers](https://img.shields.io/github/followers/WaRtrO89) ![GitHub contributors](https://img.shields.io/github/contributors/WaRtrO89/francinette-image) ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/WaRtrO89/francinette-image/master)

<h1 align="center">Installation de la Francinette sur <strong>une session de 42 Ubuntu</strong></h1>

La Francinette, créée par **[xicodomingues](https://github.com/xicodomingues)** est un outil permettant de tester différents projets de l'école 42 tels que `libft`, `ft_printf`, `get_next_line`, `minitalk` et `pipex`.

Utilisez la commande `francinette` ou `paco` à l'intérieur du dossier de votre projet pour l'exécuter.

Voici un installateur simple qui vous permet d'installer Francinette sur un **ordinateur Ubuntu** au sein d'un **cluster de l'école 42** sans avoir besoin des privilèges `sudo`. Je tiens à souligner que je ne suis pas le créateur de Francinette ! Il s'agit simplement d'un script qui facilite l'installation. Merci à [xicodomingues](https://github.com/xicodomingues).

Comment fonctionne cet installateur ? Il utilise `Docker` pour créer un environnement Ubuntu isolé qui configurera automatiquement Francinette avec toutes les autorisations nécessaires dans cet espace virtuel. Votre répertoire local `$HOME` sera partagé avec le conteneur Docker, permettant au conteneur d'exécuter des commandes qui interagissent avec vos fichiers et ainsi d'exécuter Francinette.

> [!note]
> Ce script a été développé pour l'installation sur les ordinateurs de l'école 42. Utilisez le script original pour votre ordinateur personnel, disponible [ici](https://github.com/xicodomingues/francinette/tree/master#readme).

## INSTALLATION :

Copiez et collez la ligne suivante dans votre terminal pour lancer l'installation, et vous serez prêt à commencer à tester vos projets de l'école 42 avec Francinette en un rien de temps !

```shell
bash -c "$(curl -fsSL https://raw.githubusercontent.com/WaRtrO89/francinette-image/master/install.sh)"
```
## Documentation

Je vous conseille vivement de consulter la [documentation originale de Francinette](https://github.com/xicodomingues/francinette/tree/master#readme) pour bien utiliser cet excellent outil !