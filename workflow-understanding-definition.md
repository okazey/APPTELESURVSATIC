# Workflow Design Thinking — Phases Understanding & Definition

**Sujet** : Conception et mise en place d'un système de télésurveillance des évaluations à l'UFR SATIC  
**Étudiants** : Serigne Fallou FAYE & Lamine KOUYATE — L3 D2A, Université Alioune Diop de Bambey  
**Durée estimée** : 3 semaines

---

## 1. PHASE 1 : UNDERSTANDING (Empathie / Compréhension du problème)

### 1.1 Objectif de la phase

Comprendre en profondeur l'écosystème actuel de la surveillance des évaluations à l'UFR SATIC :

- **Qui** sont les acteurs impliqués (étudiants, enseignants, surveillants, administration, service informatique) ?
- **Comment** se déroule actuellement la surveillance des examens ?
- **Quels** sont les problèmes vécus par chaque acteur ?
- **Quelles** sont les contraintes techniques, humaines et institutionnelles ?

À la fin de cette phase, vous devez avoir une vision claire et documentée du terrain, sans encore proposer de solution.

---

### 1.2 Sous-étapes

| # | Sous-étape | Durée | Responsable |
|---|-----------|-------|-------------|
| 1 | Recherche documentaire | 2 jours | Fallou |
| 2 | Cartographie des parties prenantes | 1 jour | Lamine |
| 3 | Élaboration des guides d'entretien | 1 jour | Fallou + Lamine |
| 4 | Interviews terrain | 4–5 jours | Fallou + Lamine (en parallèle) |
| 5 | Observation terrain (période d'examens ou simulation) | 1–2 jours | Fallou + Lamine |
| 6 | Enquête quantitative (questionnaire) | 3 jours (diffusion + collecte) | Lamine |
| 7 | Synthèse et création des livrables d'empathie | 2 jours | Fallou + Lamine |

---

### 1.3 Actions concrètes à mener

#### Étape 1 — Recherche documentaire (Jour 1–2)

**Actions :**

- Recenser les articles, mémoires et rapports existants sur la télésurveillance d'examens (proctoring) en milieu universitaire, en particulier en Afrique
- Rechercher les solutions techniques existantes : Proctorio, ExamSoft, Safe Exam Browser, solutions open-source (e.g. Open Exam Suite)
- Identifier les réglementations sénégalaises sur la vidéosurveillance et la protection des données (loi 2008-12 sur la protection des données personnelles, CDP – Commission des Données Personnelles)
- Consulter les PV de conseils de département ou d'UFR mentionnant les problèmes de fraude
- Documenter l'infrastructure réseau et matérielle actuelle de l'UFR SATIC (salles informatiques, Wi-Fi, caméras existantes)

**Livrables :**
- Fiche de synthèse documentaire (2–3 pages max)
- Tableau comparatif de 4–5 solutions de télésurveillance existantes (nom, fonctionnalités, coût, prérequis techniques, compatibilité contexte SATIC)

**Outils :** Google Scholar, HAL, mémoires en ligne (UCAD, UVS), sites éditeurs (Proctorio, ExamSoft), site CDP Sénégal

---

#### Étape 2 — Cartographie des parties prenantes (Jour 3)

**Actions :**

Identifier et classer tous les acteurs concernés par la surveillance des évaluations :

| Catégorie | Acteurs | Rôle dans la surveillance | Niveau d'influence |
|-----------|---------|--------------------------|-------------------|
| **Étudiants** | L1, L2, L3, Master | Surveillés | Faible (mais utilisateurs finaux) |
| **Enseignants** | Responsables de modules | Conception sujets, parfois surveillance | Moyen |
| **Surveillants** | Enseignants ou vacataires | Surveillance directe en salle | Élevé |
| **Administration** | Chef de département, Directeur UFR, Scolarité | Organisation, décision | Très élevé |
| **Service informatique** | Techniciens SATIC | Infrastructure, maintenance | Élevé |
| **Direction UAD** | Rectorat, DISI | Politique numérique, budgets | Très élevé |

**Livrable :** Carte des parties prenantes (schéma en cercles concentriques : au centre = utilisateurs directs, en périphérie = décideurs)

**Outil :** Dessin à la main, Canva, ou draw.io (gratuit)

---

#### Étape 3 — Élaboration des guides d'entretien (Jour 4)

Préparer **4 guides d'entretien semi-directifs** adaptés à chaque profil :

##### Guide A — Étudiants (durée : 15–20 min)

1. Comment se passent les examens pour toi actuellement ? Décris-moi une session type.
2. As-tu déjà été témoin de tentatives de fraude ? Si oui, comment ça s'est passé ?
3. Comment perçois-tu la surveillance actuelle ? (suffisante, excessive, laxiste ?)
4. Que penserais-tu d'un système de caméras dans les salles d'examen ?
5. Quelles seraient tes craintes principales concernant un tel système ?
6. As-tu accès facilement à internet / un smartphone pendant les périodes d'examen ?
7. Selon toi, qu'est-ce qui serait la solution la plus juste pour lutter contre la fraude ?
8. Y a-t-il des examens qui se passent mieux que d'autres ? Pourquoi ?

##### Guide B — Enseignants / Surveillants (durée : 20–25 min)

1. Comment organisez-vous la surveillance de vos examens ?
2. Quelles sont les principales difficultés rencontrées pendant la surveillance ?
3. Quels types de fraude avez-vous observés ? Fréquence estimée ?
4. Comment gérez-vous un cas de fraude flagrant ?
5. Que pensez-vous de l'introduction de la vidéosurveillance dans les salles d'examen ?
6. Quels outils numériques utilisez-vous déjà dans votre enseignement ?
7. Quelles conditions devraient être remplies pour qu'un système de télésurveillance soit acceptable ?
8. Quels sont les examens les plus problématiques (effectifs, matière, format) ?

##### Guide C — Administration / Scolarité (durée : 20–25 min)

1. Comment est organisé le processus de surveillance des évaluations à l'UFR ?
2. Combien de cas de fraude sont officiellement signalés par session ?
3. Quels moyens sont actuellement alloués à la surveillance ?
4. Existe-t-il des projets en cours pour moderniser la surveillance ?
5. Quel budget pourrait être consacré à un système de télésurveillance ?
6. Quels sont les principaux obstacles institutionnels à un tel projet ?
7. Quelle est la politique actuelle de l'université en matière de vidéosurveillance ?

##### Guide D — Service informatique (durée : 15–20 min)

1. Quel est l'état actuel de l'infrastructure réseau de l'UFR SATIC ?
2. Existe-t-il déjà des caméras installées ? Si oui, quel usage ?
3. Quelle est la bande passante internet disponible ?
4. Quels équipements informatiques sont disponibles (serveurs, stockage, postes) ?
5. Quelles contraintes techniques anticipez-vous pour un système de vidéosurveillance ?
6. Quel type de maintenance pourrait être assuré en interne ?

**Livrable :** 4 guides d'entretien imprimés + formulaire de consentement oral

---

#### Étape 4 — Interviews terrain (Jours 5–9)

**Plan d'interviews :**

| Profil | Nombre visé | Responsable | Méthode |
|--------|------------|-------------|---------|
| Étudiants | 8–10 | Fallou (5) + Lamine (5) | Entretien individuel, 15–20 min |
| Enseignants | 4–5 | Fallou | Entretien individuel, 20 min |
| Surveillants | 2–3 | Lamine | Entretien individuel, 20 min |
| Administration | 2–3 | Fallou + Lamine (ensemble) | Entretien formel, 25 min |
| Service info | 1–2 | Lamine | Entretien technique, 15 min |

**Règles de conduite :**

- Toujours demander le **consentement oral** avant de commencer (enregistré ou noté)
- **Enregistrer** avec le téléphone (avec accord) ET prendre des notes manuscrites
- Ne pas orienter les réponses : poser des questions ouvertes, relancer avec "pourquoi ?", "pouvez-vous donner un exemple ?"
- Noter les **émotions** et **réactions non verbales** (frustration, hésitation, enthousiasme)
- Conclure chaque entretien par : "Y a-t-il autre chose que vous aimeriez ajouter ?"

**Livrable :** Fichier de transcription par entretien (résumé structuré, pas nécessairement verbatim)

**Outils :** Téléphone (dictaphone), carnet de notes, Google Docs pour les transcriptions

---

#### Étape 5 — Observation terrain (Jours 10–11)

**Actions :**

Si une session d'examen est en cours ou simulable :

- **Observer** sans intervenir pendant au moins 2 sessions d'examen différentes
- Utiliser une **grille d'observation** :

| Critère | Observations |
|---------|-------------|
| Disposition de la salle (taille, nombre de places, espacement) | |
| Nombre de surveillants vs nombre d'étudiants | |
| Comportement des étudiants (concentration, agitation, échanges) | |
| Comportement des surveillants (circulation, attention, téléphone) | |
| Points aveugles de surveillance (coins, fond de salle) | |
| Présence de matériel interdit (téléphones, oreillettes) | |
| Infrastructure existante (prises, Wi-Fi, caméras) | |
| Éclairage et conditions de captation vidéo | |
| Durée effective de surveillance vs durée prévue | |

- **Photographier** (avec autorisation) les salles, le matériel, la disposition
- **Chronométrer** les temps morts, les incidents

**Livrable :** 2 rapports d'observation terrain (1 par session observée)

**Outils :** Grille imprimée, téléphone (photos + chrono), carnet

---

#### Étape 6 — Enquête quantitative (Jours 8–12, en parallèle des interviews)

**Actions :**

Créer un **questionnaire Google Forms** pour toucher un échantillon plus large (50–100 étudiants minimum).

**Structure du questionnaire :**

**Section 1 — Profil** (4 questions)
- Filière (D2A, SRT, LPCM, autre)
- Niveau (L1, L2, L3, Master)
- Genre
- Tranche d'âge

**Section 2 — Expérience des examens** (5 questions)
- "Comment évalues-tu l'organisation actuelle des examens ?" (Échelle 1–5)
- "As-tu déjà été témoin de fraude pendant un examen ?" (Oui / Non / Préfère ne pas répondre)
- "Quel type de fraude as-tu observé ?" (Choix multiples : copie sur voisin, antisèche, téléphone, communication orale, autre)
- "La surveillance actuelle est-elle efficace ?" (Échelle 1–5)
- "Quels examens sont les plus touchés par la fraude ?" (Réponse libre)

**Section 3 — Perception de la télésurveillance** (5 questions)
- "Serais-tu favorable à l'installation de caméras dans les salles d'examen ?" (Oui / Non / Sous conditions)
- "Quelles seraient tes principales craintes ?" (Choix multiples : vie privée, stress, erreur d'interprétation, stockage des images, autre)
- "Quelles conditions rendraient un tel système acceptable ?" (Réponse libre)
- "Penses-tu qu'un système de télésurveillance réduirait la fraude ?" (Échelle 1–5)
- "Préférerais-tu un autre moyen de lutte contre la fraude ?" (Réponse libre)

**Section 4 — Accès technologique** (3 questions)
- "As-tu un smartphone avec accès internet ?" (Oui / Non)
- "Comment évalues-tu la qualité du Wi-Fi à l'UFR ?" (Échelle 1–5)
- "Utilises-tu des outils numériques pour tes cours ?" (Oui / Non, lesquels)

**Diffusion :** Groupes WhatsApp des promotions, affichage QR code, distribution en présentiel

**Livrable :** Questionnaire en ligne + fichier de réponses exporté (CSV/Excel)

**Outil :** Google Forms (gratuit, accessible hors ligne pour la création)

---

### 1.4 Livrables de la Phase Understanding

#### Livrable 1 — Personas (2–3 personas)

Créer des profils fictifs mais réalistes basés sur les données collectées.

**Exemple — Persona 1 : Abdoulaye, étudiant L3 D2A**

| Champ | Description |
|-------|-------------|
| **Nom** | Abdoulaye N. |
| **Âge** | 23 ans |
| **Filière** | L3 D2A |
| **Contexte** | Étudiant sérieux, vient de Kaolack, vit en cité universitaire |
| **Frustrations** | "Je révise pendant des semaines et mon voisin copie tout pendant l'examen sans conséquence" |
| **Besoins** | Équité dans les évaluations, reconnaissance du mérite |
| **Craintes vis-à-vis de la télésurveillance** | "Je ne veux pas me sentir comme un suspect" |
| **Usage tech** | Smartphone Android, utilise WhatsApp et Google, Wi-Fi universitaire intermittent |
| **Citation clé** | "Si tout le monde est surveillé de la même manière, ça me va" |

Créer aussi : un persona enseignant/surveillant + un persona administration.

#### Livrable 2 — Carte d'empathie (1 par persona principal)

Pour chaque persona, remplir les 4 quadrants :

```
┌─────────────────────────────────────┐
│           CE QU'IL DIT              │
│ "La fraude est un vrai problème"    │
│ "Les surveillants ne peuvent pas    │
│  tout voir"                         │
├──────────────────┬──────────────────┤
│  CE QU'IL PENSE  │  CE QU'IL FAIT  │
│ "Le système est  │ Révise seul,    │
│  injuste pour    │ s'assoit devant │
│  ceux qui        │ pour être vu,   │
│  travaillent"    │ évite les       │
│                  │ voisins suspects│
├──────────────────┴──────────────────┤
│          CE QU'IL RESSENT           │
│ Frustration, sentiment d'injustice, │
│ méfiance envers le système actuel   │
└─────────────────────────────────────┘
```

#### Livrable 3 — Synthèse des insights

Document de 3–5 pages résumant les découvertes clés, organisé ainsi :

1. **Insights sur les pratiques actuelles** (comment ça se passe vraiment)
2. **Insights sur les problèmes** (fraude, manque de moyens, désorganisation)
3. **Insights sur les perceptions** (acceptabilité, craintes, attentes)
4. **Insights sur les contraintes** (techniques, financières, humaines, éthiques)
5. **Surprises et contradictions** (ce qu'on ne s'attendait pas à trouver)

---

## 2. PHASE 2 : DEFINITION (Définition claire du problème)

### 2.1 Objectif de la phase

Transformer les données brutes de la phase Understanding en une **formulation claire et exploitable du problème** à résoudre. À la fin de cette phase, vous devez pouvoir énoncer précisément :

- Quel problème vous résolvez
- Pour qui
- Pourquoi c'est important
- Quels sont les axes d'innovation prioritaires

---

### 2.2 Méthode de synthèse des données collectées

#### Étape 1 — Regroupement thématique (Jour 13)

**Actions :**

1. Imprimer ou recopier sur des post-its (réels ou virtuels) **tous les verbatims et observations clés** issus des interviews et questionnaires
2. Regrouper par **thèmes émergents**. Exemples de thèmes probables :
   - Fraude (types, fréquence, perception)
   - Surveillance actuelle (moyens, limites, efficacité)
   - Infrastructure (réseau, matériel, salles)
   - Éthique et vie privée (consentement, stockage, abus)
   - Organisation (planification, effectifs, coordination)
   - Acceptabilité (conditions, résistances, motivations)
3. Pour chaque thème, noter le **nombre de mentions** et le **niveau d'émotion** associé

**Outil :** Post-its physiques sur un mur, ou Miro/FigJam (version gratuite), ou simplement un tableau Google Sheets

**Livrable :** Diagramme d'affinité (photo du mur de post-its ou capture Miro)

---

#### Étape 2 — Identification des problèmes clés (Jour 14)

**Actions :**

À partir du diagramme d'affinité, formuler les **5 à 8 problèmes clés** identifiés.

**Format de formulation :**

> **[Acteur]** rencontre **[problème]** parce que **[cause]**, ce qui entraîne **[conséquence]**.

**Exemples concrets :**

1. > **Les surveillants** ne peuvent pas couvrir efficacement les grandes salles (100+ étudiants) **parce que** le ratio surveillant/étudiant est trop faible (1 pour 80+), **ce qui entraîne** des zones non surveillées où la fraude prolifère.

2. > **Les étudiants honnêtes** ressentent un sentiment d'injustice **parce que** les fraudeurs ne sont que rarement sanctionnés, **ce qui entraîne** une démotivation et une perte de confiance dans le système d'évaluation.

3. > **L'administration** ne dispose pas de preuves tangibles de fraude **parce que** la surveillance repose uniquement sur l'observation humaine subjective, **ce qui entraîne** des difficultés à appliquer le règlement disciplinaire.

4. > **Le service informatique** ne peut pas déployer de système numérique de surveillance **parce que** l'infrastructure réseau (Wi-Fi, bande passante, serveurs) est insuffisante, **ce qui entraîne** une dépendance totale aux méthodes manuelles.

5. > **Les enseignants** craignent que la vidéosurveillance crée un climat de méfiance **parce que** les étudiants associent caméra et intrusion dans la vie privée, **ce qui entraîne** une résistance au changement de la part du corps pédagogique.

**Livrable :** Liste des problèmes clés formulés (tableau)

---

#### Étape 3 — Formulation des "How Might We" (Jour 15)

Transformer chaque problème clé en une **question d'innovation** ouverte au format "How Might We" (Comment pourrions-nous…).

**Règles de formulation :**
- Ni trop large ("Comment pourrions-nous améliorer l'université ?") → inutile
- Ni trop étroit ("Comment pourrions-nous installer 10 caméras IP dans la salle 204 ?") → pas assez exploratoire
- Le bon niveau : orienté solution sans imposer une solution spécifique

**Exemples :**

| Problème clé | How Might We |
|-------------|-------------|
| Ratio surveillant/étudiant insuffisant | **Comment pourrions-nous** étendre la capacité de surveillance sans multiplier le personnel ? |
| Manque de preuves tangibles de fraude | **Comment pourrions-nous** documenter objectivement le déroulement des examens ? |
| Craintes liées à la vie privée | **Comment pourrions-nous** surveiller efficacement tout en respectant la dignité et la vie privée des étudiants ? |
| Infrastructure réseau insuffisante | **Comment pourrions-nous** concevoir un système de surveillance fonctionnel même avec une connectivité limitée ? |
| Résistance au changement | **Comment pourrions-nous** impliquer les étudiants et enseignants dans la co-conception du système pour favoriser l'adhésion ? |
| Absence de cadre réglementaire interne | **Comment pourrions-nous** établir un cadre d'utilisation transparent et éthique de la vidéosurveillance ? |

**Livrable :** 5–8 questions HMW priorisées

---

#### Étape 4 — Priorisation des problèmes (Jour 15–16)

Utiliser une **matrice Impact × Faisabilité** pour prioriser les HMW :

```
        IMPACT ÉLEVÉ
             │
     ┌───────┼───────┐
     │ ZONE  │ ZONE  │
     │ À     │ PRIO- │
     │ PLAN- │ RI-   │
     │ IFIER │ TAIRE │
     │       │  ★    │
─────┼───────┼───────┼─────
FAISA│       │       │FAISA
BILI │ ZONE  │ ZONE  │BILI
TÉ   │ À     │ QUICK │TÉ
FAIB │ ÉCAR- │ WINS  │ÉLEVÉE
LE   │ TER   │       │
     └───────┼───────┘
             │
        IMPACT FAIBLE
```

**Critères d'évaluation :**

| Critère | Indicateurs |
|---------|------------|
| **Impact** | Nombre d'acteurs concernés, gravité du problème, fréquence |
| **Faisabilité technique** | Compatible avec l'infrastructure SATIC ? Technologie disponible ? |
| **Faisabilité financière** | Coût estimé vs budget disponible |
| **Acceptabilité sociale** | Les utilisateurs seraient-ils prêts à l'adopter ? |
| **Faisabilité temporelle** | Réalisable dans le cadre du mémoire (quelques mois) ? |

Chaque HMW est notée de 1 à 5 sur chaque critère. Les 2–3 HMW prioritaires deviennent le cœur du projet.

**Livrable :** Matrice de priorisation remplie + justification des choix

---

### 2.3 Livrables de la Phase Definition

#### Livrable principal — Problem Statement final

Rédiger LE problem statement consolidé qui guidera tout le reste du mémoire.

**Format recommandé :**

> **Les [utilisateurs cibles]** de l'UFR SATIC ont besoin d'un moyen de **[besoin fonctionnel]** parce que **[insight clé issu du terrain]**.

**Exemple :**

> **Les acteurs du processus d'évaluation** (étudiants, enseignants, administration) **de l'UFR SATIC** ont besoin d'un **système de surveillance des examens fiable, objectif et respectueux de la vie privée**, parce que **le dispositif actuel, exclusivement humain, est insuffisant face aux effectifs croissants, ne fournit aucune preuve documentée, et génère un sentiment d'injustice chez les étudiants honnêtes**.

#### Livrable complémentaire — Axes d'innovation

Lister 3–4 axes d'innovation issus des HMW prioritaires :

1. **Axe Vidéosurveillance intelligente** : système de caméras avec enregistrement local, consultation a posteriori
2. **Axe Optimisation organisationnelle** : réaménagement des salles, protocoles de surveillance renforcés
3. **Axe Acceptabilité et éthique** : charte de télésurveillance, co-construction avec les parties prenantes
4. **Axe Résilience technique** : architecture fonctionnant en mode dégradé (stockage local si pas de réseau)

---

## 3. WORKFLOW GLOBAL

### 3.1 Timeline sur 3 semaines

| Jour | Activité | Responsable | Livrable |
|------|----------|-------------|----------|
| **J1–J2** | Recherche documentaire | Fallou | Fiche de synthèse + tableau comparatif solutions |
| **J3** | Cartographie parties prenantes | Lamine | Carte des parties prenantes |
| **J4** | Rédaction guides d'entretien | Fallou + Lamine | 4 guides + formulaire consentement |
| **J5–J7** | Interviews étudiants + enseignants | Fallou (enseignants) + Lamine (étudiants) | Transcriptions |
| **J8–J9** | Interviews admin + service info | Fallou + Lamine ensemble | Transcriptions |
| **J8–J12** | Diffusion questionnaire Google Forms | Lamine | Questionnaire + données collectées |
| **J10–J11** | Observation terrain (examens) | Fallou + Lamine | 2 rapports d'observation |
| **J12** | Création personas + cartes d'empathie | Fallou | 2–3 personas + cartes d'empathie |
| **J12** | Synthèse des insights | Lamine | Document de synthèse (3–5 pages) |
| **J13** | Regroupement thématique (diagramme d'affinité) | Fallou + Lamine | Diagramme d'affinité |
| **J14** | Formulation problèmes clés | Fallou + Lamine | Liste des problèmes clés |
| **J15** | Formulation HMW + priorisation | Fallou + Lamine | HMW priorisées + matrice |
| **J16** | Rédaction Problem Statement final + axes d'innovation | Fallou + Lamine | Problem Statement + axes |
| **J17–J18** | Relecture, mise en forme, validation encadreur | Fallou + Lamine | Dossier complet phases 1 & 2 |

---

### 3.2 Répartition des tâches

| Domaine | Fallou | Lamine |
|---------|--------|--------|
| **Recherche documentaire** | Rédaction synthèse | Relecture + compléments |
| **Guides d'entretien** | Guides B (enseignants) + C (admin) | Guides A (étudiants) + D (service info) |
| **Interviews** | Enseignants + admin | Étudiants + service info |
| **Questionnaire** | Relecture | Création + diffusion + analyse |
| **Observation terrain** | Salle 1 | Salle 2 |
| **Personas** | Rédaction | Relecture + validation |
| **Synthèse insights** | Relecture | Rédaction |
| **Diagramme d'affinité** | Co-construction | Co-construction |
| **Problem Statement** | Première version | Révision + finalisation |

**Principe** : chaque livrable a un **rédacteur principal** et un **relecteur**. Les étapes de synthèse (J13–J16) sont réalisées ensemble.

---

### 3.3 Checklist opérationnelle

#### Avant de commencer
- [ ] Valider le planning avec l'encadreur
- [ ] Obtenir une lettre d'autorisation de recherche du département (si nécessaire pour les interviews administration)
- [ ] Préparer le formulaire de consentement pour les interviews
- [ ] Créer un dossier Google Drive partagé (Fallou + Lamine + encadreur)
- [ ] S'assurer d'avoir : téléphone chargé, carnet, stylos, copies des guides

#### Phase Understanding
- [ ] Fiche de synthèse documentaire rédigée
- [ ] Tableau comparatif des solutions existantes complété
- [ ] Carte des parties prenantes dessinée
- [ ] 4 guides d'entretien validés par l'encadreur
- [ ] 15–20 interviews réalisées et transcrites
- [ ] Questionnaire Google Forms diffusé (objectif : 50+ réponses)
- [ ] 2 observations terrain documentées
- [ ] 2–3 personas créés
- [ ] Cartes d'empathie remplies
- [ ] Synthèse des insights rédigée

#### Phase Definition
- [ ] Diagramme d'affinité réalisé
- [ ] 5–8 problèmes clés formulés
- [ ] 5–8 questions HMW rédigées
- [ ] Matrice de priorisation remplie
- [ ] Problem Statement final validé
- [ ] Axes d'innovation définis
- [ ] Dossier relu et validé par l'encadreur

---

### 3.4 Erreurs fréquentes à éviter

| Erreur | Pourquoi c'est un problème | Comment l'éviter |
|--------|---------------------------|-----------------|
| **Proposer des solutions dès la phase Understanding** | Vous risquez de résoudre le mauvais problème | Interdisez-vous de parler de "caméras" ou de "système" pendant les 12 premiers jours |
| **N'interviewer que des étudiants** | Vision partielle du problème | Respecter la diversité des profils dans le plan d'interviews |
| **Poser des questions fermées ou orientées** | "Tu es pour la vidéosurveillance ?" → biais de confirmation | Utiliser les guides préparés, poser des questions ouvertes |
| **Ne pas enregistrer/documenter** | Perte de données, insights oubliés | Toujours enregistrer + prendre des notes, transcrire le soir même |
| **Questionnaire trop long** | Taux d'abandon élevé | Maximum 15–17 questions, durée < 7 minutes |
| **Ignorer les aspects éthiques** | Rejet du projet par les parties prenantes | Intégrer systématiquement les questions sur la vie privée et le consentement |
| **Rédiger le Problem Statement seul dans son coin** | Risque de biais individuel | Toujours co-construire et valider avec l'autre étudiant + l'encadreur |
| **Négliger l'infrastructure technique** | Proposer un système irréalisable | Documenter précisément les capacités réseau/matériel dès J1 |

---

## 4. BONUS

### 4.1 Recommandations spécifiques au contexte UFR SATIC

- **Réseau** : Ne pas présupposer une connectivité stable. Prévoir dès maintenant que le système devra fonctionner avec stockage **local** (carte SD, NVR) et synchronisation **différée**
- **Électricité** : Prévoir la question des coupures de courant dans les interviews (onduleurs, autonomie des équipements)
- **Effectifs** : L'UFR SATIC a des promotions nombreuses. Documentez les effectifs exacts par filière et par niveau — c'est un argument clé pour justifier la télésurveillance
- **Culture** : Au Sénégal, la notion de "surveillance" peut être perçue comme un manque de confiance. Insistez dans vos interviews sur la dimension **équité** et **protection** plutôt que **contrôle**
- **Langue** : Si certains entretiens se font en wolof, prévoyez la traduction dans les transcriptions
- **Temporalité** : Planifiez vos observations terrain pendant une vraie session d'examen — contactez la scolarité pour connaître le calendrier

### 4.2 Risques potentiels

| Risque | Probabilité | Impact | Mitigation |
|--------|------------|--------|-----------|
| **Refus d'entretien par l'administration** | Moyen | Élevé | Obtenir un soutien écrit de l'encadreur ; présenter le projet comme bénéfique pour l'UFR |
| **Faible taux de réponse au questionnaire** | Moyen | Moyen | Distribuer en présentiel dans les amphis, offrir un résumé des résultats aux participants |
| **Pas d'examen observable pendant la période** | Élevé | Moyen | Organiser une simulation avec l'accord d'un enseignant ; ou s'appuyer sur les descriptions des interviews |
| **Résistance étudiante au concept de vidéosurveillance** | Élevé | Moyen | Ne pas imposer — documenter les résistances comme un insight majeur, proposer des alternatives |
| **Infrastructure réseau inutilisable** | Moyen | Élevé | Prévoir une architecture offline-first dès la conception ; valider avec le service info |
| **Manque de temps (sessions d'examen proches)** | Moyen | Élevé | Prioriser les interviews les plus critiques (admin, service info) en premier |

### 4.3 Conseils pour valider rapidement les hypothèses

1. **Test du couloir** : Après 5 interviews, résumez vos 3 principaux insights en une phrase chacun. Allez les présenter informellement à 3 personnes (un étudiant, un enseignant, un membre de l'admin). Si tous acquiescent → vous êtes sur la bonne piste. Si l'un contredit → creusez.

2. **La règle du "5 pourquoi"** : Pour chaque problème identifié, demandez "pourquoi ?" 5 fois successivement pour atteindre la cause racine. Exemple :
   - Pourquoi y a-t-il de la fraude ? → Parce que les étudiants ne sont pas bien surveillés
   - Pourquoi ne sont-ils pas bien surveillés ? → Parce qu'il n'y a pas assez de surveillants
   - Pourquoi pas assez de surveillants ? → Parce que le budget est limité
   - Pourquoi le budget est limité ? → Parce que la surveillance n'est pas une priorité budgétaire
   - Pourquoi ce n'est pas une priorité ? → Parce qu'il n'y a pas de données chiffrées sur l'ampleur du problème
   - → **Insight** : le vrai problème est l'absence de données pour justifier un investissement

3. **Prototype rapide de questionnaire** : Avant de diffuser le Google Forms à 100+ personnes, testez-le auprès de 3–5 étudiants. Chronométrez, notez les questions incomprises, ajustez.

4. **Matrice 2×2 express** : Dès J10, faites un premier tri rapide de vos insights sur un tableau "Nouveau / Connu" × "Important / Secondaire". Concentrez votre énergie sur le quadrant **Nouveau + Important**.

5. **Validation encadreur régulière** : Ne attendez pas J18 pour montrer votre travail. Envoyez un résumé de 10 lignes à votre encadreur à J7 (fin interviews) et J14 (fin synthèse) pour recadrer si nécessaire.

---

## Récapitulatif des livrables

| # | Livrable | Format | Phase |
|---|---------|--------|-------|
| 1 | Fiche de synthèse documentaire | Google Docs, 2–3 pages | Understanding |
| 2 | Tableau comparatif solutions existantes | Google Sheets | Understanding |
| 3 | Carte des parties prenantes | Schéma (draw.io / papier) | Understanding |
| 4 | 4 guides d'entretien + formulaire consentement | Google Docs, imprimés | Understanding |
| 5 | Transcriptions d'interviews (15–20) | Google Docs | Understanding |
| 6 | Questionnaire Google Forms + données | Google Forms + Sheets | Understanding |
| 7 | 2 rapports d'observation terrain | Google Docs | Understanding |
| 8 | 2–3 personas | Google Docs ou Canva | Understanding |
| 9 | Cartes d'empathie (2–3) | Schéma | Understanding |
| 10 | Synthèse des insights | Google Docs, 3–5 pages | Understanding |
| 11 | Diagramme d'affinité | Photo mur post-its ou Miro | Definition |
| 12 | Liste des problèmes clés (5–8) | Google Docs | Definition |
| 13 | Questions HMW priorisées (5–8) | Google Docs | Definition |
| 14 | Matrice de priorisation | Google Sheets ou schéma | Definition |
| 15 | Problem Statement final | Google Docs, 1 page | Definition |
| 16 | Axes d'innovation (3–4) | Google Docs | Definition |
