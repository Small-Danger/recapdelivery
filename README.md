# Gestionnaire de Livraisons

Une application web simple et efficace pour gérer les livraisons de restaurant et les livraisons simples.

## Fonctionnalités

- **Deux modes de livraison** :
  - Mode Restaurant : Gestion des livraisons avec montant nourriture et frais de livraison
  - Mode Simple : Gestion des livraisons simples avec frais de livraison uniquement

- **Gestion des paiements** :
  - Suivi du statut de paiement de chaque livraison
  - Possibilité de marquer les livraisons comme payées/non payées
  - Règlements partiels avec le restaurant

- **Suivi détaillé** :
  - Vue chronologique des livraisons
  - Historique des règlements restaurant
  - Résumé journalier avec statistiques

- **Interface utilisateur** :
  - Design moderne et responsive
  - Mode sombre/clair
  - Interface en français
  - Devise en Dirham (MAD)

## Installation

1. Clonez le dépôt :
```bash
git clone https://github.com/Small-Danger/recapdelivery.git
```

2. Ouvrez le fichier `index.html` dans votre navigateur

## Utilisation

1. Choisissez le mode de livraison (Restaurant ou Simple)
2. Entrez les montants pour chaque livraison
3. Utilisez le bouton "Règlement Restaurant" pour effectuer des règlements partiels
4. Consultez les détails de la journée pour voir le récapitulatif
5. Clôturez la journée une fois toutes les livraisons payées

## Technologies utilisées

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla)
- LocalStorage pour la persistance des données

## Licence

MIT 