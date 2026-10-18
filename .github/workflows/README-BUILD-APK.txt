Worldgen-ai — préparation APK

Ce paquet contient les fichiers nécessaires pour que GitHub Actions compile un APK Android de test à partir de index.html.

Installation dans le dépôt existant :
1. Décompressez ce ZIP.
2. Ajoutez package.json et capacitor.config.json à la racine du dépôt, au même niveau que index.html.
3. Ajoutez .github/workflows/build-apk.yml en conservant exactement les dossiers .github/workflows/.
4. Enregistrez les modifications sur la branche main.
5. Dans GitHub, ouvrez Actions. Choisissez Build Worldgen-ai APK, puis Run workflow. Un push sur main lance aussi la compilation automatiquement.
6. Lorsque le travail est terminé, ouvrez-le, descendez à Artifacts et téléchargez Worldgen-ai-debug-apk. Décompressez le fichier téléchargé pour obtenir app-debug.apk.

Important : ce ZIP est le fichier de configuration de compilation, pas l'APK déjà compilé. L'APK sera généré par GitHub Actions après l'ajout des fichiers. C'est un APK debug de test, pas une version signée prête pour Google Play. L'application actuelle n'authentifie pas les billets avec une IA réelle.
