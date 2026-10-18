<!-- SPDX-License-Identifier: AGPL-3.0-only · Copyright (c) 2026 SBS BiM Consulting, Jordi Subirós -->
# guaitaMón

<p align="center">
<img src="https://img.shields.io/badge/versi%C3%B3-1.3-C6FF00?style=for-the-badge&labelColor=0b0d07" alt="v1.2">
<img src="https://img.shields.io/badge/llic%C3%A8ncia-AGPL--3.0--only-FF2ECC?style=for-the-badge&labelColor=0b0d07" alt="AGPL-3.0-only">
<img src="https://img.shields.io/badge/offline-0%20CDN-00E5FF?style=for-the-badge&labelColor=0b0d07" alt="offline">
</p>

<p align="center"><b>🇨🇦 <a href="#català">Català</a></b> · <b>🇬🇧 <a href="#english">English</a></b></p>

---

## Català

**guaitaMón** és la pàgina de presentació de la suite **Guaita Apps**: una declaració d'intencions, els principis de les eines, un catàleg i les dades de contacte. És un sol fitxer HTML, sense dependències externes i amb interfície en **català i anglès** (selector CA/EN a la capçalera).

### Fitxers

| Fitxer | Contingut |
|---|---|
| `index.html` | La pàgina de presentació (landing). És la que serveix GitHub Pages. |
| `guaitaMon.html` | Còpia idèntica d'`index.html`, per descarregar-la i obrir-la en local. |
| `LICENSE` | GNU Affero General Public License v3.0. |

### Catàleg d'eines

Al catàleg, les eines amb **repositori públic a GitHub** surten al capdamunt, amb la insígnia *Disponible*, un botó **Codi** (el repositori) i, si el repositori té `index.html`, un botó **Obre** (la pàgina publicada a `subi2.github.io/<repo>/`). La resta d'eines surten a *Properament*, sense enllaços.

Ara mateix, disponibles: guaitaPDF, guaitaApps, guaitaIFCparser, guaitaSKP, guaitaPreus, guaitaLaTeX, guaitaFitxers, guaita19650, guaitaNoms, guaitaBCF, guaitaPDFaMarkdown, guaita.md i guaitaHTMLeditor. Les que viuen dins de `guaitaApps` (`apps/`) s'obren amb l'adreça exacta del seu fitxer. Tres d'elles (guaitaBCF, guaitaPDFaMarkdown i guaitaHTMLeditor) carreguen recursos externs (cdnjs, Tailwind, markdown-it o Google Fonts) i ho indiquen amb una nota a la targeta.

Per fer disponible una eina, cal afegir-hi `repo` (i `url`, si té pàgina publicada) a la llista `EINES` del `<script>` d'`index.html`, i copiar el resultat a `guaitaMon.html`.

### Com s'usa

1. Obre `index.html` (o `guaitaMon.html`) en un navegador modern. No cal instal·lació ni connexió.
2. Per publicar-la, activa GitHub Pages sobre la branca `main` (carpeta arrel).

### Llicència

GNU Affero General Public License v3.0 only (`AGPL-3.0-only`). Vegeu [`LICENSE`](LICENSE).

Guaita Apps es distribueix «tal com és», sense cap garantia. Les eines estan pensades desde la recerca i com a suport tècnic i educatiu; la verificació dels resultats i la responsabilitat derivada del seu ús recauen únicament sobre l'usuari final.

### Contacte

guaitaapps@gmail.com · © 2026 SBS BiM Consulting, Jordi Subirós

---

## English

**guaitaMón** is the presentation page of the **Guaita Apps** suite: a statement of intent, the principles behind the tools, a catalogue and contact details. It is a single HTML file with no external dependencies and a **Catalan and English** interface (CA/EN switch in the header).

### Files

| File | Content |
|---|---|
| `index.html` | The presentation page (landing). This is what GitHub Pages serves. |
| `guaitaMon.html` | Identical copy of `index.html`, to download and open locally. |
| `LICENSE` | GNU Affero General Public License v3.0. |

### Tool catalogue

In the catalogue, tools with a **public GitHub repository** are listed first, with an *Available* badge, a **Code** button (the repository) and, if the repository has an `index.html`, an **Open** button (the page published at `subi2.github.io/<repo>/`). The remaining tools are listed under *Coming soon*, without links.

Currently available: guaitaPDF, guaitaApps, guaitaIFCparser, guaitaSKP, guaitaPreus, guaitaLaTeX, guaitaFitxers, guaita19650, guaitaNoms, guaitaBCF, guaitaPDFaMarkdown, guaita.md and guaitaHTMLeditor. Those that live inside `guaitaApps` (`apps/`) open with the exact address of their file. Three of them (guaitaBCF, guaitaPDFaMarkdown and guaitaHTMLeditor) load external resources (cdnjs, Tailwind, markdown-it or Google Fonts) and say so with a note on the card.

To make a tool available, add `repo` (and `url`, if it has a published page) to the `EINES` list in the `<script>` of `index.html`, then copy the result to `guaitaMon.html`.

### How to use

1. Open `index.html` (or `guaitaMon.html`) in a modern browser. No installation or connection needed.
2. To publish it, enable GitHub Pages on the `main` branch (root folder).

### License

GNU Affero General Public License v3.0 only (`AGPL-3.0-only`). See [`LICENSE`](LICENSE).

Guaita Apps is distributed "as is", without any warranty. The tools are designed from research and as technical and educational support; verification of the results and responsibility for their use rest solely with the end user.

### Contact

guaitaapps@gmail.com · © 2026 SBS BiM Consulting, Jordi Subirós
