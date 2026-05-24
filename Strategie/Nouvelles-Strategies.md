# Stratégies PPC Assist – Automatisations complètes

Ce document regroupe les 4 stratégies PPC automatisées mises en place dans PPC Assist pour optimiser les campagnes Amazon Ads.

---

## 1. Négativation automatique des termes de recherche

### 🎯 Objectif
Bloquer automatiquement les termes de recherche non rentables afin de protéger le budget et améliorer la pertinence des campagnes.

### 🔧 Déclencheur
- Terme de recherche

### 🧩 Types de campagnes
- AUTO
- SPP (manuelles)

### 📌 Conditions
- Coût ≥ 2.50
- Commandes = 0
- Clics ≥ 3
- Période : 7 derniers jours

### 🛠 Action
- Mettre en ciblage négatif (selon les options disponibles dans l’interface)

---

## 2. Mise en pause automatique des mots-clés perdants  
*(Alternative au “Bid Down” lorsque la baisse d’enchère n’est pas disponible)*

### 🎯 Objectif
Couper les mots-clés qui dépensent sans vendre, pour éviter les pertes et stabiliser l’ACOS.

### 🔧 Déclencheur
- Ciblage

### 🧩 Types de campagnes
- SPP (manuelles)

### 📌 Conditions
- Coût ≥ 2.50
- Commandes = 0
- Clics ≥ 3
- Période : 7 derniers jours

### 🛠 Action
- Mettre en ciblage négatif (équivalent fonctionnel à une baisse d’enchère radicale)

---

## 3. Extraction automatique des termes gagnants (Harvesting)

### 🎯 Objectif
Transformer automatiquement les termes de recherche performants en mots-clés EXACT dans la campagne d’origine.

### 🔧 Déclencheur
- Terme de recherche

### 🧩 Types de campagnes
- AUTO
- SPP (optionnel)

### 📌 Conditions
- Commandes ≥ 1
- ACOS ≤ 40%
- Clics ≥ 3
- Période : 7 derniers jours

### 🛠 Action
- Ajouter à la campagne d’origine
- Type : EXACT

---

## 4. Nettoyage automatique des ASIN (ASIN Cleaning)

### 🎯 Objectif
Désactiver automatiquement les ASIN non rentables dans les campagnes AUTO ou SPP.

### 🔧 Déclencheur
- Ciblage

### 🧩 Types de campagnes
- AUTO
- SPP (si ciblage produit manuel)

### 📌 Conditions
- Coût ≥ 2.50
- Commandes = 0
- Clics ≥ 3
- Période : 7 derniers jours

### 🛠 Action
- Désactiver le produit cible  
*(équivalent à un ASIN négatif dans ton interface)*

---

## ✔ Résultat global
Ces 4 stratégies créent un système PPC semi-automatisé qui :
- coupe les pertes  
- renforce les gagnants  
- nettoie les campagnes  
- améliore l’ACOS  
- réduit le temps de gestion  
- stabilise les performances  

