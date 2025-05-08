# Roadmap de développement pour OWL

## 🟢 Phase 1 – Initialisation
- Créer la structure de projet (React Native ou Flutter, à choisir)
- Mettre en place un écran d’accueil avec bouton “Scanner une facture”

## 🟡 Phase 2 – Fonction OCR
- Intégrer OCR offline (ML Kit ou Tesseract)
- Scanner une facture imprimée (pas manuscrite)
- Extraire le texte brut

## 🟡 Phase 3 – Parsing et analyse
- Analyser les lignes extraites : produit, quantité, prix unitaire, total
- Détecter :
  - Les doublons
  - Les erreurs de calcul
  - Les montants > 1 000 000 DA

## 🟡 Phase 4 – Interface
- Afficher un tableau clair des données extraites
- Ajouter options : supprimer ligne, corriger, exporter

## 🟢 Phase 5 – Export
- Générer un fichier PDF de la facture analysée
- Stockage local uniquement

## 🔴 Ne pas faire :
- Pas de connexion serveur/API
- Pas de base de données en ligne
