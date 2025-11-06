# ISORHUM Project - Excel Tool

## Installation

To get started, clone the repository and open the Excel file:

```bash
git clone https://github.com/maximestph/Glaser-Predictor.git
cd mon-projet
```

## Introduction
This Excel file was developed as part of the ISORHUM project within the OMBREE program.  It was created through a collaboration between the PIMENT laboratory (University of La Réunion) and the IMAGREEN consulting firm. It is based on work carried out by all the partners involved in the ISORHUM project.

This workbook offers an a priori prediction of condensation risks over one year within an insulating wall, using the Glaser model.

The Glaser model is limited to describing the steady-state regime, unlike coupled heat, air, and moisture (HAM) models, which account for transient phenomena. This limitation should be considered, especially when two layers with high resistance to water vapor diffusion are stacked. In such cases, wall desorption is delayed, preventing the rapid attainment of the steady-state regime.

This document in no way replaces official reference texts, whether regulatory (laws, decrees, orders, etc.), normative (standards, DTUs, professional rules, RAGE and PACTE recommendations, or calculation rules), or codified (technical approvals, technical specifications guides, etc.), which must be consulted. The CSTB declines all responsibility for any direct or indirect consequences of any kind that may result from any misinterpretation of the content of this document.

**Author contact :** maxime.stephan-phd@protonmail.com	

## Color code

Un code couleur est utilisé dans les feuilles de calcul afin d’identifier leur rôle :

| Couleur  | Description                                   |
|----------|-----------------------------------------------|
| 🟧 Orange | Titre d'une cellule modifiable                |
| 🟨 Jaune  | Cellule modifiable                             |
| 🟩 Verte  | Cellule calculée (intermédiaire)              |
| 🟦 Bleu   | Cellule calculée (résultat)                    |
| ▫️ Grise  | Entête de tableau                              |
| ▫️ Grise  | Cellule vide                                  |
| ⬜ Blanche| Donnée calculée sur l'année, modifiable ou supprimable |
