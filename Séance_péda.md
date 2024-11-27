**Titre de la séance :** Conception et programmation d'un robot aspirateur évitant les obstacles à l'aide d'un capteur choisi.

---

### **Objectifs de la séance :**

- **Objectifs pédagogiques :**
  - Comprendre le fonctionnement d'un capteur spécifique et son intégration dans un système embarqué.
  - Savoir programmer une carte Arduino pour contrôler un robot en fonction des données du capteur.
  - Développer des compétences en résolution de problèmes et en travail collaboratif.

- **Compétences visées :**
  - **CO3.1** : Identifier et caractériser les fonctions et les constituants d’un produit ainsi que ses entrées/sorties.
  - **CO3.3** : Identifier et caractériser le fonctionnement temporel d’un produit ou d’un processus.
  - **CO5.3** : Mettre en évidence les constituants d’un produit à partir des diagrammes pertinents.
  - **CO5.5** : Proposer des solutions à un problème technique identifié en participant à des démarches de créativité.
  - **CO5.8** : Proposer/choisir l’architecture d’une solution logicielle et matérielle au regard de la définition d’un produit.
  - **CO7.4** : Réaliser et valider un prototype ou une maquette obtenus en réponse à tout ou partie du cahier des charges initial.
  - **CO7.5** : Mettre en œuvre un scénario de validation, interpréter les résultats et qualifier le produit.

---

### **Avant la séance :**

- **Pour les élèves :**
  - **Recherche personnelle :** Chaque élève doit réfléchir au type de capteur qu'il utiliserait pour permettre à un robot aspirateur d'éviter les obstacles (parmi une sélection proposée : capteur à ultrasons, infrarouge, lidar, etc.).
  - **Justification du choix :** Préparer une courte explication du choix du capteur, en mentionnant ses avantages et inconvénients.

- **Pour le professeur :**
  - **Préparation du matériel :**
    - Préparer les kits Arduino par groupe, incluant le capteur choisi par les élèves.
    - Fournir un code de base pour la prise en main du capteur (lecture des données du capteur).
  - **Organisation des groupes :**
    - Constituer des groupes en fonction des capteurs choisis pour favoriser la diversité des solutions.

---

### **Déroulement de la séance (3 heures) :**

#### **1. Introduction (15 minutes)**

- **Présentation des objectifs :**
  - Expliquer le contexte du TP : améliorer un robot aspirateur pour qu'il évite les obstacles.
  - Rappeler les compétences visées et l'importance de chaque étape du travail.
- **Discussion initiale :**
  - Chaque groupe présente brièvement le capteur qu'il a choisi et les raisons de ce choix.

#### **2. Prise en main du capteur (45 minutes)**

- **Installation du matériel :**
  - Distribution des kits Arduino et des capteurs aux groupes.
- **Exécution du code de base :**
  - Les élèves chargent le code fourni et observent les données du capteur.
- **Analyse :**
  - Comprendre comment le capteur fonctionne et comment les données peuvent être utilisées.

#### **3. Développement du programme (95 minutes)**

- **Étape 1 : Conception de l'algorithme (30 minutes)**
  - **Analyse du problème :**
    - Identifier les situations où le robot doit changer de direction.
  - **Création de l'algorithme :**
    - Élaborer un schéma logique ou un organigramme du fonctionnement souhaité.
- **Étape 2 : Programmation (50 minutes)**
  - **Écriture du code :**
    - Programmer les réactions du robot en fonction des données du capteur (avancer, reculer, tourner).
  - **Intégration des commandes moteurs :**
    - Associer les sorties du programme aux actions des moteurs du robot.
- **Étape 3 : Tests et ajustements (15 minutes)**
  - **Mise en pratique :**
    - Tester le programme sur le robot.
  - **Débogage :**
    - Identifier les problèmes et ajuster le code en conséquence.

#### **4. Conclusion et compte rendu (15 minutes)**

- **Rédaction du rapport :**
  - Chaque groupe rédige un court compte rendu incluant :
    - Le fonctionnement du capteur utilisé.
    - Les étapes de la programmation et les défis rencontrés.
    - Une auto-évaluation de leur solution et des améliorations possibles.
- **Discussion finale :**
  - Partage des expériences entre les groupes.
  - Mise en commun des réussites et des difficultés.

---

### **Matériel nécessaire :**

- **Pour chaque groupe :**
  - Une carte Arduino.
  - Le capteur choisi (ultrasons, infrarouge, etc.).
  - Un module de contrôle de moteurs (si nécessaire).
  - Un châssis de robot avec roues et moteurs.
  - Ordinateur avec l'IDE Arduino installé.

---

### **Organisation des idées :**

- **Séquençage clair :**
  - Diviser la séance en étapes logiques pour guider les élèves.
- **Responsabilisation des élèves :**
  - Encourager l'autonomie en les laissant concevoir leur algorithme.
- **Collaboration :**
  - Favoriser le travail en groupe pour développer les compétences sociales.
- **Adaptabilité :**
  - Prévoir des solutions de secours pour les groupes en difficulté (par exemple, fournir des indices ou des exemples supplémentaires).

---

### **Évaluation :**

- **Critères d'évaluation :**
  - Compréhension du fonctionnement du capteur.
  - Qualité de l'algorithme conçu.
  - Fonctionnalité du programme final.
  - Qualité du compte rendu (clarté, pertinence des informations).
- **Observation durant la séance :**
  - Participation active.
  - Capacité à résoudre des problèmes.
  - Travail en équipe.

---

### **Conseils supplémentaires :**

- **Gestion du temps :**
  - Veiller à ce que chaque étape respecte le timing prévu.
- **Support aux élèves :**
  - Passer régulièrement auprès des groupes pour répondre aux questions.
- **Encouragement de la créativité :**
  - Laisser les élèves proposer des idées innovantes ou des améliorations.

---

### **Alignement avec les compétences visées :**

- **CO3.1 & CO3.3 :**
  - Identification des fonctions du robot et analyse du fonctionnement temporel lors de la conception de l'algorithme.
- **CO5.3 :**
  - Utilisation de diagrammes pour représenter les constituants du système.
- **CO5.5 :**
  - Choix du capteur et justification en début de séance.
- **CO5.8 :**
  - Conception de l'architecture matérielle et logicielle du robot.
- **CO7.4 & CO7.5 :**
  - Réalisation du prototype fonctionnel et validation à travers les tests.
