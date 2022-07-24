---
title: |
  ![](./img/Logo.png){width=2in}  
  "Rapport fin de parcours DevOps."
subtitle: "Overview"
date: \today{}
lang: fr-FR
urlcolor: blue
geometry: "left=2.5cm,right=2.5cm,top=3cm,bottom=3cm"
documentclass: article

---
# Rapport sur les commandes GIT et LINUX


# Les commandes linux:
1. La commande LS:
- Description:
La commande LS permet de lister le contenu du répertoire courant: fichiers et autres répertoires imbriqués.
- _Eemple d'utilisation:

![](./img/commande_LS.png){width=2in}

2. La commande PWD:
- Description: 
Elle permet d'afficher le répertoire de travail et donne le chemin absolu du répertoire dans lequel vous vous trouvez.
PWD "Print Working Directory". 
- _Exemple d'utilisation:

![](./img/commande_PWD.png){width=2in}

3. La commande CD:
- Description: 
Elle permet d'accéder à un répertoire en mettant cd et le nom.
Elle signifie "Change Directory". 
- _Exemples d'utilisation:
- __Exples:
cd .. :permet de monter d'un niveau.
cd - : retourner au répertoire précedent.

![](./img/commande_CD.png){width=2in}

4. La commande CP:
- Description: 
Elle permet de copier des fichiers et des répertoires directement depuis le terminal. 
- _Exemples d'utilisation:
- __Exples:
cp fichier1.rtf nouveau_fichier.rtf 
cp -r rep1/ nouveau_rep/

![](./img/commande_CP.png){width=2in}

5. La commande RM:
- Description: 
Elle permet de suppprimer des fichiers et des répertoires. 
- _Exemples d'utilisation:
- __Exples:
rm -r permet de supprimer un répertoire vide
rm -rf permet de supprimer un répertoire avec son contenu.

![](./img/commande_RM.png){width=2in}

6. La commande MV:
- Description: 
Elle permet de déplacer ou renommer des fichiers/répertoires ds le système de fichiers. 
- _Exemples d'utilisation:
- __Exples:
mv fichier2.rtf nouveau_rep/
mv nouveau_fichier.rtf fichier2.rtf

![](./img/commande_MV.png){width=2in}

7. La commande MKDIR:
- Description: 
Elle permet de créer de nouveaux répertoires au niveau du shell. 
- _Exemples d'utilisation:
- __Exples:
mkdir rep3/
mkdir -p rep3/rep4/

![](./img/commande_MKDIR.png){width=2in}

![](./img/Illustration1_MKDIR.png){width=2in}

![](./img/Illustration2_MKDIR.png){width=2in}

8. La commande MAN:
- Description: 
Elle affiche la page de manuel de n'importe quelle autre commande. 
- _Exemple d'utilisation:
- __Exple:
mkdir man

![](./img/commande_MAN.png){width=2in}

![](./img/Illustration_MAN.png){width=2in}

9. La commande TOUCH:
- Description: 
Elle permet de créer de nouveaux fichiers ainsi que de mettre à jour les temps d'accès et de modification des fichiers. 
- _Exemple d'utilisation:
- __Exple:
touch fiche3.rtf

![](./img/commande_TOUCH.png){width=2in}

![](./img/Illustration_TOUCH.png){width=2in}

10. La commande History:
- Description: 
Elle affiche une liste numérotée des commandes utilisées antérieurement. 
- _Exemple d'utilisation:
- __Exple:
history

![](./img/commande_HISTORY.png){width=2in}


# Les commandes GIT:
1. La commande GIT STATUS:
Elle affiche la liste des fichiers modifiés ainsi que les fichiers qui doivent encore être ajoutés ou validés.
Exemple d'illustration:
git status

![](./img/commande_git_status.png){width=2in}

2. La commande GIT ADD:
Elle permet d'ajouter des fichiers à l'index.
Exemple d'illustration:
git add article.md

![](./img/commande_git_add.png){width=2in}

3. La commande GIT COMMIT:
Elle permet de valider les modifications apportées au HEAD.
Exemple d'illustration:
git commit -m "Commande GIT STATUS"

![](./img/commande_git_commit.png){width=2in}

4. La commande GIT PUSH:
Elle permet d'envoyer les modifications locales apportées à la branche principale.
Exemple d'illustration:
git push

![](./img/commande_git_push.png){width=2in}

5. La commande CLONE GIT:
Elle permet de vérifier les dépôts, aussi de créer un dépôt de travail en local sur la machine.
Exemple d'illustration:
git clone /chemin/vers/dépôt

![](./img/commande_git_clone.png){width=2in}

6. La commande GIT INIT:
Elle permet de créer un nouveau dépôt GIT.
Exemple d'illustration:
git init

![](./img/commande_git_init.png){width=2in}

7. La commande GIT CONFIG:
Elle permet de configurer les préférences de l'utilisateur:mail, nom utilisateur, format fichier.
Exemple d'illustration:
git config --global user.email alioune201@outlook.com

![](./img/commande_git_config.png){width=2in}

8. La commande GIT BRANCH:
Elle permet de répertorier, créer ou supprimer des branches.
Exemple d'illustration:
git branch: pour répertorier les branches.
git branch -d <nom-branche>: pour supprimer une branche.

![](./img/commande_git_branch.png){width=2in}









## Sous titre:
### Sous sous titre

# Liste

- Un
- _Deux_
- __Trois__

# Liste numérotée

1. Un
2. Deux
3. Trois

# Liens:

- [Google](https://www.google.com)
- ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

# Tables

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |









