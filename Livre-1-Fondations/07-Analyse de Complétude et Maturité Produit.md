# AI Product Intelligence

# 07 - Analyse de Complétude et Maturité Produit

**Version : 1.0**  
**Statut : Draft**  
**Dernière mise à jour : 13 juillet 2026**

---

# Question fondamentale

**Comment la plateforme détermine-t-elle si elle comprend suffisamment un produit pour produire des recommandations fiables ?**

---

# Pourquoi cette question est importante

Toutes les connaissances n'ont pas la même valeur.

Deux produits peuvent contenir le même nombre d'informations.

Pourtant :

- l'un peut être parfaitement compris ;
- l'autre peut présenter de nombreuses zones d'ombre.

La plateforme doit donc être capable d'évaluer la qualité de sa propre compréhension.

Cette capacité constitue un élément fondamental de son intelligence.

---

# Notre conviction

La plateforme ne doit jamais produire une recommandation importante tant que le niveau de compréhension est insuffisant.

Elle doit être capable de dire :

- ce qu'elle sait ;
- ce qu'elle ne sait pas ;
- ce qui reste à découvrir ;
- ce qui est encore incertain.

---

# Les quatre dimensions de la maturité

La maturité d'un produit ne dépend pas uniquement de la quantité d'informations.

Elle dépend de plusieurs dimensions complémentaires.

---

## 1. Complétude

Toutes les dimensions importantes du produit sont-elles couvertes ?

Exemples :

- problème métier
- acteurs
- capacités
- objets métier
- règles
- événements
- contraintes
- risques

Le moteur identifie les zones encore incomplètes.

---

## 2. Cohérence

Les connaissances sont-elles compatibles entre elles ?

Le moteur recherche :

- contradictions
- doublons
- conflits
- ambiguïtés

Une connaissance contradictoire diminue le niveau de maturité.

---

## 3. Confiance

Chaque information possède un niveau de confiance.

Une architecture fondée sur des hypothèses fragiles sera elle-même fragile.

Le moteur mesure donc la solidité des connaissances disponibles.

---

## 4. Couverture

Les connaissances couvrent-elles réellement le fonctionnement du produit ?

Exemple :

Le système connaît les acteurs.

Mais il ne connaît aucun processus.

La couverture reste insuffisante.

---

# Les indicateurs

Le moteur calcule différents indicateurs.

Par exemple :

- Score de complétude
- Score de cohérence
- Score de confiance
- Score de couverture
- Score global de maturité

Ces indicateurs évoluent après chaque interaction.

---

# Les zones d'ombre

Le moteur identifie en permanence :

- les concepts absents ;
- les relations manquantes ;
- les hypothèses non validées ;
- les règles incomplètes ;
- les processus partiellement connus.

Ces zones deviennent les priorités du moteur de découverte.

---

# Les seuils de décision

Chaque capacité de la plateforme exige un niveau minimal de maturité.

Exemple :

Découverte initiale

↓

20 %

Analyse métier

↓

50 %

Architecture

↓

75 %

Simulation

↓

85 %

Analyse d'impact

↓

90 %

Ces valeurs pourront évoluer.

Le principe, lui, restera identique.

---

# Les recommandations

Le moteur ne se contente pas d'afficher un score.

Il explique :

Pourquoi le score est faible.

Quelles connaissances sont manquantes.

Quelles questions permettront le plus d'améliorer la compréhension.

Ainsi, chaque score conduit naturellement à une action.

---

# Le principe fondamental

La plateforme ne cherche jamais à atteindre 100 %.

Elle cherche à atteindre un niveau suffisant pour l'objectif demandé.

Comprendre un produit n'est pas une fin.

C'est un moyen de prendre de meilleures décisions.

---

# Décisions prises

- La maturité est multidimensionnelle.
- Les scores sont explicables.
- Les zones d'ombre sont identifiées.
- Les recommandations dépendent du niveau de maturité.
- Le moteur sait reconnaître les limites de sa propre connaissance.

---

# Prochaine étape

Une fois la maturité évaluée, une nouvelle question apparaît naturellement.

**Comment détecter automatiquement les incohérences et les contradictions dans les connaissances du produit ?**

Cette question sera traitée dans :

**08 - Détection des Contradictions**