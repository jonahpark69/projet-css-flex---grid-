# 🧩 Exercice — Choisir entre **CSS Grid** et **Flexbox**

> Atelier d’intégration : intégrer plusieurs blocs issus d’une maquette Figma en choisissant **la bonne méthode de positionnement** (Grid ou Flex) et **justifier** ce choix dans l’interface.

---

## 📑 Sommaire

* [Objectif de l'exercice](#-objectif-de-lexercice)
* [Instructions](#-instructions)
* [Fichiers fournis](#-fichiers-fournis)
* [Démarrage rapide](#-démarrage-rapide)
* [Critères d’évaluation](#-critères-dévaluation)
* [Conseils : Grid ou Flex ?](#-conseils--grid-ou-flex-)
* [Modèles de justification (très simples)](#-modèles-de-justification-très-simples)
* [Bonus (mobile)](#-bonus-mobile)
* [Livrables attendus](#-livrables-attendus)

---

## 🎯 Objectif de l'exercice

Dans cet atelier, vous intégrez des **blocs d’interface** extraits d’une maquette Figma. Pour chaque bloc, vous devez **choisir** entre **Flexbox** et **Grid**, puis **expliquer brièvement** ce choix **directement dans l’interface** (un court paragraphe sous le bloc).

L’objectif est de montrer un **CSS fonctionnel** et une **compréhension claire** des concepts de layout.

---

## ✅ Instructions

1. Analysez chaque bloc (structure visuelle, axes, répétitions).
2. Intégrez le HTML/CSS du bloc.
3. Ajoutez une **courte justification** sous le bloc.
4. **Bonus** : proposez une version mobile.
5. Testez le rendu dans le navigateur.

---

## 📦 Fichiers fournis

```plaintext
/R0002_exercice
  ├── style.css  
  ├── index.html
  └── README.md  # Explication du projet
```

---

## 🚀 Démarrage rapide

```bash
# Ouvrir un serveur local (au choix)
python3 -m http.server 5173
# ou
npx serve .
# puis http://localhost:5173
```

> Ou ouvrez simplement `index.html` dans le navigateur (les chemins relatifs doivent fonctionner).

---

## 🧪 Critères d’évaluation

* **Fidélité visuelle** à la maquette (espaces, alignements, tailles).
* **Pertinence du choix** Grid/Flex et propreté du code.
* **Sémantique HTML** (balises adaptées, titres hiérarchisés).
* **Accessibilité de base** (focus visibles, `alt`, contrastes).
* **Responsive** raisonnable (bonus si pertinent).
* **Justification** claire, courte et compréhensible.

---

## 🧭 Conseils : Grid ou Flex ?

**Utilisez *Grid* si…**

* la **mise en page a 2 dimensions** (lignes **et** colonnes),
* il y a des **alignements verticaux/horizontaux** simultanés,
* vous avez besoin de **pistes/gouttières régulières**.

**Utilisez *Flex* si…**

* vous alignez des éléments **sur un axe** (ligne **ou** colonne),
* l’ordre et la répartition (**gap / wrap / justify / align**) suffisent,
* vous gérez une **barre** (nav, boutons, cartes en ligne).

> Règle rapide : **Barre → Flex** ; **Grille → Grid**.

---

## ✍️ Modèles de justification (très simples)

* **Version Grid (courte)** :
  *« J’utilise **CSS Grid** car la section comporte plusieurs **lignes et colonnes** à aligner avec des **gouttières régulières**. »*
* **Version Flex (courte)** :
  *« J’utilise **Flexbox** car les éléments sont **sur un seul axe** et je gère l’espace avec **justify/align/gap**. »*
* **Variante (ultra‑simple)** :
  *« **Grid** pour le **2D**, **Flex** pour le **1D**. »*

---

## 📱 Bonus (mobile)

* Empilement progressif (de 3→2→1 colonnes pour une grille).
* Ajuster tailles de typo/espacements (rem/px simples).
* Conserver des **focus visibles** et des zones cliquables suffisantes.

---

## 📤 Livrables attendus

* Le dossier du projet avec **`index.html`** et **`style.css`**.
* Des **justifications** visibles sous chaque bloc intégré.
* (Optionnel) **Captures** desktop/mobile dans un dossier `captures/`.
