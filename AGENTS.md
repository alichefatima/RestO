# Instructions de développement pour Rest'O

## Présentation du projet
Application Android Kotlin avec Jetpack Compose pour la recherche de recettes de cuisine à partir d'ingrédients (TheMealDB), stockage local de favoris (Room) et minuteur de cuisson.

## Directives d'architecture et de code
- Langage : Kotlin avec typage strict et immutabilité prioritaire (`val`).
- UI : Jetpack Compose uniquement (Material 3). Pas de fichiers XML de layout.
- Architecture : Séparation stricte UI Layer -> ViewModel/StateFlow -> Repository -> Data Source (Room/Retrofit).
- Sécurité : Jamais de clés d'API ou de secrets dans le code ou versionnés sur Git (utiliser `local.properties`).
- Qualité : Traiter les états de chargement, d'erreur et les données vides ("empty states").