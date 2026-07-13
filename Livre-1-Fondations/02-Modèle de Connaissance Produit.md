# AI Product Intelligence

# 02 - Modèle de Connaissance Produit (Product Knowledge Model)

**Version : 1.0**  
**Statut : Draft**  
**Dernière mise à jour : 13 juillet 2026**

---

# Question fondamentale

**Comment représenter un produit de manière structurée afin qu'il puisse être compris, analysé et faire l'objet d'un raisonnement ?**

---

# Pourquoi cette question est importante

Nous avons défini qu'un produit n'est pas une description textuelle.

Il est un ensemble de connaissances organisées.

La plateforme a donc besoin d'un modèle unique capable de représenter toutes les informations découvertes au cours des échanges.

Ce modèle devient la mémoire permanente de la plateforme.

Toutes les analyses, recommandations et générations futures s'appuieront sur lui.

Nous l'appelons :

**Product Knowledge Model (PKM).**

---

# Définition

Le Product Knowledge Model est la représentation structurée de tout ce que la plateforme connaît d'un produit.

Il ne représente pas uniquement l'état actuel du produit.

Il représente également :

- ce qui est connu ;
- ce qui est inconnu ;
- ce qui reste à découvrir ;
- les hypothèses ;
- les contradictions ;
- le niveau de confiance associé à chaque information.

Le PKM constitue la source de vérité de la plateforme.

---

# Les grandes dimensions du modèle

Nous considérons qu'un produit est composé de plusieurs dimensions complémentaires.

## 1. Le problème

Pourquoi le produit existe-t-il ?

Exemples :

- problème métier
- objectifs
- valeur apportée
- contexte

---

## 2. Les acteurs

Qui interagit avec le système ?

Exemples :

- utilisateur
- administrateur
- client
- partenaire
- système externe

---

## 3. Les capacités métier

Que permet réellement le produit ?

Exemples :

- réserver
- payer
- notifier
- analyser
- contrôler

Les capacités représentent les intentions métier.

---

## 4. Les objets métier

Quels sont les objets manipulés ?

Exemples :

- réservation
- facture
- véhicule
- ticket
- contrat

---

## 5. Les règles métier

Quelles sont les règles qui gouvernent le système ?

Exemples :

- un paiement est obligatoire
- une réservation expire après 15 minutes
- un utilisateur ne peut réserver qu'une place

---

## 6. Les processus

Comment les capacités s'enchaînent-elles ?

Exemples :

Réserver

↓

Payer

↓

Valider

↓

Notifier

---

## 7. Les événements

Quels événements importants peuvent se produire ?

Exemples :

- réservation créée
- paiement confirmé
- ticket annulé
- contrat signé

---

## 8. Les contraintes

Quelles sont les limites du système ?

Exemples :

- réglementaires
- techniques
- métier
- organisationnelles

---

## 9. Les décisions

Quels choix ont été pris ?

Pourquoi ?

Chaque décision doit conserver sa justification.

---

## 10. Les risques

Quels risques ont été identifiés ?

Pourquoi ?

Quel est leur impact ?

---

# Les relations

Le PKM ne contient pas uniquement des concepts.

Il contient également leurs relations.

Exemples :

Acteur

↓

utilise

↓

Capacité

Capacité

↓

manipule

↓

Objet métier

Objet métier

↓

déclenche

↓

Événement

Événement

↓

impacte

↓

Processus

Décision

↓

résout

↓

Risque

Ces relations sont aussi importantes que les concepts eux-mêmes.

---

# Les propriétés de chaque concept

Chaque concept possède au minimum :

- un identifiant
- un type
- une description
- une origine
- un niveau de confiance
- un statut
- une date de découverte
- une justification

Ainsi, la plateforme sait toujours :

- pourquoi une information existe ;
- d'où elle provient ;
- dans quelle mesure elle est fiable.

---

# Un modèle vivant

Le Product Knowledge Model n'est jamais figé.

À chaque interaction, il peut :

- ajouter de nouveaux concepts ;
- enrichir un concept existant ;
- corriger une hypothèse ;
- supprimer une ambiguïté ;
- détecter une contradiction ;
- augmenter le niveau de confiance.

Le produit évolue.

Le modèle évolue avec lui.

---

# Pourquoi ce modèle est différent

Les outils traditionnels produisent des documents.

Le Product Knowledge Model produit de la connaissance.

Cette connaissance est :

- réutilisable ;
- interrogeable ;
- explicable ;
- évolutive.

Tous les artefacts futurs seront générés à partir du même modèle.

---

# Conséquence

Le Product Knowledge Model devient le cœur de la plateforme.

Les moteurs de découverte, de raisonnement, d'analyse et de génération ne créent pas leur propre représentation.

Ils enrichissent tous le même modèle.

---

# Décisions prises

- Le Product Knowledge Model est la source de vérité unique.
- Toutes les fonctionnalités enrichissent le même modèle.
- Les concepts sont reliés entre eux.
- Les relations ont autant d'importance que les concepts.
- Chaque information est traçable.
- Le modèle est vivant et évolutif.

---

# Prochaine étape

Une fois le modèle défini, une nouvelle question apparaît naturellement :

**Comment découvrir progressivement toutes ces connaissances sans demander à l'utilisateur de remplir un long formulaire ?**

Cette question sera traitée dans le document suivant :

**03 - Moteur de Découverte Produit**