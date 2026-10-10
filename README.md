# 🌐 STM32WB55 BLE & IoT Monitoring System Design Board

> Carte de monitoring IoT sans fil bicoeur (Cortex-M4 + Cortex-M0+) propulsée par le microcontrôleur **STM32WB55**, conçue pour l'acquisition de données et la transmission BLE (Bluetooth Low Energy).

---

## 📋 Table des matières
- [Aperçu du projet](#-aperçu-du-projet)
- [Fonctionnalités principales](#-fonctionnalités-principales)
- [Arborescence du projet](#-arborescence-du-projet)
- [Structure du matériel (KiCad)](#-structure-du-matériel-kicad)
- [Guide de démarrage rapide](#-guide-de-démarrage-rapide)
- [Auteur](#-auteur)

---

## 🚀 Aperçu du projet
Ce projet consiste en la conception complète d'une carte électronique dédiée au monitoring IoT. Basée sur le SoC sans fil **STM32WB55**, elle associe des performances de calcul et une connectivité radio basse consommation (Bluetooth 5.0).

---

## ✨ Fonctionnalités principales
- **Microcontrôleur principal :** STM32WB55xx (Dual-Core : ARM Cortex-M4 pour l'application & Cortex-M0+ pour la pile Bluetooth).
- **Connectivité :** Bluetooth Low Energy (BLE).
- **Conception CAO :** Réalisé sous **KiCad** (schéma, routage PCB, empreintes et bibliothèques personnalisées).

---

## 📂 Arborescence du projet
Voici l'organisation des fichiers de ce dépôt[cite: 1] :

```tree
STM32WB_BLE/
├── Docs/                       # Documentation, datasheets et notes techniques
├── DFL_Library.pretty/         # Empreintes KiCad personnalisées
├── DFL_Library.kicad_sym       # Symboles schématiques personnalisés
├── STM32WB_BLE.kicad_pro       # Fichier projet KiCad principal
├── STM32WB_BLE.kicad_sch       # Schéma électronique
├── STM32WB_BLE.kicad_pcb       # Routage du PCB
├── STM32WB_BLE.csv             # Nomenclature (BOM)
└── .history/                   # Historique et versions de conception
