# Prerequisites

## Setting up/updating the git environment and git flow

[Get the installer](https://git-scm.com/downloads)

{% hint style="info" %}
Git-flow library:\
For Windows, is natively integrated.\
For Mac, [here is the procedure](https://git-scm.com/download/mac).\
Pour Linux, [here is the procedure.](https://howtoinstall.co/en/git-flow)
{% endhint %}

```
[INPUT]
sudo apt-get install git-flow 

[OUTPUT]
télécharge les paquets de git flow et installe après confirmation
```

* [x] Confirm the installed version

```
[INPUT]
git flow version

[OUTPUT]
1.12.3 (AVH Edition)
```

* [ ] What do you think about this release?

```
//TODO
```

## What's git-flow, branches feature.

[Source](https://nvie.com/posts/a-successful-git-branching-model/)

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Source : A successful git branching model</p></figcaption></figure>

* [x] Which branches are persistent and what do they contain?

```
Main -> la branche principale où le code doit être toujours à jour et fonctionnel

Develop -> la branche de développement où on peut travailler et tester sans déranger le branche principale 
```

* [x] Why do we have to merge hotfix in both master and develop branches, but not into all active feature branches?

```
Afin de pouvoir travailler dans la branche voulue avec les hotfix récemment fixé, si on le fait pas, on codera sur une branche dont l'erreur est toujours là
```

## Initialize git flow on an existing project

* [x] What happens when you run the "git flow init" command on an existing local repository?

```
Le message d'erreur apparaît "Working tree contains unstaged changes. aborting"


```

* [x] When do we need to make this git command?

```
Après avoir cloné un dépot vierge, ensuite taper "git flow init" pour initialiser les branches de bases dans le répertoire local
```

## Practice the basic git commands

[Source](https://www.atlassian.com/git/glossary)

* [x] What does this git command "git add -all" achieve (.gitignore impacts)?

```
git add -all ajoute tout , même les données de .gitignore et c'est pas le but 
```

* [x] What does this git command "git status" achieve?

```
Affiche la branche et les /dossier/Fichiers qui ont été modifiés. 
```

* [x] What does this git command "git remote add upstream \<url>" achieve?

```
cette commande permet de "remote" un dépot à distance afin de pouvoir agir avec eux. 
```
