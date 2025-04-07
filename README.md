# 📄 Mini Automatisation Python : Génération d’un rapport PDF à partir d’un fichier Excel

Ce projet vous permet de créer un **mini rapport PDF automatique** à partir de n’importe quel fichier Excel structuré.\
Plus besoin de copier-coller manuellement dans Word ou PowerPoint : tout est fait automatiquement avec Python.

---

## ▶️ Lancer le script directement sur Google Colab

👉 https\://colab.research.google.com/drive/10vkDn52w71JSc9UcL2mBhYlceFRXvCsw#scrollTo=LxRUYLt1r2Ao

Vous pourrez uploader un fichier `.xlsx` et générer un fichier PDF avec un résumé automatique.

---

## 🔧 Fonctionnalités

- 📥 Lecture de fichiers Excel avec `pandas`
- 📊 Extraction d'indicateurs clés :
  - Nombre de lignes
  - Liste des colonnes
  - Contenu de la première ligne
- 🧾 Génération d’un fichier PDF structuré avec `fpdf`
- 🚀 Automatisation simple, sans interface complexe

---

## 🧪 Exemple de structure attendue dans l’Excel

| Nom       | Valeur | Date       |
| --------- | ------ | ---------- |
| Produit A | 1200   | 2025-03-01 |
| Produit B | 1500   | 2025-03-02 |
| ...       | ...    | ...        |

---

## 📁 Fichiers générés

- **rapport\_auto.pdf** : résumé automatique de votre fichier Excel

---

## 📚 Bibliothèques utilisées

- `pandas` : manipulation de données
- `fpdf` : génération de fichiers PDF

---

## 🧠 Auteur

Créé par [Ton Nom] dans le cadre d'une série de mini-automatisations pour les métiers opérationnels (RH, Qualité, Admin, Supply, etc.)

---

## 💬 Besoin d’une version personnalisée ?

Je peux vous aider à :

- Ajouter des indicateurs métier
- Générer des rapports graphiques
- Créer une interface utilisateur simple

---

## 🤝 Licence

Projet libre à usage personnel et professionnel.
