# AB BE CRM — Solution Intégrée de Gestion Commerciale Mobilier

## 1. Contexte Académique et Objectifs
Ce projet a été réalisé à l'**ENCG Settat** dans le cadre du module **Outils CRM** (Master Management International et Développement Commercial, Année Universitaire 2025-2026). 

L'exercice pratique vise à :
- Concevoir et configurer les processus de gestion commerciale au sein de l'environnement ERP **Odoo** (référencé sous l'image native `AB BE Meubles.png.png`).
- Expérimenter une méthodologie de **prototypage rapide par Intelligence Artificielle** (Studio AI & Google AI Builder) en soumettant la cartographie fonctionnelle d'Odoo afin de générer une application métier web dédiée, autonome et optimisée.

---

## 2. Structure Fonctionnelle du CRM
Le système intègre l'ensemble du périmètre opérationnel de la relation client de la société **AB BE** :

- **Ventes (Pipeline Kanban) :** Réplication exacte du flux commercial configuré sur Odoo (Colonnes *Nouveau, Qualifié, Proposition, Gagné*) avec les opportunités réelles d'affaires (ex: Devis tapis à 40 000 $, chaises à 22 500 $).
- **Suivi Livraisons :** Suivi des bons de livraison logistiques (`#BL-2026-001`) avec gestion d'états d'avancement (En préparation, Livré) et géolocalisation des comptes.
- **Stock Mobilier :** Module d'inventaire corrélant la disponibilité des produits avec les opportunités commerciales actives.
- **Contacts Clients :** Base de données relationnelle centralisant les comptes clés (Acme Corp, Ready Mat) et les interlocuteurs décisionnaires (SFA).
- **Feedback Client :** Outil d'évaluation de la satisfaction client (Indicateur CSAT) conforme aux dimensions du CRM Collaboratif enseignées en cours.

---

## 3. Architecture Technique
- **Structure applicative :** Architecture *Single Page Application* (SPA) optimisée en HTML5 et JavaScript natif.
- **Identité Visuelle & Design :** Intégration stricte de la charte graphique institutionnelle via Tailwind CSS (Bleu corporate `#072F4F` et Or `#C5A021` extraits du logo officiel `Capture d'écran 2026-05-23 134637.png`).
- **Composants graphiques :** Lucide Icons.

---

## 4. Déploiement Local
1. Clonez ce dépôt GitHub.
2. Assurez-vous d'avoir le fichier `index.html` à la racine.
3. Exécutez le fichier directement dans votre navigateur web.
