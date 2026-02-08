# Bras Robotique 3D – Contrôle par Arduino

Projet de bras robotique imprimé en 3D, contrôlé par Arduino à l’aide de
potentiomètres, de boutons poussoirs, de servomoteurs et d’un moteur DC.

## 🎯 Objectif
Concevoir et réaliser un bras robotique capable de mouvements multi-axes,
en combinant mécanique (impression 3D), électronique et programmation.

## 🧩 Architecture du système
- Interface utilisateur : potentiomètres et boutons poussoirs  
- Unité de contrôle : Arduino Uno R4 WiFi  
- Actionneurs : servomoteurs MG90 et moteur DC  
- Structure mécanique : bras imprimé en PLA  
- Alimentation : module MB-102 externe  

## 🧰 Matériel utilisé
- Arduino Uno R4 WiFi (x1)
- Servomoteurs MG90 (x3)
- Moteur DC (x1)
- Driver moteur DC (x1)
- Potentiomètres 10kΩ (x3)
- Boutons poussoirs (x2)
- Module d’alimentation MB-102 (x1)
- Breadboard et mini breadboard
- Câbles Dupont
- Structure imprimée en 3D (PLA)

## ⚙️ Fonctionnement
Les potentiomètres génèrent une valeur analogique (0 à 1023) lue par l’Arduino.
Ces valeurs sont converties en angles de rotation (0 à 180°) pour piloter les
servomoteurs MG90.

Les boutons poussoirs permettent de commander le moteur DC via un driver,
afin de contrôler un mouvement supplémentaire du bras.

## 💻 Logiciels
- Arduino IDE : programmation
- Tinkercad : modélisation du bras
- Bambu Studio : préparation et impression 3D

## 📷 Résultats
*(Photos et/ou vidéo du bras robotique en fonctionnement)*

## 📈 Ce que j’ai appris
- Conversion d’entrées analogiques en commandes moteur
- Pilotage de servomoteurs et moteur DC
- Gestion d’une alimentation externe
- Conception et impression 3D de pièces mécaniques
- Intégration mécanique / électronique / logicielle

## 🚀 Améliorations possibles
- Ajout du WiFi (pilotage à distance)
- Augmentation du nombre d’axes
- Remplacement par des moteurs pas à pas
- Utilisation d’encodeurs rotatifs
- Amélioration du modèle 3D
- Création d’un boîtier de commande
- Soudure et passage sur plaque de prototypage

