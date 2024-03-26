# Le CNAB

Aujourd'hui tu vas travailler sur le site du CNAB, le _Club Nautique des Amoureux du Bâteau_.

Tu disposes pour cela d'un dossier `assets` qui contient des images, un fichier audio et une vidéo.

Et ce sera à toi de créer les fichiers HTML et de les liers entre eux.

## Créer une première page

- Clone ton dépot
- Ouvre le ensuite dans VSCode
- Crée un premier fichier `index.html` directement à la racine du projet
- N'oublie pas de lancer _live server_ pour tester au fur et à mesure  
- Complète ton fichier avec le texte ci dessous en choisissant bien tes balises et en insérant les élements demandés

<details>
  <summary>Texte de la page Accueil</summary>

```md
# Bienvenue au CNAB

Le CNAB est le Club Nautique des Amoureux du Bâteau. Devenez adhérent pour rejoindre notre communauté de passionés de la voile.

## Notre coach Popeye

[ici mettre l'image popeye.jpg]

Notre coach Popeye vous accueille tous les lundis sur son voilier pour vous transmettre ses compétences de marin.
```

</details>

- Ta page doit posséder le titre `Bienvenue au CNAB`
- Ta page doit posséder la meta description `Le CNAB est le Club Nautique des Amoureux du Bâteau. Devenez adhérent pour rejoindre notre communauté de passionés de la voile.`
- Ta page doit posséder une icône de favoris, elle est fournie dans `assets/img`
- Prends l'habitude de `commit` et `push` chaque exercice réussi avec les commandes `git`

## Créer une deuxième page

- Crée un dossier `pages` pour y ranger les autres pages que l'on va créer à l'intérieur de ce dépot
- Crée une page `crew.html`
- Remplis là avec le contenu fourni ci dessous (en insérant les élements demandés)

<details>
  <summary>Texte de la page Equipage</summary>

```md
# L'équipage du CNAB

Notre club compte déjà quelques adeptes. Découvrez ci-dessous un extrait de notre dernière sortie.

[ici mettre la vidéo boats.mp4]

## Un équipe pleine de compétences

Notre coach Popeye capture régulièrement le son de l'océan. Voici un extrait enregistrée lors de notre dernier voyage.

[ici mettre le son waves.mp3]
```

</details>

- Il faut que l'audio et la vidéo disposent de contrôles pour gérer la lecture. L'audio doit se lancer automatiquement et se répéter, mais pas la vidéo. Place les attributs nécessaires.
- Ta page doit posséder le titre `Equipage du CNAB`
- Ta page doit posséder la meta description `Les membres du CNAB sont réunis autour de la passion commune de la voile et de l'océan.`
- Ta page doit posséder l'icône de favoris
- Prends l'habitude de `commit` et `push` chaque exercice réussi avec les commandes `git`

##  Créer un menu

- Rajoute sur chacune des pages des liens de navigations pour pouvoir passer de l'accueil à la page _équipage_
- Tu devras par la suite ajouter également des liens vers les pages des exercices suivants
- Commit et push

## Créer une troisième page
- Crée désormais une nouvelle page `blog.html`
- Remplis là avec le contenu fourni ci dessous (en insérant les élements demandés)
<details>
  <summary>Texte de la page Blog</summary>

```md
# Actu du CNAB

Découvrez ci dessous la [galerie photos] `ancre vers Galerie photos` ou [proposer vos souvenir] `ancre vers Partagez vos souvenirs`.

## Galerie photos

### Un travail d'équipe

[image crew.jpg]

Photo prise lors du voyage d'inauguration du voilier du CNAB

### Solidarité

[image helm.jpg]

Photo de Popeye venant assister nos membres lors d'une tempête

### Un bon marin doit savoir faire de bon noeuds

[image node.jpg]

Chaque premier vendredi du mois, Popeye fera la démonstration de noeuds marins.

### Le capitaine

[image popeye.jpg]

On ne présente plus le grand Popeye

## Partagez vos souvenirs

Pour partagez vos souvenir envoyez un email à [popeye@cnab.local] `lien mailto`.

En cas de problème appelez moi au [0123456789] `lien tel` 
```

</details>

- Ta page doit posséder le titre `Actu du CNAB`
- Ta page doit posséder la meta description `Retrouvez l'actu du CNAB et contactez-nous pour partager vos souvenirs de nos événements.`
- Ta page doit posséder l'icône de favoris
- Prends l'habitude de `commit` et `push` chaque exercice réussi avec les commandes `git`

## Corriger la quatrième page

- Je te fournis une dernière page, copie son contenu dans un fichier `history.html`

<details>
  <summary>Code de la page Histoire</summary>

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Historique du CNAB</title>
  <meta name="description" content="Retrouvez toute l'histoire du CNAB fondé par le grand Popeye.">
  <link rel="shortcut icon" href="./assets/favicon.ico" type="image/x-icon">
</head>
<body>
  <h1>Historique du CNAB</h1>
  <p>Fondé en 2007 par Popeye, le CNAB n'a cessé d'évoluer au fil des années</p>
  <p><img src="./assets/img/popeye.png" alt="Popeye : le fondateur"></p>
  <p>En 2022 la grande sortie d'été s'est tenue pour la première fois</p>
  <p>En 2023, Popeye lance le programme de formation aux noeuds marin. <a target="_blank' href="https://fr.wikipedia.org/wiki/Cat%C3%A9gorie:N%C5%93ud_marin" >Page wikipédia à propos des noeuds marin</a></p>
  <p><a href="/">Retour accueil</a></p>
</body>
</html>
```

</details>

- Corrige les erreurs que présente cette page, il y en a 3
- Commit et push

## Aller plus loin
- Si tu as fini n'hésite pas à tester plus de choses ou à étoffer ton CV mis en ligne avec Vercel.