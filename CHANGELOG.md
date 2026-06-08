# Journal des modifications — Mission STMG

Application web pédagogique (serious game) pour les STMG.
Fichier unique `index.html` — à déposer tel quel sur GitHub Pages.

---

## Version 3.0 — juin 2026

### ✨ Nouveautés majeures — les 4 enseignements spécifiques de Terminale

L'application couvre désormais **13 matières**. Ajout des **4 enseignements
spécifiques de terminale STMG** (BO spécial n°8 du 25/07/2019), au choix de l'élève :

- **Spé Mercatique 🛍️** (MKT) — 4 thèmes : connaître les consommateurs, étudier
  le marché, construire l'offre (marchéage), communiquer et fidéliser.
- **Spé Gestion et finance 💶** (FIN) — 3 thèmes : appliquer les règles comptables,
  analyser la situation de l'entreprise, accompagner la prise de décision.
- **Spé Ressources humaines et communication 👥** (RHC) — 3 thèmes : individu/groupe
  et communication, motivation et mobilisation des compétences, cohésion et QVT.
- **Spé Systèmes d'information de gestion 🖥️** (SIG) — 4 thèmes : organisation et
  numérisation, données et information, sécurité/RGPD/processus, collaboration et décision.

Chaque spécialité propose le **contenu complet** identique aux autres matières :
notions à **double explication** (définition académique + version simplifiée ✨),
programme officiel, et **10 jeux par thème** — les 8 jeux habituels
(Trieur, Memory, Flash, Vrai/Faux, Intrus, Étude de docs, Cas, Mission) **plus
les 2 jeux Grand oral** (Construis ta problématique 🎯 + L'exposé dans l'ordre 🔢).
Contenu ancré dans le contexte réunionnais (Air Austral, Ravate, Edena, Isautier,
Groupe Caillé, Royal Bourbon, CHU, etc.).

### 🎨 Présentation
- Dans le menu de choix des matières, les 4 spécialités sont **regroupées en fin
  de liste** et signalées par une **famille de couleurs distincte**
  (rose / fuchsia / magenta / violet : `#e11d48`, `#c026d3`, `#db2777`, `#9333ea`),
  pour les identifier d'un coup d'œil comme « enseignements spécifiques ».
- Chaque spécialité dispose de son **onglet Intro** avec un encart **vidéo
  d'introduction à venir** (à compléter par le professeur via l'éditeur), et de
  jauges de Mission adaptées à son domaine
  (ex. SIG : 🔐 Sécurité / ⚙️ Performance / 📈 Valeur / 🤝 Collaboration).

### ✅ Validation
- Rendu vérifié sur les **13 matières** : **425 écrans de jeu** testés, **0 erreur**.
- Aucune régression sur les 9 matières existantes.

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

### 🆕 Nouvelle matière d'introduction & confort de jeu

- **Découverte STMG (2ᵈᵉ)** : matière d'initiation placée en tête, conforme au programme
  de l'option Management & gestion de seconde (BO spécial n°1 du 22/01/2019). Parcours en
  4 étapes (entreprendre · organiser et décider · évaluer et évoluer · premiers pas vers la
  1ʳᵉ), avec un **diaporama d'accueil** et les 8 jeux par étape.
- Texte d'accueil mis à jour pour refléter les **9 matières** (de la 2ᵈᵉ à la terminale).
- Jeu « **Le Trieur** » : chaque colonne affiche désormais une **courte explication** sous
  son titre, pour toutes les matières.

### 🔓 Déblocage des matières (verrou pédagogique)

- Bouton **« Débloquer tous les thèmes »** dans chaque matière : une fenêtre demande un
  mot de passe pour ouvrir d'un coup tous les thèmes et exercices.
- Nouveau menu professeur **« 🔑 Mots de passe »** : affiche et permet de modifier le mot
  de passe de chaque matière (valeurs par défaut fournies, thème STMG).
- Remarque : ce mot de passe est un simple verrou pédagogique (visible dans le code de la
  page), ce n'est pas une protection sécurisée.

### 👤 Comptes élèves & reprise de progression

- Les identifiants (pseudonyme, nom, prénom, classe) ne tiennent plus compte de la
  **casse** : un élève qui se reconnecte en variant majuscules/minuscules retrouve son
  compte et sa progression, sans doublon.
- Message sur la page de connexion rappelant que la **progression est sauvegardée** et se
  reprend avec le même pseudonyme et la même classe.

### 🎬 Intro éditable & éditeur de texte enrichi

- Chaque matière peut recevoir une **introduction** (texte, diaporama, vidéo) éditable
  depuis l'espace professeur (banque « 🎬 Intro de la matière »), affichée dans un onglet
  « Intro » avant les jeux.
- L'éditeur de texte intègre l'insertion de **vidéos YouTube** (lecteur responsive) et de
  **fichiers audio** (lecteur intégré).

### 🧱 Technique

- 8 matières au total : Management, SDGN, MSDGN Tle, Droit 1ʳᵉ, Économie 1ʳᵉ,
  Droit Tle, Économie Tle, Grand oral.
- Les nouvelles matières s'ajoutent automatiquement au menu, à l'éditeur professeur
  et au tableau de bord. Compatibilité ascendante des données conservée (migration).
- Aucune dépendance externe ajoutée : le fichier reste un `index.html` autonome.

---

*Conformité : programmes officiels (BO) ; contextualisation Réunion 974 ;
double explication systématique des notions.*
