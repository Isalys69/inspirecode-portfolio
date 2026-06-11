# Inspire Code — Isalys Creuzeau-Gulinck

Développeuse web indépendante. Je construis des outils sur mesure pour les TPE, les vignerons et les porteurs de projets qui veulent une présence numérique qui leur ressemble vraiment.

→ [inspirecode.fr](https://inspirecode.fr) · [LinkedIn](https://www.linkedin.com/in/isalys-creuzeau-gulinck-b885992a2/)

---

## Qui je suis

Autodidacte. Autoentrepreneuse. Je suis passée du "je comprends comment ça marche" au "je l'ai construit moi-même". C'est exactement cette trajectoire qui me permet d'accompagner mes clients sans les noyer dans le jargon.

Mon terrain de jeu : les petites structures avec de grandes ambitions. Vignerons en conversion, commerces locaux, artisans du goût. Des gens qui ont une histoire à raconter et qui n'ont pas besoin d'un prestataire qui survend, ils ont besoin d'un outil qui fonctionne, qui dure, et qu'ils comprennent.

Ce qui m'intéresse autant que le code : **la démarche**. Pourquoi ce choix technique ? Qu'est-ce qu'on sacrifie ? Comment ça évolue dans 18 mois quand le client a grandi ?

---

## Projets

### 🌐 Inspire Code — Site vitrine agence
**[inspirecode.fr](https://inspirecode.fr)**

Site de l'agence. Conçu pour être lisible sur mobile avant tout — parce que mes clients vignerons consultent depuis leur tracteur ou leur cave, pas depuis un MacBook.

- Stack : HTML/CSS/JS vanilla, hébergement statique
- Choix délibéré : zéro dépendance frontend. Pas de build step, pas de framework à maintenir, charge en < 1s sur 4G.
- Itération en cours : refonte v2 avec section témoignages et devis en ligne

---

### 🍷 Les Silences du Vin — E-commerce vins confidentiels
**[lessilencesduvin.fr](https://www.lessilencesduvin.fr)** *(en cours — ouverture commerciale à venir)*

Boutique en ligne pour un vigneron indépendant. Vins produits en très petite quantité, clientèle de connaisseurs. Le cahier des charges : une expérience d'achat qui soit à la hauteur du produit — sobre, sensorielle, sans fioriture marketing.

- Stack : Flask (Python), SQLAlchemy, Stripe, Vue.js
- Modèle de stock en temps réel : quand la dernière bouteille est vendue, la fiche disparaît
- Enjeu technique : gestion des millésimes comme entités distinctes d'un même produit
- Back-office sur mesure : carnet de dégustation intégré, structuré autour de la méthode de dégustation réellement pratiquée (géo-sensorielle et poly-sensorielle)
- Démarche : 3 rounds de wireframes papier avec le vigneron avant la première ligne de code

---

### 📱 Tirelire Maison — App iOS épargne familiale
**[Disponible sur l'App Store](https://apps.apple.com/fr/app/tirelire-maison/id6761920315)**

Application d'épargne pour les familles qui veulent enseigner la valeur de l'argent à leurs enfants. Interface volontairement simple : une tirelire par objectif, un graphique de progression, c'est tout.

- Stack : Swift / SwiftUI
- Contrainte forte : l'app doit être utilisable par un enfant de 7 ans sans explication parentale
- Ce que j'ai appris : la rigueur de l'App Store review process est une bonne école de qualité

---

### 🎮 Pièce par Pièce — Jeu de construction tablette
*(en développement)*

Jeu de construction procédurale pour tablette. L'idée : des pièces avec des comportements physiques réalistes, une progression par niveaux, zéro violence, zéro monétisation agressive.

- Engine : Godot 4 (GDScript)
- Pourquoi Godot : open source, export multiplateforme propre, communauté saine
- Où j'en suis : prototype jouable avec 12 pièces, physique 2D validée, UX en cours de test

---

### 📊 Gestion Boursière — App web de pilotage de portefeuille
*(en production, usage personnel quotidien)*

Application web développée pour piloter un portefeuille boursier (PEA) au quotidien, en remplacement d'un tableur devenu limitant. Deux espaces distincts : pilotage du portefeuille existant et préparation des décisions d'entrée (pré-trade).

- Stack : Flask (Python), SQLAlchemy
- Recalcul des objectifs d'investissement à la demande, plutôt que des projections figées
- Répartition automatique de l'investissement mensuel selon la somme disponible
- Grille d'analyse d'entreprise pour objectiver les choix d'entrée
- Cas d'école du passage tableur → application métier : périmètre cadré, calculs fiabilisés

---

### 🏛️ PhilaMaster — Gestion de collection philatélique
*(en service, accès privé)*

Application de numérisation et de valorisation d'une collection de timbres transmise en héritage. Construite autour du geste le plus naturel : photographier un timbre, le laisser être reconnu par l'IA, puis rejoindre le catalogue.

- Stack : frontend mobile-first (Expo), backend FastAPI (Python)
- Reconnaissance par IA du timbre photographié : identification, origine, références catalogue
- Quatre espaces : accueil, catalogue, ajout, statistiques
- Ce qui m'a plu : un outil intime, sans vocation publique, mais qui rend un service réel au quotidien

---

### 🔍 Sourcing de domaines viticoles — Outil interne
*(repo privé — Les Silences du Vin)*

Outil de croisement de données publiques pour identifier des domaines viticoles confidentiels, en amont d'une prospection menée sur le terrain.

- Données : Registre Parcellaire Graphique (open data agricole) croisé avec les références INSEE
- Stack : Python, pandas
- Traitement ponctuel, adapté au rythme réel de l'activité : une campagne de sourcing par an
- Résultat volontairement restreint : quelques domaines ciblés plutôt qu'une liste exhaustive
- Philosophie : l'automatisation ne remplace pas le travail humain, elle le concentre là où il a le plus de valeur

> Plus de détails (démarche, captures d'écran, contexte) sur [inspirecode.fr/realisations](https://www.inspirecode.fr/realisations) et [inspirecode.fr/realisations_automatisations](https://www.inspirecode.fr/realisations_automatisations).

---

## Stack technique

```
Backend       Python 3.13 · Flask · FastAPI · SQLAlchemy · REST
Frontend      HTML/CSS/JS · Vue.js · mobile-first systématique
iOS           Swift · SwiftUI
Game dev      Godot 4 · GDScript
Scraping      Selenium · pandas · geckodriver
Outils        Git · GitHub · Figma (wireframes) · Notion
Déploiement   VPS Linux · Nginx · domaines OVH
```

---

## Démarche

Je travaille en itérations courtes avec des points de validation réguliers. Cette méthode Agile évite de construire six semaines dans le mauvais sens et le client mesure l'évolution.

Pour chaque projet client, il y a une phase de cadrage qui précède le code : comprendre le métier, identifier les vrais irritants, distinguer ce qui doit être dans l'outil de ce qui doit rester dans la tête du client. C'est souvent là que le projet prend sa forme définitive.

Je documente ce que je construis. Pas pour faire bien mais pour que ça reste maintenable dans deux ans, y compris par quelqu'un d'autre que moi.

---

## Contact

**Isalys Creuzeau — Inspire Code**
[contact@inspirecode.fr](mailto:contact@inspirecode.fr)
[inspirecode.fr/contact](https://inspirecode.fr/contact)
[inspirecode.fr](https://inspirecode.fr)

*Mentions légales complètes disponibles sur [inspirecode.fr/mentions-legales](https://inspirecode.fr/mentions-legales)*
