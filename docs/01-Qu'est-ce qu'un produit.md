# AI Product Intelligence

# 01 - Qu'est-ce qu'un produit ?

**Version : 1.0**  
**Statut : Draft**  
**Dernière mise à jour : 13 juillet 2026**

---

# Question fondamentale

**Qu'est-ce qu'un produit du point de vue d'une intelligence artificielle capable de le comprendre ?**

---

# Pourquoi cette question est importante

La plupart des outils de conception considèrent un produit comme une description textuelle.

Exemple :

> "Je souhaite créer une plateforme de réservation de parkings."

Pour un être humain, cette phrase évoque déjà de nombreuses connaissances implicites.

Pour une intelligence artificielle, elle reste insuffisante.

Elle ne décrit ni le métier, ni les acteurs, ni les règles, ni les contraintes.

Notre première décision est donc la suivante :

**Un produit n'est pas une description.**

---

# Notre définition

Nous définissons un produit comme un système organisé de connaissances représentant une réponse à un problème métier.

Ce système évolue au cours du temps.

Il possède :

- un objectif ;
- des acteurs ;
- des objets métier ;
- des capacités ;
- des règles ;
- des événements ;
- des contraintes ;
- des décisions ;
- des dépendances.

Un produit est donc un modèle vivant.

---

# Les trois niveaux d'un produit

Nous considérons qu'un produit peut être observé selon trois niveaux complémentaires.

## Niveau 1 : Le problème

Pourquoi ce produit existe-t-il ?

Le système doit comprendre :

- le problème à résoudre ;
- les personnes concernées ;
- les objectifs recherchés ;
- les limites des solutions actuelles.

Sans cette compréhension, aucune décision technique ne peut être pertinente.

---

## Niveau 2 : Le métier

Comment fonctionne le domaine métier ?

Le système découvre progressivement :

- les acteurs ;
- les objets métier ;
- les processus ;
- les règles ;
- les événements ;
- les décisions.

C'est à ce niveau que se construit le Modèle de Connaissance Produit.

---

## Niveau 3 : La solution

Comment répondre au besoin identifié ?

Ce n'est qu'à cette étape que peuvent apparaître :

- l'architecture ;
- les API ;
- les bases de données ;
- les traitements ;
- les composants techniques.

La solution est une conséquence des deux niveaux précédents.

---

# Notre représentation

Pour AI Product Intelligence, un produit n'est jamais stocké sous la forme d'un texte.

Il est représenté comme un ensemble de concepts reliés entre eux.

Exemple simplifié :

Produit

↓

Problème

↓

Acteurs

↓

Capacités

↓

Objets métier

↓

Règles

↓

Événements

↓

Contraintes

↓

Décisions

↓

Architecture

Cette représentation pourra évoluer au fil de la découverte.

---

# Une idée n'est pas un produit

Une idée constitue uniquement un point de départ.

Par exemple :

> "Créer un SaaS de gestion de cliniques."

Cette phrase ne permet pas de concevoir un système.

Le rôle de la plateforme est de transformer progressivement cette idée en un modèle suffisamment riche pour permettre des décisions fiables.

---

# Ce que découvre progressivement la plateforme

Au fil des échanges, le système cherche à identifier notamment :

- le problème métier ;
- les utilisateurs ;
- les objectifs ;
- les capacités métier ;
- les objets manipulés ;
- les règles métier ;
- les événements importants ;
- les contraintes fonctionnelles ;
- les contraintes non fonctionnelles ;
- les risques ;
- les dépendances externes ;
- les hypothèses encore non validées.

Chaque réponse enrichit le modèle.

---

# Conséquence majeure

Une architecture ne sera jamais générée directement à partir d'un prompt.

Elle sera déduite d'un Modèle de Connaissance Produit suffisamment complet.

Plus le modèle est riche, plus les recommandations seront pertinentes.

---

# Décision

À partir de ce document, AI Product Intelligence considérera toujours qu'un produit est un **modèle de connaissances évolutif**, et non une simple description textuelle.

Toutes les fonctionnalités futures devront renforcer cette vision.

---

# Prochaine étape

Cette définition appelle naturellement une nouvelle question :

**Comment représenter ce modèle de connaissances ?**

Cette question sera traitée dans le document suivant :

**02 - Modèle de Connaissance Produit**