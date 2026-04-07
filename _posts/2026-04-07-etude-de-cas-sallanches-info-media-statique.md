---
layout: post
title: "Étude de cas : Pourquoi nous avons lancé Sallanches.info, le média 100% statique"
description: "Découvrez les coulisses techniques et stratégiques de Sallanches.info : un média local conçu pour la performance absolue, le SEO et la résilience."
date: 2026-04-07 12:00:00 +0200
category: Agence
author: La redaction
image: /assets/img/articles/etude-cas-sallanches-info.webp
tags: [jamstack, jekyll, seo, etude-de-cas, web-statique, performance]
---

Peut-on rivaliser avec les grands quotidiens régionaux en utilisant uniquement des technologies statiques ? C'est le défi que nous avons relevé avec le lancement de Sallanches.info. Retour sur les choix techniques et stratégiques d'un projet qui redéfinit l'information locale.

## L'objectif : L'indépendance par la performance

Lorsque nous avons conçu Sallanches.info, nos exigences étaient claires : 
1. **Zéro latence :** Un affichage instantané sur mobile (Core Web Vitals à 100%).
2. **SEO agressif :** Une structure pensée pour Google News et Discover dès le premier jour.
3. **Sécurité totale :** L'absence de base de données pour éliminer tout risque de piratage.

## La stack technique : Jekyll au service de l'info

Nous avons opté pour une architecture **JAMstack** basée sur le générateur de site statique **Jekyll** et un déploiement via **GitHub Pages**. Ce choix permet de servir des fichiers HTML purs, extrêmement légers et mis en cache de façon optimale.

### Les piliers du projet :
* **SEO technique :** Génération automatique de JSON-LD structurés pour chaque article et chaque événement d'agenda.
* **Optimisation des images :** Conversion systématique en WebP avec attributs de dimensions pour éviter le Layout Shift (CLS).
* **EEAT & Auteurs :** Un système de gestion des profils auteurs sans accents (via `slugify: ascii`) pour garantir l'autorité du média aux yeux des algorithmes.
* **Respect du RGPD :** Intégration de Tarteaucitron.js pour une gestion granulaire des scripts sans impacter l'expérience utilisateur.

## Un modèle de résilience pour l'avenir

Sallanches.info n'est pas seulement un site d'actualité, c'est une démonstration de force pour l'agence Duval DVL. Nous prouvons qu'avec une stratégie technique rigoureuse, un média indépendant peut obtenir une visibilité supérieure à des structures bien plus lourdes.

Ce projet sert aujourd'hui de laboratoire pour nos outils (Audit GMB, Simulateur ROI) et de vitrine pour notre vision du web de demain : rapide, sobre et centré sur l'utilisateur.
