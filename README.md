# Création d'une base de données immobilière — SQL

Conception et création d'une base de données relationnelle pour stocker et
requêter des biens immobiliers.

---

## Contexte / besoin métier

Une agence immobilière souhaite disposer d'une base structurée pour gérer ses
biens, ses clients et ses transactions, et pouvoir interroger les données
efficacement.

## Données

- **Source** : jeu de données fourni par l'agence
- **Entités** : biens, clients, agents, transactions
- **Qualité** : données à structurer depuis des fichiers plats
- **Limites** : périmètre limité, pas de données réelles de marché

## Démarche

1. **Modélisation** : schéma relationnel (tables, clés primaires/étrangères)
2. **Création** : scripts SQL de création de tables 
3. **Insertion** : import des données dans la base
4. **Requêtes** : sélections, jointures, agrégations, sous-requêtes
5. **Analyses** : prix moyen par zone, turnover, biens par agent

## Résultats

- Base de données relationnelle opérationnelle
- Requêtes SQL répondant aux besoins métier (statistiques, recherches filtrées)
- Structure normalisée et extensible

## Limites & pistes

- Pas d'interface utilisateur
- Données statiques, pas de mise à jour en temps réel
- **Pistes** : ajouter des vues et procédures stockées, connecter à une
  application web, intégrer des données de marché externes
