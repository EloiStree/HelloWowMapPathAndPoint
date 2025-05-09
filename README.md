# Hello Wow Map Path And Point

In the context of workshop in World of Warcraft. Let work in group on the paths and XP point of the game

> **ONLY ALPHA NUMERICAL and -_ allowed in file name.**

```aliasName.wowxpoint```   
`-xxxxx;-yyyyyy/n`   

```aliasName.wowpath```  
`-xxxxx;-yyyyyy/n`   

If in the file name:
`_era` Saved on Classic Era    
`_classic` Saved on classic  
`_retail` Saved on retail  


**Add a file `.credit` in your folder:**  

`.credit`
```
NOM:
PRENOM:
GITHUB:
LINKEDIN:
BUYMEBEER:
LICENSE:BEERWARE
```
APInt:https://buymeacoffee.com/apintio
IF you participate to this project it is by default to a [beerware license](https://fr.wikipedia.org/wiki/Beerware)

**Add a file `ReadMe.md` in your folder:**  

Present the files your provided to the community


Vo

**Petit exercice de Git :**

* Exercice : respecter une convention.
* Exercice : pratiquer les commandes `add .`, `commit`, `pull`, `push`.
* Exercice : laisser une faute dans le fichier et laisser le voisin la corriger pendant que l’on continue à travailler dessus.
* Exercice : créer une branche *development* quand on travaille en groupe.


Souhaites-tu que je reformule aussi pour plus de clarté ou fluidité ?


---------------

🤖


### 🧠 **Objectif pédagogique :**

* Apprendre les commandes de base `add`, `commit`, `pull`, `push`
* Travailler avec une convention de commit
* Travailler en groupe avec branches
* Pratiquer la collaboration en corrigeant les erreurs des autres

---

## 📝 Exercice Git : Collaboration & Convention

### 🎯 Étape 1 — Préparation initiale

1. Crée un dépôt Git (local ou distant via GitHub/GitLab).
2. Clone-le en local si nécessaire.
3. Décide d'une **convention de commit** (ex: [Conventional Commits](https://www.conventionalcommits.org/), ou simplement `type: message`, ex: `feat: ajout d'une fonctionnalité`).

---

### 🧩 Étape 2 — Travailler avec Git

#### Tâche individuelle :

Chaque participant va :

1. Créer un fichier `.md` ou `.txt` avec son prénom comme nom (ex: `paul.md`).
2. Écrire quelques lignes dedans, dont **une ligne contenant volontairement une faute**.
3. Exécuter :

   ```bash
   git add .
   git commit -m "feat: ajout du fichier paul.md avec contenu initial"
   git pull origin main  # ou master selon le nom de la branche
   git push origin main
   ```

---

### 🧑‍🤝‍🧑 Étape 3 — Correction entre pairs

1. Chaque participant choisit le fichier d’un autre.
2. Il/elle **corrige uniquement la faute** (ne pas modifier le reste).
3. Commit de correction avec un message du type :

   ```bash
   git add .
   git commit -m "fix: correction d'une faute dans le fichier paul.md"
   git push origin main
   ```

---

### 🌱 Étape 4 — Branches de développement

1. Créer une branche partagée pour un développement groupé :

   ```bash
   git checkout -b development
   git push origin development
   ```
2. Travailler à plusieurs sur cette branche, chacun modifiant un fichier différent.
3. Une fois le travail terminé, faire un **merge dans main** via pull request ou commande Git.

---

### 🔁 Étape 5 — Résolution de conflit (si souhaité)

Provoquez volontairement un conflit pour apprendre à le résoudre :

* Deux personnes modifient la même ligne d’un fichier sur deux branches différentes.
* Merge -> Conflit -> Résolution manuelle.


