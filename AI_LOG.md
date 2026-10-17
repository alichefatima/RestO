# Journal de Développement IA — Application Rest'O

---

## [17-10-2026] - Initialisation du projet et gouvernance IA

* **Objectif :** Initialisation du dépôt Git, configuration de l'environnement Android Studio sous Windows 11, sécurisation de la connexion SSH avec GitHub, et mise en place du fichier d'encadrement IA (`GEMINI.md`).
* **Outil / Modèle :** Gemini plus (Etudiant).
* **Prompts :**
  * Prompt 1 (Configuration & Connexion SSH) : *"Je suis sur Windows 11 avec Android Studio. Guide-moi pas à pas pour générer la clé SSH, lier mon compte GitHub et initialiser mon projet."*
  * Prompt 2 (Gestion d'erreur de sécurité Git) : *"J'ai obtenu ce message lors de l'exécution de `ssh -T git@github.com` : 'The authenticity of host github.com can't be established'. Que dois-je répondre et pourquoi ?"*
  * Prompt 3 (Organisation des fichiers de gouvernance) : *"Je veux renommer le fichier AGENTS.md en GEMINI.md pour refléter l'outil exact que j'utilise. Donne-moi la commande Git pour effectuer cette modification proprement."*

* **ce qui a été accepté :**
    * La structure par phases pour découper le projet jusqu'à la remise finale.
    * Le nom de paquetage `fr.paris8.resto` (conforme aux consignes du cours).
    * L'utilisation de la convention *Conventional Commits* (ex: `feat:`, `docs:`) pour garder un historique Git propre.
* **ce qui a été modifié :**
    * Renommer `AGENTS.md` en `GEMINI.md` à la racine pour cibler spécifiquement l'assistant Gemini.
    * Utilisation de la commande `git mv` au lieu d'une suppression/création manuelle afin de conserver le suivi dans Git.
* **ce qui a été rejeté :**
    * *(Rien à signaler pour cette séance)*

* **Erreurs introduites :** Aucune erreur de code ou de commande n'a été commise par l'assistant au cours de cette séance.