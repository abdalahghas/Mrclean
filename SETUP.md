# État et installation du dépôt Mr Clean+

Ce dépôt est **incomplet** : il contient des fichiers de configuration Next.js, mais pas les sources `src/`, les traductions ni les ressources nécessaires. Il ne peut actuellement pas être lancé comme une application web.

## Avant une installation locale

1. Obtenir et ajouter le code source partageable du projet, avec l’accord du client si nécessaire.
2. Retirer les secrets, clés API, informations privées et fichiers générés avant publication.
3. Vérifier les versions de Node.js et les dépendances indiquées dans `package.json`.
4. Une fois le code complet présent, exécuter `npm ci`, puis `npm run dev` et `npm run build` pour valider le projet. Ces commandes ne sont **pas** garanties fonctionnelles dans l’état actuel du dépôt.

Ne pas confondre les fonctionnalités envisagées dans la documentation historique avec celles démontrées par ce dépôt public.
