---
title: "Interface en ligne de commande"
linkTitle: "Command Line Interface"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Convertissez des documents directement depuis le terminal avec l'outil en ligne de commande groupdocs-conversion — aucun script Python requis. Inspectez les documents, listez les formats pris en charge et appliquez une licence, le tout depuis le shell."
type: docs
url: /fr/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


L'installation du package `groupdocs-conversion-net` ajoute également un script console `groupdocs-conversion` à votre `PATH`. Il s'agit d'un léger wrapper autour de l'API Python, conçu pour les cas où lancer un script Python est excessif — pipelines shell, règles Make, étapes CI et conversions ponctuelles.

## Prerequisites

Le CLI est fourni avec le package, aucune installation supplémentaire n'est donc nécessaire. Assurez‑vous que `groupdocs-conversion-net` est installé (voir le [Quick Start Guide]()), puis vérifiez que le script console est disponible :

```bash
groupdocs-conversion --version
```

Vous devriez voir la version du package affichée, par exemple `groupdocs-conversion 26.9.0`.

Si la commande `groupdocs-conversion` n'est pas trouvée, le répertoire des scripts du package n'est peut‑être pas dans votre `PATH`. Vous pouvez toujours invoquer le CLI via le module Python : `python -m groupdocs.conversion`. Les deux sont équivalents.

## Commands

Le CLI expose quatre sous‑commandes. Exécutez `groupdocs-conversion --help` pour la liste complète des options, ou `groupdocs-conversion <command> --help` pour une sous‑commande spécifique.

### convert

Convertissez un document vers un autre format. Le format cible est déduit de l'extension du fichier de sortie ; passez `--format` pour le remplacer.

```bash
# L'extension détermine le format cible
groupdocs-conversion convert business-plan.docx business-plan.pdf

# Remplacez le format lorsque le nom de sortie ne possède pas d'extension utilisable
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# Convertissez une seule page (indexée à 1) — utile pour les cibles raster
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# Ouvrir une source protégée par mot de passe
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| Option | Description |
| :- | :- |
| `--format` | Jeton de format cible (remplace l'extension de sortie). |
| `--password` | Mot de passe pour un document source protégé. |
| `--page` | Première page à convertir, indexée à 1. |
| `--count` | Nombre de pages à convertir. |

En cas de succès, la commande affiche le chemin de sortie et se termine avec le code `0`.

### info

Affiche les informations de base sur un document — format, taille, nombre de pages et date de création lorsqu'elles sont disponibles.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

Utilisez `--password` pour les sources protégées.

### list-formats

Liste chaque format cible que le moteur peut produire pour un document d'entrée donné, séparés en cibles principales et secondaires.

```bash
groupdocs-conversion list-formats business-plan.docx
```

Utilisez `--password` pour les sources protégées.

### list-all-formats

Affiche la matrice complète de conversion source-vers-cible connue du moteur — chaque format d'entrée et les cibles vers lesquelles il peut être converti.

```bash
groupdocs-conversion list-all-formats
```

Cette commande ne prend aucun fichier d'entrée.

## Global options

Ces options s'appliquent à chaque commande :

| Option | Description |
| :- | :- |
| `--license PATH` | Appliquez un fichier de licence avant d'exécuter la commande. |
| `--version` | Affiche la version du CLI et quitte. |
| `--help` | Affiche l'aide d'utilisation et quitte. |

Appliquez une licence dès le départ en plaçant `--license` avant la sous-commande :

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

Le CLI respecte également la variable d'environnement `GROUPDOCS_LIC_PATH` — si elle est définie, la licence est appliquée automatiquement et vous pouvez omettre `--license`. Voir le sujet [Licensing]() pour plus de détails.

## Format tokens

`convert` associe l'extension de sortie — ou la valeur `--format`, en minuscules — aux options de conversion correspondantes et au type de fichier. Les jetons pris en charge sont :

| Catégorie | Jetons |
| :- | :- |
| PDF | `pdf` |
| Traitement de texte | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| Feuille de calcul | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| Présentation | `ppt`, `pptx`, `pptm`, `odp` |
| Web | `html`, `htm`, `mhtml` |
| Image | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| eBook | `epub`, `mobi`, `azw3` |

Un jeton inconnu provoque la sortie de la commande avec le code `2` et affiche la liste des jetons acceptés.

## Exit codes

| Code | Signification |
| :- | :- |
| `0` | Succès. |
| `2` | Erreur utilisateur — jeton de format inconnu ou fichier d'entrée manquant. |
| `1` | Erreur d'exécution — le message d'exception .NET sous-jacent est affiché sur la sortie d'erreur standard. |

Ces codes facilitent le branchement du CLI dans les scripts shell et les pipelines CI.

## When to use the Python API instead

Le CLI couvre les cas courants de conversion d'un seul document. Pour tout ce qui dépasse cela — rappels par page, flux en mémoire, filigrane, police ou options de plage de cellules, et hiérarchies de conteneurs multi-documents — utilisez directement l'API Python. Elle offre une surface plus riche que les options du CLI. Consultez le [Developer Guide]() pour l'ensemble complet des fonctionnalités.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
