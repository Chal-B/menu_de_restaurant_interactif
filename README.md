<div align="center">

# 🍲 La Marmite Congolaise

**Menu de restaurant congolais complet — 39 plats, 4 tableaux de prix et formulaire de réservation**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/CSS)
[![Akieni Academy](https://img.shields.io/badge/Akieni-Academy-2563eb?style=flat-square)](https://akieni.com)
[![W3C](https://img.shields.io/badge/W3C-Validé-22c55e?style=flat-square)](https://validator.w3.org/)

[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](#)
[![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![Stars](https://img.shields.io/github/stars/Chal-B/menu_de_restaurant_interactif?style=social)](https://github.com/Chal-B/menu_de_restaurant_interactif)

[Installation](#-installation) · [Architecture](#-architecture-du-projet) · [Contribuer](#-contribuer) · [Contact](#-contact)

</div>

---

## 📖 Table des matières

- [À propos](#-à-propos)
- [Fonctionnalités](#-fonctionnalités)
- [Prérequis](#-prérequis)
- [Installation](#-installation)
- [Utilisation](#-utilisation)
- [Architecture du projet](#-architecture-du-projet)
- [Technologies utilisées](#-technologies-utilisées)
- [Tests](#-tests)
- [Contribuer](#-contribuer)
- [Contact](#-contact)

---

##  À propos

Menu digital du restaurant **La Marmite Congolaise** (Brazzaville). Plus de 30 plats traditionnels congolais organisés en sections, avec photos, prix en FCFA et réservation en ligne.

> 💡 Chaque plat est un `<article>` sémantique avec `<figure>`, description et `<data value>` pour les prix.

##  Fonctionnalités

- ✅ **39 articles** — entrées, plats, desserts, boissons
- ✅ **4 tableaux de prix** — récapitulatifs par catégorie
- ✅ **Spécial du jour** — promo Poulet à la Moambe (8 500 vs 10 000 FCFA)
- ✅ **73 images** — photos jpg/webp + illustrations SVG
- ✅ **Formulaire réservation** — 3 `<fieldset>` (coordonnées, date, demandes)
- ✅ **Horaires** — `<dl>` structuré

##  Prérequis

- Navigateur web moderne
- *(Optionnel)* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

##  Installation

```bash
git clone https://github.com/Chal-B/menu_de_restaurant_interactif.git
cd menu_de_restaurant_interactif
```

Ouvrir **`restaurant/index.html`** dans le navigateur.

> Les chemins d'images (`../images/`) nécessitent de conserver la structure de dossiers.

##  Utilisation

Projet statique — parcourir le menu via la navigation (Entrées, Plats, Desserts, Boissons, Réservation).

##  Architecture du projet

```
menu_de restaurant_interactif/
├── restaurant/
│   └── index.html      # Point d'entrée (~958 lignes)
├── images/             # Photos plats + SVG
└── README.md
```

## Technologies utilisées

| Catégorie | Technologie |
|---|---|
| Structure | HTML5 sémantique (`ul > li > article`) |
| Données | `<data value>`, `<table>`, `<dl>`, `<address>` |
| Formulaires | `<fieldset>`, `<legend>`, types variés |
| Validation | W3C HTML — 0 erreur |

##  Tests

- [Validateur HTML W3C](https://validator.w3.org/#validate_by_input)

## 📬 Contact

**MALONGA Saint Chalbhery** — [GitHub @Chal-B](https://github.com/Chal-B) — saintmlg@icloud.com

Lien du projet : [https://github.com/Chal-B/menu_de_restaurant_interactif](https://github.com/Chal-B/menu_de_restaurant_interactif)

---
