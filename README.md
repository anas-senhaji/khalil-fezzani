## Angular technical test
GitHub Profile Viewer:

GitHub API:

* https://api.github.com/users ===> GET ALL USERS
* https://api.github.com/users/{login} ==> GET USER PROFIL
* https://api.github.com/users/{login}/repos ==> GET USER REPOS
* https://api.github.com/users/{login}/followers ==> GET USER FOLLOWERS
* https://api.github.com/repos/{login}/{repo_name} ==> GET REPO BY REPO NAME AND USERNAME

### The application would allow to:

* User Profile Information: The application should display the user's name, profile picture, bio, location, and other information that is publicly available on their GitHub profile.
* Repository List: The application should display a list of repositories owned by the user, including the repository name, description, and number of stars.
* Followers: The application should display a list of followers for the user, including their name and profile picture.
* Repository Statistics: For each repository, the application should display the number of commits, issues, and pull requests, as well as a graph of the repository's activity over time.
* Search Functionality: The application should allow users to search for a specific GitHub user by username, and display their profile information and repositories.

##### Technologies and utilities that should be used:

* Angular (Frontend Framework)
* NgRx (state management)

##### The most important of this test is to write a clean and readable code.


## Test technique Angular
Visiteur de profil GitHub :

GitHub API:

* https://api.github.com/users ===> OBTENIR TOUS LES UTILISATEURS
* https://api.github.com/users/{login} ==> OBTENIR LE PROFIL UTILISATEUR
* https://api.github.com/users/{login}/repos ==> OBTENIR LES DÉPÔTS DE L'UTILISATEUR
* https://api.github.com/users/{login}/followers ==> OBTENIR LES ABONNÉS DE L'UTILISATEUR
* https://api.github.com/repos/{login}/{repo_name} ==> OBTENIR LE DÉPÔT PAR NOM DE REPOSITOIRE ET NOM D'UTILISATEUR

### L'application permettra de :

* Informations sur le profil utilisateur : L'application devra afficher le nom de l'utilisateur, la photo de profil, la biographie, l'emplacement et d'autres informations disponibles publiquement sur leur profil GitHub.
* Liste de dépôts : L'application devra afficher une liste de dépôts possédés par l'utilisateur, y compris le nom du référentiel, la description et le nombre d'étoiles.
* Abonnés : L'application devra afficher une liste d'abonnés pour l'utilisateur, y compris leur nom et leur photo de profil.
* Statistiques sur les dépôts : Pour chaque dépôt, l'application devra afficher le nombre (commits, issues, pull requests), ainsi qu'un graphique de l'activité du dépôt au fil du temps.
* Fonctionnalité de recherche : L'application devra permettre aux utilisateurs de rechercher un utilisateur GitHub spécifique par nom d'utilisateur, et afficher les informations de son profil et ses dépôts.

##### Technologies et utilitaires à utiliser :

* Angular (Frontend Framework)
* NgRx (state management)

##### Le plus important de ce test est d'écrire un code propre et lisible.
