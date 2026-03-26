# IDEL Pro — Application Infirmier Libéral

Application complète de gestion pour les Infirmiers Libéraux en exercice libéral (IDEL).

## Liens de démonstration

- **Espace Professionnel :** https://bella2223.github.io/idel-pro/
- **Espace Patient :** https://bella2223.github.io/idel-pro/idel_patient.html

## Fonctionnalités

### Espace Professionnel (idel_pro.html)

- **Tableau de bord** — Vue d'ensemble avec KPI (visites du jour, CA, patients actifs, impayés), tournée du jour, facturation mensuelle et transmissions récentes
- **Planning** — Vue hebdomadaire des rendez-vous avec navigation semaine précédente/suivante
- **Tournée du jour** — Liste des visites du jour avec statuts (validé/refusé/en attente)
- **Dossiers patients** — Gestion complète des dossiers patients avec antécédents, traitements et historique
- **Soins & Actes** — Catalogue des soins avec tarification SESAM-Vitale, ajout de soins personnalisés
- **Transmissions** — Messagerie interne pour les notes de liaison
- **Facturation** — Module de facturation avec suivi des impayés et relances automatiques
- **Comptabilité** — Module complet avec bilan, TVA, dépenses
- **Statistiques** — Analyses graphiques (actes par mois, top actes, CA, temps moyen de tournée)
- **Messagerie MSS** — Messagerie sécurisée type MS Santé pour échanges patient-pro
- **Horloge analogique** — Affichage de l'heure en temps réel
- **Télétransmission** — Envoi des actes au format SESAM-Vitale
- **Notifications Push** — Alertes pour demandes en attente

### Espace Patient (idel_patient.html)

- **Vue générale** — Accueil personnalisé avec salutation et récapitulatif
- **Planning** — Voir ses rendez-vous à venir
- **Messages** — Échanger avec son infirmier (messagerie sécurisée)
- **Documents** — Accès aux documents médicaux partagés
- **Suivi santé** — Saisie des paramètres de santé (douleur, sommeil, température, glycémie, tension)
- **Mon Espace Santé** — Lien vers Mon Espace Santé

## Design

Style **Liquid Glass** inspiré du design Apple avec :
- Effet de verre givré (backdrop-filter)
- Dégradés subtils
- Animations fluides
- Interface claire et moderne

## Structure du projet

- `index.html` — Page de redirection vers l'application principale
- `idel_pro.html` — Application professionnelle complète
- `idel_patient.html` — Espace patient
- `style.css` — Feuilles de styles Liquid Glass (partagé)

## Hébergement

Application hébergée sur **GitHub Pages** avec :
- Hébergement certifié HDS (Hebergement de Données de Santé)
- Respect du RGPD
- Données stockées localement (localStorage)

## Utilisation

1. Ouvrir le lien de l'espace professionnel pour la version IDEL
2. Les données sont stockées dans le navigateur (localStorage)
3. Partager le lien de l'espace patient avec vos patients

## Version

v1.0 — IDEL Pro © 2026
