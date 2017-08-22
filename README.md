# TUTORIEL GIT : UTILISATION EN LIGNE DE COMMANDE

## LIEN UTILE
[Tutoriel Openclassrooms](https://openclassrooms.com/courses/gerez-vos-codes-source-avec-git "Lien vers le tuto")

## PREMIERS PAS
* Créer un nouveau dépôt :
```
git init
```
* Ajouter le fichier lisez moi "README" :
```
git add README.md
```
* Soumettre le fichier 
```
git commit -m "Mon commentaire"
```
* Remonter et ajouter à l'origine
```
git remote add origin https//github.com/utilisateur/
```
* Ajouter au dépôt
```
git push -u origin master
```

## SOUMETTRE UN FICHIER

* 1. Ajouter un fichier prêt à être envoyé :
```
git add nomfichier1 nomfichier2
```
* 2. Effectuer le commit
```
git commit
```

### SOUMETTRE PLUSIEURS FICHIERS
```
git commit -a
```
