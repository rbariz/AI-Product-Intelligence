# AI Product Intelligence

# 03 - Moteur de Découverte Produit (Product Discovery Engine)

**Version : 1.0**  
**Statut : Draft**  
**Dernière mise à jour : 13 juillet 2026**

---

# Question fondamentale

**Comment découvrir progressivement un produit sans demander à l'utilisateur de décrire l'ensemble de son idée dès le départ ?**

---

# Pourquoi cette question est importante

La majorité des outils d'intelligence artificielle commencent par une question unique :

> "Décrivez votre projet."

Cette approche suppose que l'utilisateur connaît parfaitement son produit.

Dans la réalité, c'est rarement le cas.

Les idées sont souvent :

- incomplètes ;
- imprécises ;
- implicites ;
- évolutives.

Le rôle de la plateforme n'est donc pas uniquement de recueillir des réponses.

Son rôle est de découvrir progressivement les connaissances manquantes.

---

# Notre conviction

Un bon architecte ne commence jamais par dessiner une architecture.

Il commence par poser les bonnes questions.

AI Product Intelligence doit adopter la même démarche.

Le système ne collecte pas des informations.

Il mène une enquête.

---

# Le principe fondamental

Le moteur de découverte poursuit un objectif unique :

**Transformer une idée en Modèle de Connaissance Produit.**

Chaque interaction doit enrichir ce modèle.

Une question n'est jamais posée au hasard.

Elle répond toujours à un manque identifié dans le modèle.

---

# Le cycle de découverte

Chaque interaction suit le même cycle.

Observation

↓

Analyse

↓

Identification des connaissances manquantes

↓

Choix de la meilleure question

↓

Réponse utilisateur

↓

Extraction des concepts

↓

Validation

↓

Enrichissement du Product Knowledge Model

↓

Nouvelle analyse

Ce cycle est répété jusqu'à obtenir une compréhension suffisante.

---

# Les missions du moteur

Le moteur doit être capable de :

- découvrir de nouveaux concepts ;
- compléter un concept existant ;
- détecter les informations manquantes ;
- identifier les ambiguïtés ;
- révéler les contradictions ;
- estimer le niveau de maturité du produit ;
- déterminer la prochaine meilleure question.

---

# Les catégories de questions

Toutes les questions n'ont pas le même objectif.

Le moteur distingue plusieurs catégories.

## Découverte

Exemple :

Qui utilisera le produit ?

---

## Clarification

Exemple :

Quand vous parlez de "client", s'agit-il d'une entreprise ou d'un particulier ?

---

## Validation

Exemple :

Cette règle s'applique-t-elle dans tous les cas ?

---

## Exploration

Exemple :

Existe-t-il des cas particuliers ?

---

## Contradiction

Exemple :

Vous indiquez qu'un paiement est obligatoire, mais vous mentionnez également un accès gratuit.

Pouvez-vous préciser ?

---

## Projection

Exemple :

Comment ce processus évoluerait-il si votre activité doublait ?

---

# Les critères de sélection d'une question

Avant de poser une question, le moteur évalue :

- quelles informations sont absentes ;
- quelles hypothèses restent fragiles ;
- quels risques sont élevés ;
- quels concepts possèdent un faible niveau de confiance ;
- quelles réponses auront le plus fort impact sur la compréhension globale.

La meilleure question est celle qui apporte le plus de connaissance.

---

# Quand arrêter ?

Le moteur ne cherche pas à tout découvrir.

Il s'arrête lorsque le modèle est jugé suffisamment mature pour permettre une décision fiable.

Par exemple :

- comprendre le métier ;
- proposer une architecture ;
- lancer une simulation ;
- produire une analyse.

La profondeur de découverte dépend donc de l'objectif.

---

# Ce que le moteur ne fait pas

Le moteur ne suit jamais un questionnaire fixe.

Deux utilisateurs décrivant des produits différents suivront des parcours différents.

Chaque conversation est pilotée par le Product Knowledge Model.

Le modèle décide des prochaines questions.

Pas un scénario prédéfini.

---

# Conséquence

Le dialogue n'est plus linéaire.

Il devient adaptatif.

Deux produits similaires pourront suivre des chemins proches.

Deux produits très différents produiront des explorations totalement différentes.

Le moteur s'adapte en permanence à l'état du Product Knowledge Model.

---

# Décisions prises

- Les questions sont guidées par le modèle.
- Chaque question poursuit un objectif précis.
- Le dialogue est adaptatif.
- Le moteur cherche à réduire l'incertitude.
- Le moteur privilégie les informations ayant le plus fort impact.
- La découverte s'arrête lorsque l'objectif est atteint.

---

# Prochaine étape

Découvrir un produit ne suffit pas.

Le système doit ensuite être capable de raisonner sur les connaissances collectées.

Cette capacité sera définie dans le document suivant :

**04 - Moteur de Raisonnement**