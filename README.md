# Youpah ONE - GEN

## Overview
YOH-Client is a custom Minecraft 1.8.9 client with an integrated launcher, focused on custom branding, modular architecture, and a seamless user experience. Developed and maintained by Youpah.

## Key Facts
Role: Founder / Lead Developer
Version actuelle: 0.17
Base: Minecraft 1.8.9 (Forge compatible)
Tech: Java · Gradle · Mixin · Swing

- - - -

## Features
Launcher graphique intégré (Swing) avec gestion de comptes, sélecteur de versions et de loaders
Console intégrée dans le launcher — pas de fenêtre PowerShell visible
Auto-updater au démarrage (vérification via GitHub Releases API)
Branding personnalisé : logo Galaxy PvP Pack, écran de chargement YOH-GENS, watermark HUD en jeu
Support Forge et Vanilla
Mixin : brand client personnalisé (YOH-Client V0.17)
Gestion des favoris de version par compte

- - - -

## Tech Stack
Java (launcher Swing + client Minecraft)
Gradle (build system, fat JAR)
SpongePowered Mixin (injection bytecode)
Gson (parsing JSON — auto-updater, manifests)
Getting Started
Prérequis
Java 8+
IntelliJ IDEA (recommandé)

- - - -

## Clone & lancement

git clone https://github.com/MamyVentouse/YOH-Client.git
cd YOH-Client
./gradlew runClient

- - - -

## Build (fat JAR)

./gradlew fatJar
# → build/libs/YOH-Client-0.17.jar
