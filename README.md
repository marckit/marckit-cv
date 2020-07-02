<h1 align="center">
  Curriculum Vitae
  <br />
  <a href="https://github.com/marckit/cv-marckit" title="Marckit CV Documentation">
    <img alt="Marckit CV" src="https://github.com/marckit/cv-marckit/blob/french/images/profile.png" width="200px" height="200px" />
  </a>
</h1>

<p align="center">
  LaTeX CV
</p>

<div align="center">
  <a href="https://circleci.com/gh/marckit/cv-marckit/">
    <img alt="CircleCI" src="https://circleci.com/gh/marckit/cv-marckit/tree/french.svg?style=shield" >
  </a>
  <a href="https://raw.githubusercontent.com/marckit/cv-marckit/french/pdf/cv.pdf">
    <img alt="Example CV" src="https://img.shields.io/badge/cv-pdf-purple.svg" />
  </a>
  <a href="https://raw.githubusercontent.com/marckit/cv-marckit/french/pdf/coverletter.pdf">
    <img alt="Example Coverletter" src="https://img.shields.io/badge/coverletter-pdf-pink.svg" />
  </a>
</div>

<br />

## Table des matières

- [Fichiers](#fichiers)
- [Fonctionnement](#fonctionnement)
    * [Sont requis](#sont-requis)
    * [Utilisation](#utilisation)
- [Credit](#credit)

## Fichiers

**Code source fichiers**
- [Code source](./texfichiers) des fichiers `.tex` pour créer les `pdf`
- [cv.tex](./texfichiers/cv.tex)
  * Changer de branche pour changer la langue.
  * La branche `master` est en [anglais](https://github.com/marckit/cv-marckit/).
- [coverletter.tex](./texfichiers/cv.tex)
  * Décommenter la ligne `\photo[circle,noedge,left]{./images/profile}`
    en enlevant `%` pour utiliser l'image.
  * Selectionner `R`, `C` ou `L` pour aligner `\makecvheader[R]`

**Images**
- Renommer l'images à `images/profile.png`

**PDF**

- SVP, télécharger le [pdf folder](./pdf) ou cliquez sur l'icone ci-dessous.
  *  <a href="https://raw.githubusercontent.com/marckit/cv-marckit/french/pdf/cv.pdf">
       <img alt="Example CV" src="https://img.shields.io/badge/cv-pdf-purple.svg" />
    </a>
  * <a href="https://raw.githubusercontent.com/marckit/cv-marckit/french/pdf/coverletter.pdf">
      <img alt="Example Coverletter" src="https://img.shields.io/badge/coverletter-pdf-pink.svg" />
    </a>
- Curriculum Vitae

| CV page un |  CV page deux |
|:---:|:---:|
| [![Lettre de presentation (Traditionnelle)](https://raw.githubusercontent.com/marckit/cv-marckit/french/images/cv-p1.png)](https://raw.githubusercontent.com/marckit/cv-marckit/french/images/cv-p1.png)  | [![Lettre de presentation (Image)](https://raw.githubusercontent.com/marckit/cv-marckit/french/images/cv-p2.png)](https://raw.githubusercontent.com/marckit/cv-marckit/french/images/cv-p2.png) |

- Coverletter template

| Sans sections et image | Avec sections et image |
|:---:|:---:|
| [![Lettre de presentation (Traditionnelle)](https://raw.githubusercontent.com/marckit/cv-marckit/french/images/coverletter-0.png)](https://raw.githubusercontent.com/marckit/cv-marckit/french/images/coverletter-0.png)  | [![Lettre de presentation (Image)](https://raw.githubusercontent.com/marckit/cv-marckit/french/images/coverletter-1.png)](https://raw.githubusercontent.com/marckit/cv-marckit/french/images/coverletter-1.png) |

## Fonctionnement

#### Sont requis

Il faut la distribution de TeX complète.
[systems (Windows, Mac, \*nix) disponible](
http://tex.stackexchange.com/q/55437)
mais TeX live est recommandé.
Pour la dernière version
[install TeX from upstream](http://tex.stackexchange.com/q/1092)
(recommandée; plus à jour)
ou utilisez `sudo apt-get install texlive-full`.

#### Utilisation

En ligne de commande, lancez

```bash
$ make
```

## Credit

[**Bitmoji**](https://www.bitmoji.com/) pour la photo de profile.

[**Awesome-CV**](https://github.com/posquit0/Awesome-CV) canevas de
cv forked sur github.

[**Fancy CV**](https://www.sharelatex.com/templates/cv-or-resume/fancy-cv)
un ancien canevas.

[**LaTeX**](http://www.latex-project.org) tres utile pour
les travaux scientifiques.

[**LaTeX FontAwesome**](https://github.com/furl/latex-fontawesome)
utiliser pour les icones FontAwesome utiliser avec XeLaTeX.

[**Roboto**](https://github.com/google/roboto) police pour Android and ChromeOS,
pour Google’s visual language, utiliser Material Design.

[**Source Sans Pro**](https://github.com/adobe-fonts/source-sans-pro)
police OpenType travail bien avec l'interface utilisateur (IU).

