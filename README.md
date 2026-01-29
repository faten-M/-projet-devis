
# Projet de stage – Automatisation de création de devis

##  Objectif du projet
Ce projet a pour but de générer automatiquement un devis brouillon à partir d’un e-mail client non structuré.  
Le système doit extraire les informations pertinentes, identifier les données manquantes ou ambiguës, puis produire un devis pré-rempli validable par un humain.

##  Périmètre du MVP
### Entrée
- Texte brut d’un e-mail client (copié/collé)
- Pas de pièces jointes dans la première version
- Ignorer signatures, disclaimers et réponses précédentes

### Sorties
- Un devis brouillon structuré (format JSON)
- Liste des champs :
  - identifiés
  - manquants
  - ambigus / incertains
- Un score de confiance global (0–100)

##  Structure du projet
- `index.js` : point d’entrée du projet Node.js
- `package.json` : configuration du projet





