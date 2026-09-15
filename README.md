<div align="center">

# AngAinOne

**L'atelier complet de ton PC gaming.**
Debloat Windows, pilotes GPU, réglages BIOS, tests de perf datés et vitrine partageable — le tout réversible et signé.

[![Version](https://img.shields.io/github/v/release/AngATV/AngAinOne?label=version&color=2fa88a)](https://github.com/AngATV/AngAinOne/releases/latest)
[![Windows 11](https://img.shields.io/badge/Windows-11%20(64--bit)-0a7bc4)](https://github.com/AngATV/AngAinOne/releases/latest)
[![Signé AngATV](https://img.shields.io/badge/signé-AngATV%20(Authenticode)-2fa88a)](#sécurité--confiance)
[![anga.tv](https://img.shields.io/badge/site-anga.tv-1f2733)](https://anga.tv)

### [⬇ Télécharger la dernière version](https://github.com/AngATV/AngAinOne/releases/latest)

</div>

---

## Téléchargement

Un seul fichier à télécharger : **`AngAinOne-win-Setup.exe`** (sur la [dernière release](https://github.com/AngATV/AngAinOne/releases/latest)).

| Fichier | Rôle |
|---|---|
| **`AngAinOne-win-Setup.exe`** | L'installeur : installe l'app + le service, et gère les mises à jour automatiques. |
| `AngAinOne-win-Setup.exe.sha256` | Empreinte SHA-256 de l'installeur, pour vérifier l'intégrité de ton téléchargement. |
| `*.nupkg` / `*.json` | Servent aux mises à jour automatiques — **à ne pas distribuer**. |

L'installeur est **signé Authenticode** (`CN=AngATV`) et **horodaté**. Une fois installée, l'app se met à jour **toute seule** — tu ne télécharges le Setup qu'une fois.

---

## Pourquoi AngAinOne

- **Réversible** — chaque optimisation conserve l'état Windows d'avant. Un clic pour tout annuler, et la désinstallation garde tes sauvegardes au lieu de les effacer.
- **Mesuré** — FPS, frametime, 1 % low, températures et goulots d'étranglement capturés image par image (PresentMon + capteurs matériels). Des chiffres datés, pas des promesses.
- **Sûr** — binaires signés, mises à jour vérifiées, aucun pilote installé sans ton accord. Ton compte te suit d'un PC à l'autre.

---

## Ce qu'il y a dedans

**Windows** — Optimisations réversibles · Démarrage · Nettoyage & réparation · Personnalisation · Réseau (DNS, latence)

**Applications** — Installer (winget) · Désinstaller · Debloat Windows

**Matériel** — Pilotes GPU (NVIDIA / AMD / Intel) · Réglages 3D · Écrans (HDR, VRR) · Alimentation · Disques · USB · BIOS

**Gaming** — Jeux (configs conseillées) · Sessions de jeu (FPS, à-coups, températures par partie) · Test de perf (CPU / mémoire / stockage / GPU) · Streaming · DLSS

**Presets** — enregistre, rejoue et partage une configuration complète, synchronisée avec ton compte.

**Diagnostic** — triangle défaut / recommandé / courant sur chaque réglage · Plantages (lecture des écrans bleus) · Logs du service en clair.

---

## Sécurité & confiance

- **Signature** — chaque binaire est signé Authenticode par **AngATV** et horodaté.
- **Mises à jour** — le service se met à jour lui-même, signature contrôlée, sans intervention.
- **Pilotes** — le pilote de capteurs bas niveau (PawnIO) ne s'installe **que si tu l'acceptes**.
- **Réversibilité** — l'état d'origine est conservé ; la désinstallation ne détruit rien.
- **Compte** — requis pour retrouver tes données (benchmarks, sessions, presets) sur [anga.tv](https://anga.tv).

---

## Installation

1. Lance **`AngAinOne-win-Setup.exe`**.
2. Au **premier lancement**, accepte l'**UAC** : le service Windows s'installe, puis l'assistant se lance (winget, RTSS optionnel).
3. Les versions suivantes se mettent à jour **dans l'app**, sans réinstaller.

## Configuration requise

**Windows 11** (64-bit).

---

<div align="center">

**[anga.tv](https://anga.tv)** · Éditeur **AngATV**

</div>
