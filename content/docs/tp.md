+++
title = "TP Git projet solo"
author = ["Rey-Coyrehourcq Sebastien (reyman)"]
draft = false
+++

## Site web avec publications fixe {#site-web-avec-publications-fixe}


### Objectifs {#objectifs}

< image résultat final >

Nous allons déployer un site web personnalisé sur une gitlab pages.


### Pré-Requis {#pré-requis}

-   Base en Git
-   Base en HTML
-   Compte Gitlab personnel


### Etapes {#etapes}


#### (optionnel) Installation de Ruby sur votre machine {#optionnel--installation-de-ruby-sur-votre-machine}

<https://jekyllrb.com/docs/installation/>


#### Fork du site web {#fork-du-site-web}

Pour gagner du temps j'ai déjà préinstallé un thème.

```bash
git clone git@gitlab.huma-num.fr:rzine/formations/git-gitlab/templatesiteperso.git
```

```bash
bundle install
```

De base avant customisation par ajout d'un thème le site web ressemble à cela :

{{< figure src="/ox-hugo/jekyll_simple.png" height="80%" >}}

Pourquoi un fork et pas un clone ? On ne sait jamais vous voudriez peut être
proposer des modifications dans le template du site web original ...

Si vous voulez consulter votre site web en local, il faut que vous ayez
installer ruby sur votre ordinateur. Ensuite il suffit de se positionner
dans le bon répertoire et de lancer un serveur web local avec les commandes suivantes :

```bash
bundle exec jekyll serve
```

Le résultat est visible dans votre navigateur internet à l'url suivante : <http://localhost:4000>


## Publications dynamique avec Orcid / R et Vitae {#publications-dynamique-avec-orcid-r-et-vitae}


### Fork du dépot template {#fork-du-dépot-template}


### Clone du dépot en local {#clone-du-dépot-en-local}
