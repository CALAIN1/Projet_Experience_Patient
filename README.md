# Analyse de l'Expérience Patient & Plan d'Action Logistique

## Présentation du Projet
Ce projet présente une analyse de bout en bout de l'expérience patient réalisée sur un volume de **1 012 avis textuels**. L'objectif est d'identifier les goulets d'étranglement logistiques et opérationnels d'un centre hospitalier fictif sous tension afin de proposer des pistes d'amélioration concrètes.

Le pipeline de données simule un environnement de production réel : stockage dans une base de données relationnelle, extraction, nettoyage, modélisation de données et data visualisation.

---

## Stack Technique & Compétences Clés
* **Base de données :** MySQL (PhpMyAdmin) - Gestion des volumes, requêtage et duplication algorithmique de données.
* **Traitement de données :** Excel / CSV - Structuration et nettoyage des données textuelles.
* **Data Visualisation :** Power BI - Modélisation en étoile, création de mesures DAX et conception d'un tableau de bord dynamique interactif.
* **Restitution :** Rédaction d'un rapport de synthèse de niveau consulting.

---

## Indicateurs Clés de Performance (KPIs)
* **Volume total analysé (N) :** 1 012 avis patients
* **Note Moyenne Générale :** **2,87 / 5**  *(Seuil d'alerte critique)*
* **Répartition du Sentiment Global :**
  * 🔴 **Négatif :** 50,2 % (508 avis)
  * 🟢 **Positif :** 43,58 % (441 avis)
  * 🟡 **Neutre :** 6,23 % (63 avis)

---

## Principaux Insights Extraits

1. **Le Temps d'Attente (Axe Critique - 67,02 % d'avis négatifs) :** C'est le point noir majeur. Les verbatims mettent en évidence une saturation des urgences (attentes supérieures à 3h) et un engorgement des secrétariats médicaux.
2. **La Relation Personnel & Communication (Axe Bipolaire - 37,50 % d'avis négatifs) :** Contraste fort. Le personnel soignant (médecins, infirmières) est jugé très compétent et bienveillant, tandis que l'accueil administratif est critiqué pour sa froideur lors des pics de stress.
3. **Le Confort & l'Hôtellerie (Axe Logistique - 50,00 % d'avis négatifs) :** Plaintes marquées concernant la propreté générale des infrastructures et la qualité/température des repas servis en chambre.

---

## Recommandations & Perspectives Data
* **Court Terme :** Déploiement de bornes de régulation des files d'attente à l'accueil et formation à la gestion du stress en première ligne.
* **Études Data Futures :** * Analyse de corrélation temporelle pour cartographier précisément les pics d'insatisfaction selon les jours et heures d'affluence.
  * Intégration d'un système automatisé de calcul du *Net Promoter Score (NPS)* à la sortie des patients.

---

## Structure du Répertoire
* `01_donnees/` : Fichiers sources `BRUT` et `Nettoye` (1 012 lignes).
* `02_Base_de_donnees/` : Script de structure SQL de la table `avis_patients`.
* `03_Dashboard_BI/` : Fichier `.pbix` de l'application Power BI interactive.
* `04_Rapport_Word/` : Rapport exécutif officiel au format Word (.docx).

---
**Auteur :** Carole Alain — Consultante Data Analyst

