# Évaluation M1 – Conception Électronique

## Contexte

Dans le cadre de l’évaluation du module **Conception Électronique**, vous devez réaliser plusieurs travaux à l’aide du logiciel **Altium Designer**.

L’évaluation est composée de 3 parties pratiques :

- **Projet 1 → Partie 2 : Conception schématique**
- **Projet 2 → Partie 3 : Routage PCB**
- **Projet 3 → Partie 4 : Projet complet (schéma + routage)**



## Structure du dépôt

Le dépôt est organisé de la manière suivante :

```
/Projet_1   → Schématique à réaliser
/Projet_2   → Routage PCB à réaliser
/Projet_3   → Projet complet (schéma + PCB)
/Sujet      → Énoncé de l’évaluation

````

Chaque dossier contient :
- Un projet Altium  
- Les librairies nécessaires (SCH_Lib / PCB_Lib)  
- Les fichiers de base à compléter  


## Consignes générales

- Toutes les parties sont **indépendantes**  
- Le travail doit être réalisé **individuellement**  
- Vous devez utiliser **Altium Designer**  
- Respecter les contraintes indiquées dans le dossier **/Sujet**  



## Gestion Git (IMPORTANT)

### 🔹 1. Cloner le dépôt

```bash
git clone <URL_DU_DEPOT>
````

---

### 🔹 2. Créer votre branche

Vous devez créer une branche avec le format suivant :

```
prenom_nom
```

👉 Exemple :

```bash
git checkout -b jordan_clement
```

---

### 🔹 3. Travailler dans votre branche

⚠️ Ne jamais travailler sur `main`

```bash
git add .
git commit -m "Projet 1 terminé"
```

---

### 🔹 4. Pousser votre travail

```bash
git push origin prenom_nom
```

---

### ⚠️ Important

* Aucun rendu ne sera accepté sur la branche `main`
* Votre branche doit contenir **l’intégralité de votre travail**
* Vérifiez que vos fichiers sont bien poussés

---

## Travail attendu

### Projet 1 – Schématique

* Schéma complet et fonctionnel
* Organisation claire (blocs, nets nommés)

---

### Projet 2 – Routage PCB

* Placement logique des composants
* Routage complet
* DRC sans erreur

---

### Projet 3 – Projet complet

* Schématique fonctionnelle
* Routage PCB (complet ou partiel propre)
* Respect des contraintes

---

## ✅ Conseils

* Commencez par lire le sujet avant de commencer
* Soignez le placement avant de router
* Vérifiez régulièrement le DRC
* Travaillez proprement (noms de nets, organisation)

---

## 🚫 Règles

* Travail individuel
* Aucun échange de fichiers
* Respect des consignes

### Bon courage à tous !