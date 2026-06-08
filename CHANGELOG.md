# Journal des modifications — Mission STMG

Application web pédagogique (serious game) pour les STMG.
Fichier unique `index.html` — à déposer tel quel sur GitHub Pages.

---

## Version 2.0 — juin 2026

### ✨ Nouveautés majeures

**Quatre nouvelles matières (programmes officiels)**
- **Droit — 1ʳᵉ** (BO spécial n°1 du 22/01/2019) — 4 thèmes, 31 notions.
- **Économie — 1ʳᵉ** (BO spécial n°1 du 22/01/2019) — 5 thèmes, 28 notions.
- **Droit — Terminale** (BO spécial n°8 du 25/07/2019) — 4 thèmes, 27 notions.
- **Économie — Terminale** (BO spécial n°8 du 25/07/2019) — 4 thèmes, 30 notions.

Chaque matière propose 8 jeux par thème, des notions à double explication
(définition académique + version simplifiée), le programme officiel,
des études de documents et des ressources.

**Nouvelle matière transversale : Grand oral 🎤**
- Matière indépendante (4 étapes : comprendre l'épreuve, choisir sa question,
  structurer l'exposé, réussir le jour J).
- Format conforme : 20 min de préparation + 10 min d'exposé + 10 min d'entretien,
  jury de 2 professeurs, support non noté, coefficient 14 (12 dès 2027), 5 critères.
- Deux exercices spécifiques :
  - **Construis ta problématique 🎯** : transforme une question de gestion en
    problématique de Grand oral, en 3 étapes guidées.
  - **L'exposé dans l'ordre 🔢** : remets les étapes de l'exposé dans le bon ordre.
- Simulation « jour J » avec jauges adaptées (Clarté, Conviction, Connaissances, Aisance).

### 🎲 Améliorations du gameplay

- **Ordre des réponses aléatoire** dans tous les QCM (Intrus, Flash, Cas, Étude de docs)
  et pour toutes les matières : la bonne réponse change de position à chaque partie.
- **Écran de consigne avant chaque jeu** : objectif, déroulé et conseil expliqués
  simplement avant de commencer.
- **Jeu « Cas » enrichi** : la conséquence de chaque décision est explicitée à chaque
  étape, et un **bilan final récapitule toutes les décisions prises et leur impact**.
- Libellés de jauges et message de bilan de la simulation **personnalisables par matière**.

### 📚 Ressources et méthode

- **Fiches méthodo dédiées au Droit** (cas pratique/syllogisme, qualification des faits,
  analyse d'un arrêt, aborder un sujet) — 1ʳᵉ et Terminale.
- **Fiches méthodo dédiées à l'Économie** (lire un document statistique, calcul économique,
  argumentation AEI, aborder un sujet) — 1ʳᵉ et Terminale.
- **Fiches méthodo dédiées au Grand oral** (comprendre l'épreuve, formuler sa question,
  structurer l'exposé, réussir le jour J).
- Liens institutionnels fiables : Légifrance, Vie-publique.fr (Droit) ; INSEE, Citéco
  (Économie) ; éduscol (Grand oral). Toutes les fiches sont éditables par le professeur.

### ✏️ Éditeur professeur

- Les deux exercices du Grand oral (**Construis ta problématique**, **L'exposé dans
  l'ordre**) sont désormais **entièrement éditables** depuis l'interface professeur :
  modification des questions de gestion, des trois étapes guidées, de la problématique
  finale, et réorganisation des étapes de l'exposé (boutons ▲▼). Options visibles
  uniquement pour la matière Grand oral.

### 🎤 Plus de mises en situation (Grand oral)

- Simulation « jour J » portée à **10 situations par étape** (le maximum).
- Une **question de gestion** supplémentaire par étape pour « Construis ta problématique »
  (3 par étape) et un **exposé** supplémentaire pour « L'exposé dans l'ordre » (3 par étape).

### 📊 Affichage des jauges (Mission Dirigeant & simulation « jour J »)

- Pendant la partie, chaque indicateur affiche désormais en continu, à **chaque étape** :
  l'emoji, son **titre court**, sa **barre de progression** et son **pourcentage** coloré.
- L'élève visualise immédiatement l'impact de chaque décision, sans attendre le bilan final.
- Valable pour les 8 matières (Trésorerie · Part de marché · Image · Emplois pour les
  matières « entreprise » ; Clarté · Conviction · Connaissances · Aisance pour le Grand oral).

### 🧱 Technique

- 8 matières au total : Management, SDGN, MSDGN Tle, Droit 1ʳᵉ, Économie 1ʳᵉ,
  Droit Tle, Économie Tle, Grand oral.
- Les nouvelles matières s'ajoutent automatiquement au menu, à l'éditeur professeur
  et au tableau de bord. Compatibilité ascendante des données conservée (migration).
- Aucune dépendance externe ajoutée : le fichier reste un `index.html` autonome.

---

*Conformité : programmes officiels (BO) ; contextualisation Réunion 974 ;
double explication systématique des notions.*
