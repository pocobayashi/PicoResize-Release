# ⚡ PicoResize

[日本語](README.md) | [English](README.en.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md)

---

**PicoResize** est une application de bureau Windows haute performance conçue pour le traitement par lots d'images (JPG, PNG, WebP, BMP, TIFF) et de documents PDF avec **recadrage automatique des marges**, **ajustement intelligent des proportions** et **compression à une taille cible (Mo)** dans un environnement local 100 % sécurisé et hors ligne.

---

## 🌟 Fonctionnalités clés

1. **Recadrage automatique des marges (Auto Trim)**
   - Détecte et supprime automatiquement les marges blanches et les bordures inutiles des photos, images numérisées et pages PDF.
2. **Redimensionnement intelligent adapté à l'orientation (Préservation du ratio d'aspect)**
   - Ajuste les images dans le cadre défini (ex. : `[ 640 ] × [ 480 ]`) :
     - **Images horizontales (Largeur ≥ Hauteur)** : S'ajuste dans Largeur × Hauteur = `640 × 480` en préservant les proportions.
     - **Images verticales (Hauteur > Largeur)** : S'ajuste dans Hauteur × Largeur = `640 × 480` (Largeur 480 × Hauteur 640) avec rotation automatique de l'orientation.
3. **Compression à la taille cible (Mo)**
   - Ajuste automatiquement la qualité de compression par recherche binaire pour garantir que les fichiers restent inférieurs à la taille cible (ex. : `0,5` Mo) avec une dégradation visuelle minimale.
4. **Renommage automatique des doublons**
   - Si un fichier portant le même nom existe déjà dans le dossier de destination, ajoute automatiquement `(2)`, `(3)`, etc., évitant ainsi tout écrasement accidentel.
5. **Traitement par lots homogène d'images et de PDF**
   - Glissez-déposez des fichiers PDF (première page tramée à 300 DPI) et divers formats d'image dans la même file d'attente de traitement.
6. **Empreinte mémoire ultra-faible (Stable à 10–20 Mo)**
   - Utilise le rognage de la mémoire de travail Win32, la virtualisation de l'interface utilisateur et la libération de la mémoire inactive pour maintenir une empreinte d'environ 10 Mo.
7. **Localisation complète en 8 langues**
   - 🌐 Prend en charge le japonais, l'anglais, le chinois simplifié, le chinois traditionnel, le coréen, l'espagnol, l'allemand et le français avec basculement instantané en temps réel.
8. **Mises à jour automatiques avec Velopack**
   - Intégration complète avec Velopack pour des mises à jour différentielles transparentes en un clic.

---

## 🖥️ Configuration requise
- **Système d'exploitation** : Windows 10 (version 2004 ou supérieure) / Windows 11 (x64)
- **Environnement d'exécution** : Autonome / Self-contained (aucun runtime .NET externe requis)

---

## 🚀 Prise en main
1. Définissez les dimensions du ratio (`Largeur × Hauteur`), la taille cible en Mo et le format de sortie (`JPEG / PNG / WebP`).
2. Glissez et déposez vos fichiers image ou PDF dans la zone dédiée (ou cliquez sur le bouton « Ajouter des fichiers »).
3. Cliquez sur « 🚀 Redimensionner & Enregistrer » et sélectionnez le dossier de destination.
4. Une fois l'opération terminée, une boîte de dialogue de confirmation s'affiche avec un accès direct au dossier de sortie.

---

## 📄 Licence
Licence MIT
