# Thèse LaTeX EHESS

## Introduction

Ce dépôt propose un template LaTeX permettant de créer une thèse conforme aux normes de présentation de l'[École des Hautes Études en Sciences Sociales](https://www.ehess.fr/).


## Fichiers

Les fichiers suivants sont inclus dans ce projet :

- `thesis.tex` : exemple de fichier LaTeX avec un chapitre.
- `thesisehess.sty` : fichier de style pour la présentation conforme à l'EHESS.
- `ehess.png` : logo de l'université.
- `thesis.pdf` : exemple de fichier PDF généré à partir du fichier `thesis.tex`.

## Mode d'emploi

1. **Téléchargement et Organisation des fichiers** : Téléchargez tous les fichiers nécessaires, y compris le fichier `thesisehess.sty`, et placez-les dans un dossier dédié pour votre projet de thèse.

2. **Utilisation du style EHESS** : Dans votre document `.tex`, ajoutez les lignes suivantes au début du préambule pour utiliser le style [EHESS](https://www.ehess.fr/) :

    ```latex
    \documentclass{book}
    \usepackage{thesisehess}
    ```

3. **Modification des métadonnées** : Après avoir déclaré `\documentclass{book}` et `\usepackage{thesisehess}` dans le préambule de votre document `.tex`, modifiez le champs de métadonnées pour qu'ils correspondent à votre projet de thèse.

## Contact

Si vous avez des suggestions ou des questions, n'hésitez pas à me contacter : [hugo.dones@ehess.fr](mailto:hugo.dones@ehess.fr)




