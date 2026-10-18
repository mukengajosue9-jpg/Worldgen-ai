# Worldgen-ai

Application web en français pour :
- présenter une photo de billet et afficher des conseils de vérification prudents ;
- repérer quelques signaux d'alerte dans un message financier (analyse locale par règles simples) ;
- calculer un solde de budget.

## Important
Cette première version **n'authentifie pas les billets** et ne contient pas encore de modèle d'intelligence artificielle entraîné. Une photo ne suffit pas pour certifier un billet. L'analyse de message est une aide simple et peut manquer des fraudes ou signaler un message légitime. Ne partagez pas de codes secrets ni de données bancaires.

## Publier sur GitHub Pages avec un téléphone
1. Téléchargez et décompressez `Worldgen-ai.zip`.
2. Ouvrez votre dépôt GitHub, branche `main`.
3. Choisissez **Add file → Upload files** et téléversez le contenu du dossier (pas seulement le ZIP).
4. Appuyez sur **Commit changes**.
5. Allez dans **Settings → Pages** et choisissez **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
6. Attendez quelques minutes et ouvrez l'adresse Pages indiquée par GitHub.

## Version Android
La version web est conçue comme une PWA installable depuis un navigateur compatible. Un APK Android natif n'est pas inclus dans ce ZIP. Pour fabriquer un APK natif, il faut une étape de compilation Android (par exemple Capacitor + Android SDK); le site web publié ne se transforme pas automatiquement en APK.

## Confidentialité
La photo, le texte de message et les montants sont traités dans le navigateur par cette version et ne sont pas envoyés par le code de l'application à un serveur. Évitez toutefois de saisir des informations personnelles sensibles.
