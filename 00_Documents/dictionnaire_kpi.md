# 📘 Dictionnaire des KPIs – Projet BI Commercial

Ce dictionnaire liste les principaux indicateurs clés utilisés dans le projet décisionnel.

| Nom du KPI                  | Description métier                                           | Formule de calcul                             | Source(s) de données           | Unité        |
|----------------------------|--------------------------------------------------------------|-----------------------------------------------|-------------------------------|--------------|
| Chiffre d'affaires (CA)    | Montant total des ventes réalisées                          | Somme(prix × quantité vendue)                 | Ventes (CSV/Excel)            | FCFA         |
| Panier moyen               | Montant moyen dépensé par commande                          | CA / Nombre de commandes                      | Ventes                        | FCFA         |
| Nombre de commandes        | Total des commandes enregistrées                            | Nombre de lignes de vente                     | Ventes                        | unités       |
| Taux de fidélisation       | Proportion de clients qui reviennent                        | (Clients récurrents / Clients totaux) × 100   | Ventes + Fichier clients      | %            |
| Taux de conversion         | Pourcentage de leads devenus clients                        | (Nombre de clients / Nombre de leads) × 100   | CRM / Commercial              | %            |
| Marge brute                | Différence entre CA et coût de revient                      | CA - Coût d’achat                             | Ventes + Produits             | FCFA         |
| Taux de retour             | Part des produits retournés après achat                     | (Produits retournés / Produits vendus) × 100  | Ventes / SAV                  | %            |
| CA par commercial          | Performance individuelle des vendeurs                       | CA filtré par vendeur                         | Ventes                        | FCFA         |
| CA par région              | Analyse géographique des ventes                             | CA filtré par région                          | Ventes + Géographie           | FCFA         |
| Produit le plus vendu      | Identifier le produit dominant                              | Produit avec quantité vendue max              | Ventes                        | Nom produit  |
| CA vs Objectif             | Écart entre vente réelle et objectif fixé                   | (CA réel / Objectif) × 100                    | Ventes + Objectifs commerciaux| %            |
| Stock moyen                | Quantité moyenne de produits disponibles                    | Moyenne du stock sur période                  | Stock                         | unités       |
| Taux de rupture            | Fréquence des produits indisponibles                        | (jours de rupture / période totale) × 100     | Stock                         | %            |
| Délai de réapprovisionnement | Temps moyen entre commande et réception stock              | Date réception - date commande                | Stock / Logistique            | jours        |
| ROI des campagnes          | Rentabilité des campagnes marketing                         | (CA généré / Budget campagne) × 100           | Ventes + Marketing            | %            |

