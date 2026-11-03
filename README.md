# CoiffGo — Application Expo (démo)

## Démarrage
Installer Node.js LTS, puis dans le dossier du projet :

```bash
npm install
npx expo start
```

Scanner le QR code dans Expo Go sur iPhone. Pour le navigateur : `npm run web`.

## Inclus
- Recherche de coiffeurs fictifs et profils
- Demande de réservation, suivi des statuts
- Tableau de bord coiffeur pour accepter/refuser (simulation)
- Portfolio de coupes : sélection de photos, légendes et suppression
- Stockage local AsyncStorage

## Important
Cette version est une démonstration locale. Aucun coiffeur réel n'est contacté ; les comptes, les paiements, la base de données, la publication des photos en ligne et les notifications ne sont pas encore intégrés. Les profils et avis affichés sont fictifs. La validation se simule sur le même appareil. Les images choisies restent locales et ne sont pas téléversées sur un serveur.

## Étape suivante
Mettre en place une base de données sécurisée, l'authentification client/coiffeur et le stockage des photos en ligne avant un déploiement public.
