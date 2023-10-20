**29 Septembre :**

- **Création du GitHub Commun :**
    
    - Discussion initiale de 15 minutes pour désigner la personne responsable de la création du repository GitHub commun.
    - Face à l'indécision, Aymene prend l'initiative de créer le GitHub commun.
- **Étude et Recherche En Groupe :**
    
    - Nous avons consacrés 30 minutes à la lecture de la documentation sur les commandes Git. [Accédez au cours sur Git](https://github.com/michaellaunay/NotesPubliques/blob/master/cours/git.md)
    - Voici quelques vidéos en plus :  ([Documentation Git](https://git-scm.com/doc))
    - 30 minutes supplémentaires sont consacrées à la recherche sur les méthodologies agiles, dont Kanban

	**Choix de la Méthodologie Kanban :**
    
    - Discussion et décision collective sur l'adoption de la méthode Kanban pour la gestion du projet. Notre choix s'est porté dessus, car nous pensons que c'est une méthode simple, efficace, et rapide à mettre ne place.
    
	Brief résumé de ce que nous avons trouvés : 
	Kanban est une méthode de gestion des processus de production qui vise à maintenir l'efficacité et la fluidité du travail. Il a été développé au Japon dans les usines Toyota dans les années 1940. Voici quelques concepts clés de Kanban :
	
1. **Visualisation du Travail** :
    
    - Kanban encourage la visualisation du flux de travail à travers des tableaux Kanban, qui sont divisés en différentes colonnes représentant les étapes du processus.
    - Chaque élément de travail (comme une tâche ou un projet) est représenté par une carte qui se déplace à travers les colonnes à mesure qu'il progresse.
2. **Limitation du Travail en Cours (WORK IN PROGRESS)** :
    
    - Kanban préconise la limitation du travail en cours pour éviter la surcharge et maintenir un flux de travail stable.
    - En limitant le WIP, les équipes peuvent mieux gérer les priorités et réagir plus rapidement aux changements.
3. **Gestion du Flux** :
    
    - L'objectif est d'optimiser le flux de travail pour réduire les temps d'attente et les encombrements.
    - La gestion du flux aide à identifier les goulets d'étranglement et à prendre des mesures pour les résoudre.


**6 Octobre :**

- **Validation de Kanban :**
    
    - Brainstorming en début de séance pour valider le choix de la méthode Kanban. Débat sur ses avantages par rapport à d'autres méthodes agiles.
- **Recherche sur Kanban :**
    - Recherche approfondie sur l'histoire et les principes de Kanban. ([Référence Kanban](https://kanbanize.com/kanban-resources/getting-started/what-is-kanban/))
- **Session avec M. Launay :**
    - M. Launay explique le concept du "fil de l'eau" et le suivi du projet, en prenant exemple sur l'un de ses projets personnel qui a été fait en duo.

**13 Octobre :**

- **Retard et Focus sur Git :**
    - La séance commence en retard en raison d'un problème personnel de M. Launay.
    - La majorité de la séance est consacrée à Git, avec un focus sur les commandes principales et leurs utilisations.

	Insérer une image, organigramme, diagramme. Expliquant les différentes commandes 

**20 Octobre :**

- **Présentation de Kanban :**
    - Introduction de la méthode Kanban au reste de la promotion, expliquant ses avantages et comment elle a été mise en œuvre dans le projet.



Faire l'organigramme à parti de ça : git ini, vim x.txt, git status, git add x.txt, git status, git commit -m, git push 
## Commandes Essentielles Git

## Configuration Initiale

### Installation de Git
- `apt install git` (Sur les systèmes basés sur Debian)

### Configuration de l'identité
- `git config --global user.name "Nom Utilisateur"`
- `git config --global user.email email@example.com`

## Initialisation et Clonage

### Initialisation d'un Nouveau Dépôt
- `git init` : Initialise un nouveau dépôt Git dans le répertoire courant

### Clonage d'un Dépôt Existant
- `git clone <URL-du-dépôt>` : Clone un dépôt existant

## Suivi des Modifications

### Statut des Fichiers
- `git status` : Montre le statut des fichiers dans le répertoire de travail

### Ajout des Fichiers
- `git add <fichier>` : Ajoute un fichier à la zone de préparation (staging area)
- `git add .` : Ajoute tous les fichiers modifiés à la zone de préparation

### Enregistrement des Modifications
- `git commit -m "message du commit"` : Enregistre les modifications dans le dépôt

## Historique des Commits
- `git log` : Affiche l'historique des commits
- `git log --oneline` : Affiche l'historique des commits en format court

## Branches

### Création et Changement de Branche
- `git branch <nom-de-la-branche>` : Crée une nouvelle branche
- `git checkout <nom-de-la-branche>` : Change de branche

### Fusion des Branches
- `git merge <nom-de-la-branche>` : Fusionne la branche spécifiée avec la branche courante

## Collaboration et Mise à Jour

### Récupération des Modifications
- `git pull` : Récupère les modifications du dépôt distant et les fusionne avec le répertoire de travail local

### Envoi des Modifications
- `git push` : Envoie les modifications locales au dépôt distant

## Gestion des Conflits
- En cas de conflits lors d'une fusion, résolvez les conflits manuellement dans les fichiers concernés, puis utilisez `git add <fichier>` pour marquer les fichiers comme résolus.

## Références Supplémentaires
- Documentation officielle Git
- Tutoriels en ligne et vidéos de formation



