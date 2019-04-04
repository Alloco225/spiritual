# [spiritual](github.com/Alloco225/spiritual)
##  -spirituals.com- || -spiritualprogrammers.com-

## Site web du groupe Spiritual Programmers [NaN](www.nan.ci)

### Specs

- [ ] : __Login__
  Système de connexion
    - Les membres sont préalablement inscrits par l'admin
    - Seul le parrain peut inscrire ou supprimer un membre
- [ ] : __Publication de posts__
  Publication de contenus (avec fichiers) par catégories 
    __Liste des catégories__
    - Projets
    - TD / Exercices
    - Préoccupations / Problèmes / Difficultés par rapport à un exercice
    - Invitation à NaN
   *formats de fichiers acceptés :* .ZIP .JPEG .PNG .TXT
- [ ] : __Upvotes / Rating / Star / Notes sur 20__
  Système de votes et de notage
    - Les posts seront triés par ordre décroissant de votes et de notes
    - Upvoter un post pour qu'il monte
    - Downvoter un post pour qu'il descende
    - Ajouter une star sur un projet pour l'enregistrer dans ses favoris
    - *Projets et TD :* le parrain peut attribuer une note
    
- [ ] : __Commentaires / Réponses__
  Systeme de commentaires/réponses directe
    - Répondre directement à un post ou un exercice ou un TD (récursion = 3)
    - Modifier directement le code d'un post et l'afficher comme réponse

### Init
- **Technologies :**
    - [x] __Backend__
      Laravel
    - [x] __Frontend__
      Bootstrap

### Fonctionnement
- [ ] Démarrage du site
- [ ] Page de connexion
  - [ ] Si Authentification Ok
    - [ ] Renvoi sur la page d'accueil
- [ ] Page d'acceuil
 - [ ] Sidebar
    - [ ] Information du membre
      - [ ] Photo
      - [ ] Nom Prénom
      - [ ] etc
    - [ ] Navigation (block vertical)
      - [ ] Acceuil
      - [ ] Tous les posts
        - [ ] Zone de saisie d'un nouveau post ()
        - [ ] Affichage des posts par dates récentes
          - [ ] Jumbotron du post
            - [ ] h3 Titre du post (à gauche)
            - [ ] badge Catégorie du post (à droite, avec couleur contextuelle)
          - [ ] Container des commentaires/réponses
            - [ ] Liste des commentaires/réponses par votes décroissants (max: 3)
            - [ ] boutton Voir plus de commentaires
          - [ ] Zone d'action (inline)
            - [ ] Zone de upvote, star (ajout aux favoris)
            - [ ] form Saisie de commentaire/réponse
    
### Pages (min: 3)
1. [ ] Accueil
  1. [ ] Connexion (popup)
  1. [ ] Pages des posts (par date ou par catégories)
  1. [ ] Page du membres (CRUD de ses posts ou de ses favoris)
1. [ ] Administration
  1. [ ] CRUD par catégories (membres, membre_roles, post_categories, notes, etc)
    
### Credits 
  - [Souleyman Al-amin KadimouLah](github.com/toure5013)
  - [Fullstack](github.com/NonwaFabrice07)
  - [Alloco225](github.com/Alloco225)
    
