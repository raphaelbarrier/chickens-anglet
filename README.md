# Chicken’s Anglet V5 — site complet

Site statique autonome : `index.html`, `vercel.json` et `assets/`.

## Déploiement
Décompresser le ZIP, déposer tous les fichiers et le dossier `assets` à la racine du dépôt GitHub, puis importer sur Vercel (Framework : Other ; Root Directory : `./`).

## Commandes et paiements
Le panier et le bon de commande fonctionnent dans le navigateur. **Aucune commande n’est envoyée au restaurant.** Le bon peut être copié pour demander une confirmation. Le paiement en ligne (carte/PayPal/Apple Pay) est visible comme futur moyen de paiement, mais désactivé : aucune donnée bancaire n’est collectée.

Pour activer les commandes réelles, connecter un backend avec stockage des commandes, notifications au restaurant et suivi des statuts. Pour les paiements, créer les comptes marchands Stripe et/ou PayPal, utiliser leurs pages de paiement hébergées, puis vérifier les webhooks côté serveur avant de confirmer la commande. Ne jamais intégrer une clé secrète dans `index.html`.

Les images des plats sont des illustrations générées par IA. Prix et horaires à confirmer auprès du restaurant avant publication officielle.
