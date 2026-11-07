# CyberTalents — Digital Forensics Writeups

Notes techniques et solutions de challenges **Digital Forensics** sur [CyberTalents](https://cybertalents.com/).

L'objectif de ce dépôt est de documenter les méthodes d'analyse utilisées : identification de formats, inspection hexadécimale, réparation de fichiers et validation de leur intégrité.

## Challenges

| Challenge | Catégorie | Technique principale | Writeup |
|---|---|---|---|
| [Err](https://cybertalents.com/challenges/forensics/err) | Forensics | Réparation PNG, IHDR, CRC32 | [Lire la solution](Err/README.md) |

## Organisation du dépôt

```text
CyberTalents-Forensics-Writeups/
├── README.md
└── Err/
    ├── README.md
    ├── Err-Writeup.pdf
    └── screenshots/
        ├── etape_01.png
        ├── etape_02.png
        └── ... etape_09.png
```

Le challenge **Duck** sera ajouté dans un dossier séparé après sa résolution.

## Outils

Linux, `file`, `xxd`, `dd`, Python 3, `zlib` et `struct`.

## Profil

CyberTalents :`https://cybertalents.com/members/laaroussidin/profile`

> **Spoiler :** les writeups contiennent des flags et des étapes de résolution. Essayez d'abord les challenges par vous-même.
