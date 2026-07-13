# AI Product Intelligence

# 09 - Moteur d'Hypothèses (Hypothesis Engine)

**Version : 1.0**  
**Statut : Draft**  
**Dernière mise à jour : 13 juillet 2026**

---

# Question fondamentale

**Comment la plateforme peut-elle raisonner lorsque certaines informations sont absentes, tout en restant transparente sur ses suppositions ?**

---

# Pourquoi cette question est importante

Dans les premières phases de conception, un produit est toujours incomplet.

Certaines informations sont connues.

D'autres sont implicites.

D'autres encore sont totalement absentes.

Attendre que toutes les réponses soient disponibles empêcherait toute progression.

La plateforme doit donc être capable de formuler des hypothèses.

---

# Notre conviction

Une hypothèse n'est pas une vérité.

C'est une proposition de connaissance, formulée à partir des informations disponibles.

Elle permet au raisonnement de progresser, mais elle doit toujours pouvoir être confirmée, modifiée ou rejetée.

---

# Définition

Une hypothèse est une connaissance provisoire créée par le moteur de raisonnement afin de compléter temporairement le Product Knowledge Model.

Elle est toujours :

- explicite ;
- justifiée ;
- traçable ;
- réversible.

---

# Les sources d'hypothèses

Le moteur peut produire une hypothèse à partir de plusieurs sources.

## Similarité

Le produit ressemble à un domaine déjà connu.

Exemple :

Gestion de cabinets médicaux

↓

Hypothèse :

Le produit manipule probablement des rendez-vous.

---

## Règles métier

Une règle implique naturellement une autre.

Exemple :

Paiement obligatoire

↓

Hypothèse :

Le système devra probablement gérer des moyens de paiement.

---

## Dépendances

Une capacité implique d'autres capacités.

Exemple :

Réserver

↓

Hypothèse :

Une confirmation sera probablement nécessaire.

---

## Contraintes

Une contrainte entraîne des conséquences.

Exemple :

RGPD

↓

Hypothèse :

Des mécanismes de consentement seront probablement requis.

---

## Expérience accumulée

Le moteur peut reconnaître des structures fréquemment rencontrées dans des produits similaires, tout en indiquant qu'il s'agit d'une généralisation et non d'une certitude.

---

# Cycle de vie d'une hypothèse

Une hypothèse suit plusieurs états.

Créée

↓

Présentée

↓

Validée

ou

Modifiée

ou

Rejetée

Aucune hypothèse ne devient une connaissance confirmée sans validation.

---

# Niveau de confiance

Chaque hypothèse possède un score de confiance.

Ce score dépend notamment :

- des informations disponibles ;
- de la cohérence avec le modèle ;
- du nombre d'indices convergents ;
- de l'expérience acquise sur des produits comparables.

Le niveau de confiance guide la priorité des validations.

---

# Présentation à l'utilisateur

La plateforme distingue toujours :

✔ Connaissances confirmées

⚠ Hypothèses

❓ Informations inconnues

L'utilisateur comprend ainsi immédiatement le statut de chaque information.

---

# Impact des hypothèses

Une hypothèse peut :

- orienter les prochaines questions ;
- influencer les recommandations ;
- enrichir temporairement le Product Knowledge Model.

En revanche, une décision critique ne doit jamais reposer uniquement sur une hypothèse.

---

# Révision permanente

Chaque nouvelle information peut :

- confirmer une hypothèse ;
- l'affiner ;
- la remplacer ;
- la supprimer.

Le moteur révise continuellement son propre raisonnement.

---

# Ce que le moteur ne fait pas

Le moteur ne transforme jamais une hypothèse en fait établi.

Il ne masque jamais les incertitudes.

Il privilégie toujours la transparence.

---

# Décisions prises

- Les hypothèses sont des connaissances provisoires.
- Elles sont toujours explicites.
- Elles possèdent un niveau de confiance.
- Elles sont entièrement traçables.
- Elles peuvent être validées, modifiées ou rejetées.
- Elles enrichissent temporairement le Product Knowledge Model.

---

# Prochaine étape

Une fois les hypothèses formulées, une nouvelle question apparaît naturellement.

**Comment mesurer les conséquences d'une décision sur l'ensemble du produit ?**

Cette capacité sera définie dans :

**10 - Analyse d'Impact**