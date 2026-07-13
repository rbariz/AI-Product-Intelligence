# AI Product Intelligence

# 06 - Graphe de Connaissances Produit

**Version : 1.0**  
**Statut : Draft**  
**Dernière mise à jour : 13 juillet 2026**

---

# Question fondamentale

**Comment représenter toutes les connaissances d'un produit afin qu'elles puissent être explorées, analysées et enrichies de manière continue ?**

---

# Pourquoi cette question est importante

Le Product Knowledge Model définit les connaissances.

L'ontologie définit les concepts.

Le moteur de découverte enrichit ces connaissances.

Le moteur de raisonnement les exploite.

Il manque cependant une représentation permettant de relier efficacement toutes ces informations.

Cette représentation est le Graphe de Connaissances Produit.

---

# Définition

Le Graphe de Connaissances Produit est la représentation vivante de toutes les connaissances connues par la plateforme.

Chaque concept devient un nœud.

Chaque relation devient un lien.

Le graphe constitue la mémoire active de la plateforme.

---

# Pourquoi un graphe ?

Les documents sont linéaires.

Les bases relationnelles stockent des données.

Le graphe représente des connaissances.

Il permet de répondre naturellement à des questions comme :

- Quel acteur utilise cette capacité ?
- Quels événements impactent ce processus ?
- Quels risques concernent cette fonctionnalité ?
- Quelles décisions reposent sur cette règle ?
- Quels concepts sont encore isolés ?

---

# Les éléments du graphe

Le graphe est composé de deux éléments fondamentaux.

## Les nœuds

Chaque nœud représente un concept.

Exemples :

- Produit
- Acteur
- Capacité
- Objet métier
- Processus
- Événement
- Décision
- Contrainte
- Risque

Chaque nœud possède :

- un identifiant ;
- un type ;
- une description ;
- un niveau de confiance ;
- un état ;
- une origine.

---

## Les relations

Les relations donnent leur sens aux concepts.

Exemples :

ACTEUR

↓

utilise

↓

CAPACITÉ

CAPACITÉ

↓

manipule

↓

OBJET MÉTIER

OBJET MÉTIER

↓

déclenche

↓

ÉVÉNEMENT

ÉVÉNEMENT

↓

impacte

↓

PROCESSUS

PROCESSUS

↓

respecte

↓

CONTRAINTE

DÉCISION

↓

réduit

↓

RISQUE

---

# Les propriétés des relations

Une relation possède également des informations.

Par exemple :

- son type ;
- son origine ;
- son niveau de confiance ;
- sa justification ;
- sa date de création.

Une relation est une connaissance à part entière.

---

# Un graphe vivant

Le graphe évolue en permanence.

À chaque nouvelle interaction, le système peut :

- créer un nouveau nœud ;
- enrichir un nœud existant ;
- créer une nouvelle relation ;
- renforcer une relation existante ;
- supprimer une ambiguïté ;
- augmenter un niveau de confiance.

Le graphe représente toujours l'état courant de la connaissance.

---

# Le graphe comme mémoire

Tous les moteurs travaillent sur le même graphe.

Le moteur de découverte ajoute des concepts.

Le moteur de raisonnement analyse les relations.

Le moteur de simulation évalue les impacts.

Le moteur d'architecture produit des recommandations.

Ils partagent tous la même mémoire.

---

# Les avantages

Cette représentation permet notamment :

- d'explorer les dépendances ;
- d'expliquer les recommandations ;
- d'identifier les zones incomplètes ;
- de détecter les contradictions ;
- de mesurer la maturité du produit ;
- d'analyser les impacts d'une évolution.

Le graphe devient le support du raisonnement.

---

# Ce que le graphe n'est pas

Le graphe n'est pas un diagramme.

Le graphe n'est pas une visualisation.

Le graphe est une structure de connaissances.

Une visualisation n'est qu'une manière de le représenter.

Cette distinction est fondamentale.

---

# Décisions prises

- Le Graphe de Connaissances est la mémoire active de la plateforme.
- Les concepts sont représentés sous forme de nœuds.
- Les relations sont des connaissances à part entière.
- Tous les moteurs travaillent sur le même graphe.
- La visualisation est indépendante du modèle de connaissances.

---

# Prochaine étape

Le graphe contient désormais toutes les connaissances du produit.

Une nouvelle question apparaît alors naturellement :

**Comment mesurer la qualité et la maturité de cette connaissance ?**

Cette question sera traitée dans le document suivant :

**07 - Analyse de Complétude et Maturité Produit**