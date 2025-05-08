# Facture DZ

Facture DZ est une application Android destinée à scanner et analyser automatiquement des factures imprimées en français (non manuscrites), utilisée dans le contexte algérien.

## Objectifs

- Scanner des factures via la caméra (OCR offline)
- Extraire les données : produit, quantité, prix, montant total, date
- Détecter les erreurs de calcul ou les doublons
- Alerter si le montant dépasse un seuil (ex: 1 million DA)
- Afficher les données extraites dans une interface claire
- Export optionnel en PDF
- Application 100% offline (aucune API externe)

## Contraintes techniques

- Android 9+ compatible
- OCR avec ML Kit ou Tesseract
- Pas de backend (stockage local uniquement)
- UI moderne (vert & blanc), en français
