<div align="center">

<!-- <img src="docs/assets/logo.png" alt="AngAinOne" width="100" /> -->

# AngAinOne

**L'outil tout-en-un pour avoir un PC au top.**  
Optimisations · BIOS · Monitoring · Benchmarks · Drivers · Debloat · Communauté

[![Windows](https://img.shields.io/badge/Windows-11-0078d4?logo=windows&logoColor=white)](https://github.com/AngATV/AngAinOne/releases/latest)
[![.NET 9](https://img.shields.io/badge/.NET-9-512bd4?logo=dotnet&logoColor=white)](https://dotnet.microsoft.com)
[![Téléchargement](https://img.shields.io/github/v/release/AngATV/AngAinOne?label=Derni%C3%A8re%20version&color=22c55e)](https://github.com/AngATV/AngAinOne/releases/latest)
[![Site](https://img.shields.io/badge/Site-anga.tv%2FAngAinOne-3b82f6)](https://anga.tv/AngAinOne)

[**⬇️ Télécharger**](#-installation) · [**🌐 Site web**](https://anga.tv/AngAinOne) · [**🏆 Classements**](https://anga.tv/AngAinOne/benchmarks) · [**👤 Profils**](https://anga.tv/AngAinOne)

</div>

---

## C'est quoi AngAinOne ?

Un écosystème complet — **une app Windows** + **un site web** — conçu pour les joueurs et passionnés de PC qui veulent tirer le maximum de leur machine, et comparer leurs résultats avec le reste de la communauté.

Côté app : monitoring en direct, optimisations en un clic, **lecture et modification du BIOS depuis Windows**, gestion complète des drivers GPU, benchmarks intégrés, nettoyage de Windows, presets de configuration sauvegardables.

Côté site : profil public, comparaisons face-à-face, classements communautaires, détection intelligente de problèmes matériels ou de drivers — le tout partagé et exploitable collectivement.

---

## 🖥️ L'application desktop (Windows 11)

### 📊 Dashboard temps réel
Toutes tes infos matérielles au même endroit. CPU, GPU, RAM, stockage — températures, fréquences, consommation, charge. Tout s'actualise en direct pendant que tu joues ou que tu travailles.

Détection automatique du matériel : modèle exact de ta carte graphique (MSI Gaming X Trio, ASUS ROG STRIX, Gigabyte Aorus...), CPU, barrettes RAM, volumes disque.

### ⚙️ Optimisations Windows
59 tweaks système organisés par catégorie, activables en un clic :

- **Performance** — Superfetch, NTFS, planificateur, animations inutiles…
- **Interface** — Supprime les éléments qui traînent, personnalise l'explorateur
- **Confidentialité** — Télémétrie, Cortana, localisation, diagnostics…
- **Sécurité** — UAC, Credential Guard, options de démarrage
- **Maintenance** — Autoplay, Bureau à distance, mises à jour automatiques…

Chaque optimisation est réversible. Tes choix sont sauvegardés sur ton compte et visibles sur ton profil public.

### 🧹 Debloat Windows
145 applications préinstallées identifiées et supprimables proprement. Apps Microsoft inutiles, bloatware OEM (HP, Dell, Lenovo…), apps tierces — tu choisis ce que tu vires.

Un point de restauration est créé avant toute suppression.

### 🎮 Pilotes GPU — Nettoyage & réinstallation complète
L'app prend en charge l'intégralité du cycle driver :

1. **Détection** du driver actuel et de ta carte (modèle exact reconnu)
2. **Désinstallation propre** — suppression totale du driver et de toutes ses dépendances
3. **Réinstallation** de la version choisie
4. **Configuration automatique** des paramètres du pilote post-installation

Compatible **NVIDIA (GeForce)** et **AMD (Radeon)**.

### 🔥 Benchmarks intégrés
Lance tes benchmarks directement depuis l'app, sans jongler entre 5 outils :

| Benchmark | Ce que ça mesure |
|-----------|-----------------|
| **Cinebench 2024** | Puissance CPU (mono & multi-core) |
| **3DMark** | Performances GPU en jeu |
| **CrystalDiskMark** | Vitesses SSD / NVMe |
| **FurMark 2** | Stress GPU — température & stabilité |
| **OCCT** | Stabilité système sous charge max |

Les résultats sont archivés localement et synchronisés avec ton profil. Tu peux les publier pour apparaître dans les classements et les comparer avec d'autres.

### 💾 Presets — Sauvegarde & restauration complète
Optimise ton PC une bonne fois pour toutes : active tes optimisations, installe tes apps, configure tes settings. Ensuite, **sauvegarde tout en un preset**.

Si tu formates ou changes de PC, charge ton preset et l'app remet tout en place automatiquement — réapplique les optimisations, réinstalle les logiciels, restaure tes configurations. Ton PC retrouve son état exact en quelques clics.

Les presets peuvent être **partagés publiquement** sur le site pour que la communauté puisse les utiliser.

### 🧬 BIOS — Lecture, analyse et modification sans entrer dans l'UEFI

C'est probablement la fonctionnalité la plus unique de l'app. AngAinOne peut **lire l'intégralité des paramètres de ton BIOS depuis Windows**, les afficher avec des explications claires, et même les **modifier directement** — sans avoir à redémarrer dans l'UEFI, sans chercher un réglage pendant 10 minutes.

#### Comment ça marche

L'app passe par **SCEWIN** (l'outil officiel AMI utilisé par les fabricants pour le BIOS) pour extraire toute la NVRAM de ta carte mère. Cette extraction est vérifiée par checksum pour garantir son intégrité. Depuis Windows, sans reboot, sans risque.

Compatible avec les cartes mères **AMI (ASUS, MSI, Gigabyte, ASRock, B450, X570, B550, Z690, X870E...)**.

#### Ce qui est affiché

Des **centaines de paramètres BIOS** classés par catégorie et filtrés intelligemment :

- **Overclock / fréquences** — limites de puissance CPU, PBO, fréquences DRAM
- **Mémoire** — XMP / EXPO, fréquences, timings
- **PCIe** — Resizable BAR, Above 4G Decoding, génération
- **Alimentation** — C-States, modes économie d'énergie, power limits
- **Boot** — Fast Boot, Secure Boot, ordre de démarrage
- **Sécurité** — Virtualisation, TPM, Credential Guard

Chaque paramètre affiche sa **valeur actuelle**, la **valeur par défaut constructeur**, et une **infobulle explicative** rédigée en français — ce que ça fait, pourquoi c'est important, et si c'est recommandé pour le gaming (**★**).

Trois niveaux de lecture selon ton niveau :
- **Essentiel** (~25 paramètres) — les réglages qui ont le plus d'impact immédiat
- **Pro** (~80 paramètres) — pour aller plus loin
- **Extrême** — tout, sans filtre

#### Modification depuis l'app

Tu peux **changer la valeur de n'importe quel paramètre compatible** directement depuis l'interface, sans toucher à l'UEFI. L'app génère les changements, les applique via SCEWIN, et te demande de redémarrer. C'est tout.

Des **presets intégrés** permettent d'appliquer en un clic des profils optimisés :
- **Gaming** — désactive les économies d'énergie, active ReBAR, optimise les latences
- **Ultra low latency** — configuration orientée compétitif
- **Mémoire** — active XMP / EXPO automatiquement
- **Défauts constructeur** — restaure tout tel quel à l'état d'usine

#### Synchronisation et profil

Ton snapshot BIOS est synchronisé sur ton compte et peut être **rendu public** sur ton profil. Les autres utilisateurs ayant la même carte mère peuvent voir tes réglages, comparer avec les leurs, et voir des **stats communauté** par modèle de carte.

---

### 🎬 Streaming (OBS)
Détection automatique d'OBS, recommandations matérielles, gestion de plugins et templates, configuration guidée.

---

## 🌐 Le site web — [anga.tv/AngAinOne](https://anga.tv/AngAinOne)

Le site est le **prolongement communautaire** de l'app. Toutes les données collectées par l'app s'y retrouvent, analysées, comparées et partagées.

### 👤 Profil public
Chaque utilisateur a une vitrine personnelle avec sa config complète — matériel détecté, optimisations appliquées, scores de benchmark, setup photo/bio. Accessible par n'importe qui depuis `anga.tv/AngAinOne/pseudo`.

### 🏆 Classements benchmarks — [anga.tv/AngAinOne/benchmarks](https://anga.tv/AngAinOne/benchmarks)
Tous les scores de la communauté dans un seul classement. Filtrable par :
- **Marque GPU** (MSI, ASUS, Gigabyte, NVIDIA…)
- **Modèle de chip** (RTX 4090, RX 7900 XTX…)
- **CPU brand** (Intel, AMD)

Les stats montrent aussi la distribution matérielle de la communauté : quels GPU sont les plus présents, quelles configs dominent les classements.

### ⚖️ Comparateur face-à-face — [anga.tv/AngAinOne/compare](https://anga.tv/AngAinOne/compare)
Compare deux profils publics côte à côte : scores, températures, consommation, fiabilité, différences de configuration BIOS. Idéal pour voir pourquoi deux PC similaires ont des performances différentes et comprendre ce qui fait la différence.

**Cas d'usage typique** : tu as le même GPU qu'un autre utilisateur mais des scores inférieurs — la comparaison te montre exactement quelles optimisations il a appliquées et que tu n'as pas.

### 🔍 Analyse intelligente & détection communautaire
C'est là que ça devient vraiment intéressant. Quand suffisamment d'utilisateurs partagent leurs données :

- **Corrélations matérielles** : on peut détecter que certains drivers causent des pics de température sur un GPU spécifique, que certaines configurations BIOS ont un impact mesurable sur les scores, ou qu'un problème touche une gamme de matériel en particulier.
- **Alertes proactives** : si ta config ressemble à des PC qui montrent un problème connu, le site peut te le signaler avant que tu ne le remarques toi-même.
- **Remontée d'informations** : les patterns détectés collectivement peuvent être remontés aux équipes de développement de drivers ou de fabricants — une contribution concrète à l'amélioration des logiciels pour tout le monde.

### 🤝 Activité communautaire
La page activité te connecte avec des utilisateurs ayant un matériel similaire. Voir comment les autres configurent le même GPU que toi, quels presets ils utilisent, où ils se situent dans les classements.

### 🔗 Partage de presets
Partage ta configuration optimisée avec la communauté via un lien. N'importe qui peut voir ton preset, l'importer dans l'app et l'appliquer sur son propre PC.

### 📈 Historique & timeline
Tout l'historique de tes snapshots système, organisé en timeline. Vois l'évolution de tes optimisations, tes scores dans le temps, les changements de config.

### 🔧 PC Builder — [anga.tv/AngAinOne/config](https://anga.tv/AngAinOne/config)
Un configurateur PC qui ne référence que du matériel sélectionné et testé par nos soins. Tu choisis tes composants parmi notre catalogue, et le builder vérifie **automatiquement la compatibilité** en temps réel :

- **Socket** CPU / carte mère
- **Types et fréquences RAM** supportés par le CPU et la carte mère
- **Format de la carte mère** vs espace disponible dans le boîtier
- **Longueur du GPU** vs espace boîtier
- **Hauteur du ventirad air** vs espace boîtier
- **Taille du radiateur AIO** vs emplacements supportés par le boîtier
- **Slots M.2** disponibles et génération PCIe (avec avertissement si downgrade)
- **Ports SATA** disponibles
- **Wattage de l'alim** par rapport à la consommation estimée (TDP CPU + TDP GPU + marge), avec avertissement si insuffisant
- **Compatibilité ventilateurs** : taille et quantité max par emplacement boîtier

Le configurateur affiche en permanence le **total des prix** avec liens Amazon directs pour chaque composant et un **panier en un clic**.

Chaque semaine, une **config de la semaine** est mise en avant — soit une sélection éditoriale de notre équipe, soit une génération automatique basée sur les meilleurs rapports qualité/prix du catalogue du moment.

Les configs peuvent être **sauvegardées et partagées** via un lien public. N'importe qui peut voir ta config, les pièces, les prix, et l'ajouter à son panier Amazon.

### 🗄️ Base de données matériel — [anga.tv/AngAinOne/hardware-info](https://anga.tv/AngAinOne/hardware-info)
Une référence technique complète sur tous les composants que nous connaissons et recommandons. Organisée par catégorie (CPU, GPU, RAM, stockage, carte mère, boîtier, alim, refroidissement), elle rassemble pour chaque modèle les specs techniques précises que nous avons nous-mêmes ajoutées et vérifiées :

- **CPU** : socket, TDP, types RAM supportés, fréquence max, slots M.2 supportés
- **GPU** : VRAM, bande passante mémoire, TDP, longueur physique, performances estimées en 1440p et 4K Ultra, alimentation recommandée, tier de performance
- **RAM** : type, fréquence, kit, vitesse
- **Stockage** : interface, capacité, type NAND, débits séquentiels en lecture et écriture
- **Carte mère** : socket, format, slots M.2, génération PCIe, ports SATA
- **Boîtier** : formats supportés, longueur GPU max, hauteur ventirad max, emplacements radiateurs, support ventilateurs
- **Alimentation** : wattage, certification
- **Refroidissement** : hauteur (air), taille radiateur (AIO), sockets supportés

Cette base est **curatée manuellement** — seul du matériel que nous connaissons et dont nous pouvons garantir les données y figure. Elle sert à la fois de référence publique et alimente le PC Builder pour ses vérifications de compatibilité.

---

## ⬇️ Installation

1. Va sur la page **[Releases](https://github.com/AngATV/AngAinOne/releases/latest)**
2. Télécharge `AngAinOne-Setup.exe`
3. Lance l'installeur et suis les étapes
4. L'app et le service Windows s'installent automatiquement
5. Connecte-toi avec ton compte [anga.tv/AngAinOne](https://anga.tv/AngAinOne) pour synchroniser

> Le service Windows (`AngAinOne.Service`) est nécessaire pour les fonctions système. L'app te prévient s'il n'est pas actif.

### Configuration requise

| | |
|--|--|
| **OS** | Windows 11 |
| **Architecture** | x64 |
| **RAM** | 4 Go minimum |
| **Espace disque** | ~150 Mo |
| **Réseau** | Requis pour la synchronisation et les classements |

---

## 🔒 Sécurité & vie privée

- **Aucune donnée vendue.** Les infos matérielles ne quittent ton PC que si tu crées un profil public (opt-in explicite).
- **Communication locale chiffrée** entre l'interface et le service Windows — signature cryptographique sur chaque requête.
- **Tu contrôles ce que tu partages.** Chaque benchmark, chaque info matérielle est publiable ou non selon ton choix.

---

## 🌐 L'écosystème

| | |
|--|--|
| **Site & téléchargement** | [anga.tv/AngAinOne](https://anga.tv/AngAinOne) |
| **Profils publics** | [anga.tv/AngAinOne/pseudo](https://anga.tv/AngAinOne) — config, scores, matériel |
| **Classements benchmarks** | [anga.tv/AngAinOne/benchmarks](https://anga.tv/AngAinOne/benchmarks) — filtrables par GPU, marque, modèle |
| **Comparateur** | [anga.tv/AngAinOne/compare](https://anga.tv/AngAinOne/compare) — face-à-face entre deux profils |
| **PC Builder** | [anga.tv/AngAinOne/config](https://anga.tv/AngAinOne/config) — configurateur avec compatibilité en temps réel |
| **Base matériel** | [anga.tv/AngAinOne/hardware-info](https://anga.tv/AngAinOne/hardware-info) — specs techniques par composant |

---

## 🐛 Problème ou suggestion ?

Ouvre une **[Issue](https://github.com/AngATV/AngAinOne/issues)** en décrivant ce que tu as observé. Pour les bugs, précise ta version Windows, ton GPU et la version de l'app (visible dans le menu).

---

<div align="center">

Fait avec 🖤 par **[AngA](https://anga.tv/AngAinOne)**

</div>
