# AI Product Intelligence

# 05 - Ontologie Produit

**Version : 1.0**  
**Statut : Draft**  
**Dernière mise à jour : 13 juillet 2026**

---

# Question fondamentale

Quels sont les concepts fondamentaux qui composent tout produit numérique ?

---

# Pourquoi cette question est importante

Le Product Knowledge Model définit la structure globale des connaissances.

L'ontologie définit le vocabulaire utilisé pour représenter ces connaissances.

Elle constitue le langage commun de toute la plateforme.

Chaque moteur devra utiliser les mêmes concepts.

---

# Définition

Une ontologie est un ensemble de concepts clairement définis ainsi que les relations qui peuvent exister entre eux.

Elle garantit que tous les composants de la plateforme parlent le même langage.

---

# Les concepts fondamentaux

## Problème

Le besoin auquel le produit répond.

---

## Objectif

Le résultat recherché.

---

## Acteur

Toute personne, organisation ou système qui interagit avec le produit.

---

## Capacité

Ce que le produit permet de réaliser.

Une capacité décrit une intention métier.

Exemple :

Réserver

Payer

Notifier

Analyser

---

## Objet métier

Information manipulée par le produit.

Exemple :

Commande

Facture

Réservation

Contrat

Patient

---

## Processus

Enchaînement organisé de capacités.

---

## Règle métier

Condition qui gouverne le fonctionnement du produit.

---

## Événement

Fait significatif survenu dans le système.

---

## Décision

Choix réalisé par un acteur ou par la plateforme.

---

## Contrainte

Limitation imposée au produit.

---

## Risque

Situation pouvant compromettre les objectifs du produit.

---

## Système externe

Application ou service avec lequel le produit interagit.

---

# Les relations

Les concepts n'ont de valeur que par leurs relations.

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

génère

↓

Evènement

Evènement

↓

déclenche

↓

Processus

Décision

↓

réduit

↓

Risque

---

# Décisions prises

Tous les composants utiliseront cette ontologie.

Aucun nouveau concept ne pourra être introduit sans être défini ici.

Cette ontologie constitue le vocabulaire officiel de la plateforme.

---

# Prochaine étape

Une fois le langage défini, il devient possible de représenter les connaissances sous forme de relations.

Cette représentation sera décrite dans :

**06 - Graphe de Connaissances Produit**