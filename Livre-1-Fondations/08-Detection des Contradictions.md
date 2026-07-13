# AI Product Intelligence

# 08 - Détection des Contradictions

**Version : 1.0**  
**Statut : Draft**  
**Dernière mise à jour : 13 juillet 2026**

---

# Question fondamentale

**Comment la plateforme détecte-t-elle automatiquement les incohérences dans la connaissance d'un produit ?**

---

# Pourquoi cette question est importante

Les produits réels sont rarement parfaitement définis.

Ils évoluent.

Ils sont conçus par plusieurs personnes.

Ils comportent souvent des hypothèses implicites, des ambiguïtés ou des décisions incompatibles.

Une plateforme capable de raisonner doit être capable de détecter ces contradictions avant qu'elles ne deviennent des erreurs de conception.

---

# Notre conviction

Une contradiction n'est pas une erreur.

C'est une opportunité d'améliorer la compréhension.

Le rôle du moteur n'est pas de corriger automatiquement.

Il est de rendre visibles les incohérences afin qu'elles puissent être clarifiées.

---

# Les différents types de contradictions

Le moteur distingue plusieurs catégories.

---

## Contradictions métier

Deux règles métier incompatibles.

Exemple :

Le paiement est obligatoire.

↓

Le paiement est facultatif.

---

## Contradictions de processus

Deux processus incompatibles.

Exemple :

Validation avant paiement.

↓

Paiement avant validation.

---

## Contradictions d'acteurs

Deux rôles possèdent des responsabilités incompatibles.

---

## Contradictions de contraintes

Une exigence technique ne respecte pas une contrainte réglementaire.

Exemple :

Stockage mondial.

↓

Données soumises au RGPD.

---

## Contradictions d'architecture

Une architecture proposée ne respecte pas les besoins métier.

Exemple :

Haute disponibilité exigée.

↓

Serveur unique recommandé.

---

## Contradictions temporelles

Deux événements supposent des ordres différents.

---

## Contradictions de dépendances

Deux composants imposent des choix incompatibles.

---

# Détection

Le moteur recherche en permanence :

- les conflits de règles ;
- les incompatibilités ;
- les dépendances circulaires ;
- les doublons ;
- les concepts incompatibles ;
- les décisions contradictoires.

---

# Analyse

Chaque contradiction possède :

- une gravité ;
- un niveau de confiance ;
- une justification ;
- les concepts concernés ;
- les impacts potentiels.

---

# Résolution

Le moteur ne décide jamais seul.

Il peut :

- demander une clarification ;
- proposer plusieurs interprétations ;
- signaler les conséquences de chaque choix.

La décision finale appartient toujours à l'utilisateur.

---

# Priorisation

Toutes les contradictions n'ont pas le même impact.

Le moteur distingue :

- critiques ;
- importantes ;
- mineures ;
- informatives.

Cette classification permet de guider efficacement l'utilisateur.

---

# Traçabilité

Chaque contradiction reste enregistrée dans le Product Knowledge Model.

Même lorsqu'elle est résolue.

Ainsi, la plateforme conserve l'historique des décisions.

---

# Conséquence

Une architecture ne peut être considérée comme fiable tant que les contradictions critiques n'ont pas été résolues.

La cohérence du produit devient un prérequis à toute recommandation importante.

---

# Décisions prises

- Les contradictions sont détectées automatiquement.
- Elles sont classifiées selon leur gravité.
- Elles enrichissent le Product Knowledge Model.
- Le moteur ne corrige jamais sans validation.
- Les décisions restent entièrement traçables.

---

# Prochaine étape

Détecter une contradiction ne suffit pas.

La plateforme doit également être capable de raisonner lorsqu'une information est absente.

Cette capacité sera définie dans :

**09 - Moteur d'Hypothèses**