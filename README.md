# Frontend Mentor - Solution Grille Bento

Il s'agit d'une solution pour le [défi Grille Bento sur Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Les défis de Frontend Mentor vous aident à améliorer vos compétences en codage en construisant des projets réalistes.

## Table des matières

- [Frontend Mentor - Solution Grille Bento](#frontend-mentor---solution-grille-bento)
  - [Table des matières](#table-des-matières)
  - [Aperçu](#aperçu)
    - [Le défi](#le-défi)
    - [Capture d'écran](#capture-décran)
    - [Liens](#liens)
  - [Mon processus](#mon-processus)
    - [Technologies utilisées](#technologies-utilisées)
    - [Ce que j'ai appris](#ce-que-jai-appris)
    - [Développement continu](#développement-continu)
    - [Ressources utiles](#ressources-utiles)
  - [Auteur](#auteur)

## Aperçu

### Le défi

Les utilisateurs doivent être capables de :

- Voir la mise en page optimale de l'interface en fonction de la taille de l'écran de leur appareil.

### Capture d'écran

![](assets/images/solutionLarge-1100.png)
![](assets/images/solutionMobile-300.png)

### Liens

- URL de la solution : [Ajoutez l'URL de la solution ici](https://github.com/doriannegelly/tp2-bento.git)
- URL du site en direct : [Ajoutez l'URL du site en direct ici](https://doriannegelly.github.io/tp2-bento/)

## Mon processus

### Technologies utilisées

- Marquage HTML5 sémantique
- Propriétés CSS personnalisées
- Flexbox
- CSS Grid
- Workflow mobile-first 

### Ce que j'ai appris

Je suis très fière de ce css puisque ce n'est pas toujours clair pour moi la position absolue des images, mais j'ai bien réussi dans ce cas:
```css
.case3 {
    display: flex;
    flex-direction: column;
    text-align: left;
    justify-content: space-between;
    position: relative;
}
.case3__image {
    position: absolute;
    bottom: -10px; 
    left: -2;
    transform: translateX(2%);
    max-width: 60%;
}
```

Je suis aussi très fière de ce css puisque je n'avais jamais utilisé de variantes avant:
```css
.mauve {
    color: var(--color-primary);
}
```

### Développement continu

Dans le futur, je souhaite apprendre encore mieux à organiser mon css et à mieux baliser mon HTML

### Ressources utiles

- [W3C](https://validator.w3.org/#validate_by_upload+with_options) - Cela m'a aidé poi=ur améliorer mon code.

## Auteur

- Site Web - [Dorianne Gelly](https://doriannegelly.github.io/tp2-bento/)
- Frontend Mentor - [@doriannegelly](https://www.frontendmentor.io/profile/doriannegelly) 