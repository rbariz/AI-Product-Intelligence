# AI Product Intelligence

# 10 - Moteur d'Analyse d'Impact (Impact Analysis Engine)

**Version : 1.0**  
**Statut : Draft**  
**Dernière mise à jour : 13 juillet 2026**

---

# Question fondamentale

**Comment la plateforme évalue-t-elle les conséquences d'une décision sur l'ensemble du produit ?**

---

# Pourquoi cette question est importante

Concevoir un produit consiste à prendre des décisions.

Chaque décision modifie le produit.

Certaines décisions ont peu de conséquences.

D'autres impactent profondément :

- le métier ;
- les processus ;
- l'architecture ;
- la sécurité ;
- les coûts ;
- les performances ;
- l'expérience utilisateur.

Le rôle de la plateforme est d'anticiper ces conséquences avant leur mise en œuvre.

---

# Notre conviction

Une bonne décision n'est pas uniquement une décision cohérente.

C'est une décision dont les conséquences sont connues.

La plateforme doit donc être capable d'explorer les impacts potentiels d'un changement.

---

# Définition

Le Moteur d'Analyse d'Impact évalue les effets directs et indirects d'une modification sur le Product Knowledge Model.

Il s'appuie sur le Graphe de Connaissances pour identifier les dépendances entre les concepts.

---

# Les types d'impact

Le moteur distingue plusieurs catégories.

## Impact métier

La modification change-t-elle les règles métier ?

Exemple :

Le paiement devient facultatif.

Conséquences :

- nouvelles règles ;
- nouveaux scénarios ;
- nouveaux contrôles.

---

## Impact fonctionnel

Quelles capacités sont concernées ?

Exemple :

Ajout d'un abonnement.

Capacités impactées :

- paiement ;
- facturation ;
- gestion des comptes.

---

## Impact technique

Quelles parties de l'architecture devront évoluer ?

Exemple :

Introduction du temps réel.

Conséquences possibles :

- WebSocket ;
- SignalR ;
- file de messages ;
- cache distribué.

---

## Impact sécurité

Le changement modifie-t-il les exigences de sécurité ?

Exemple :

Ouverture à des partenaires externes.

Conséquences :

- OAuth ;
- gestion des permissions ;
- journalisation.

---

## Impact réglementaire

Le changement entraîne-t-il de nouvelles obligations ?

Exemple :

Extension vers l'Europe.

Conséquences :

- RGPD ;
- conservation des données ;
- consentement.

---

## Impact économique

Quels coûts supplémentaires sont probables ?

- infrastructure ;
- stockage ;
- licences ;
- exploitation.

---

# Les dépendances

Le moteur analyse toutes les relations du Graphe de Connaissances.

Par exemple :

Nouvelle capacité

↓

Nouveaux objets métier

↓

Nouveaux événements

↓

Nouveaux processus

↓

Nouvelles API

↓

Nouvelle architecture

Le changement se propage dans le graphe.

---

# Les effets en cascade

Certaines décisions déclenchent des chaînes d'impacts.

Exemple :

Marketplace

↓

Paiements multiples

↓

Commissions

↓

Fiscalité

↓

Reporting

↓

Architecture financière

Le moteur doit rendre ces chaînes visibles.

---

# Analyse avant recommandation

Avant de recommander une architecture, le moteur répond notamment à ces questions :

- Quels concepts seront modifiés ?
- Quels processus devront évoluer ?
- Quels risques apparaissent ?
- Quelles nouvelles hypothèses devront être validées ?
- Quelles décisions existantes deviendront obsolètes ?

---

# Visualisation

Les impacts peuvent être représentés sous forme de graphe.

Chaque nœud impacté reçoit :

- son niveau d'impact ;
- sa criticité ;
- son ordre de propagation.

Cette représentation aide l'utilisateur à comprendre les conséquences d'un changement.

---

# Décisions prises

- Toute décision possède des conséquences.
- Les impacts sont analysés avant toute recommandation.
- Les effets directs et indirects sont distingués.
- Les chaînes d'impact sont explicables.
- Le Graphe de Connaissances constitue le support de cette analyse.

---

# Prochaine étape

Une fois les impacts connus, une nouvelle question apparaît.

**Comment transformer toutes ces connaissances en une architecture adaptée au contexte du produit ?**

Cette question sera traitée dans :

**11 - Architecture Intelligence**