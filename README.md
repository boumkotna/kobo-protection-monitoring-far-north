# 🛡️ Protection Monitoring - Extrême-Nord Cameroun 2026

Formulaire numérique de monitoring de protection pour les départements du Mayo-Sava et Logone-et-Chari.

**🔗 Lien du formulaire en ligne :** https://ee.kobotoolbox.org/x/2awkkexS

## 📍 Contexte
Projet conçu pour le suivi des incidents de protection dans la région de l'Extrême-Nord, affectée par les déplacements forcés et l'insécurité. Le système permet une collecte rapide sur téléphone par des enquêteurs terrain sans connexion permanente.

Zone d'intervention :
- Mayo-Sava
- mayo-Tsanaga
- Logone-et-Chari

## 🎯 Objectifs
- Documenter les incidents de protection (intimidation, extorsion, restriction de mouvement, etc.)
- Identifier les personnes à besoins spécifiques
- Alerter et référer les cas critiques
- Générer des données exploitables pour le cluster Protection

## 📋 Structure du formulaire
Le formulaire est développé en XLSForm et déployé sur KoboToolbox.

**Sections clés :**
1. Identification (Département, Arrondissement, Site)
2. Type d'incident et description
3. Profil de la victime / survivant
4. Auteur présumé et lieu
5. Action prise / Référencement
6. Consentement et confidentialité

Types de questions utilisées : `select_one`, `select_multiple`, `text`, `integer`, `geopoint`, `date`, `relevance`, `constraint`.

## 🛠️ Stack Technique
- **Outil de collecte :** KoboToolbox / ODK
- **Design :** XLSForm (Excel)
- **Déploiement :** Enketo Webform + KoboCollect Android
- **Analyse :** Excel / Power BI
- **Gestion de version :** GitHub

## 🚀 Comment déployer ce formulaire

1. Télécharger `XLSForm.xlsx`
2. Aller sur https://kf.kobotoolbox.org
3. New Project > Upload an XLSForm
4. Cliquer sur DEPLOY
5. Cocher "Allow submission without username and password"
6. Partager le lien Enketo aux enquêteurs

## 📊 Gestion des données
Les données sont consultables dans l'onglet `DATA` de KoboToolbox. Export possible en XLS, CSV pour analyse et cartographie.

> ⚠️ Données sensibles : Ce dépôt contient uniquement la structure du formulaire. Aucune donnée personnelle identifiable n'est publiée, conformément aux principes de protection des données.

## 👤 Auteur
**[BOUM KOTNA Cédric]**
Fellow in Administration and IT at the Office of the United Nations High Commissioner for Human Rights Regional Hub for Central and West Africa (OHCHR RHCWA)| Spécialiste KoboToolbox & Information Management
Extrême-Nord, Cameroun

Compétences : Protection Monitoring, Project Design, XLSForm Avancé, KoboToolbox, Gestion de données humanitaires, Result-Based Management.

---
*Projet réalisé en 2026 dans le cadre du renforcement du système de monitoring de protection.*
