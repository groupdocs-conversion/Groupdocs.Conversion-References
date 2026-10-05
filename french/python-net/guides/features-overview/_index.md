---
title: "Aperçu des fonctionnalités"
linkTitle: "Features overview"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Principales fonctionnalités de GroupDocs.Conversion pour Python via .NET — plus de 10 000 paires de formats, sélection de pages, options de chargement/conversion, filigranes, inspection de documents et intégration de pipeline IA."
type: docs
url: /fr/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion pour Python via .NET convertit des documents entre **10,000+ format pairs** — Microsoft Office, PDF, OpenDocument, images, CAD, courriel, archives, eBooks, HTML, TeX et langages de description de pages. Il fonctionne entièrement en local, ne nécessite aucune installation de Microsoft Office ou d'Adobe Acrobat, et est fourni sous forme de roue pré‑compilée pour Windows, Linux et macOS.

Voir la liste complète des [formats pris en charge]() ou parcourir le [Guide du développeur]() pour des exemples exécutables de chaque surface d'API.

## File Conversion

La capacité principale consiste à convertir tout document source pris en charge en tout format cible pris en charge. Toutes les conversions sont possibles sans Microsoft Office, LibreOffice ou Adobe Acrobat installés. GroupDocs.Conversion offre un ensemble flexible d'options pour personnaliser le pipeline.

### Convert specific document pages

Convertissez des documents entiers, des pages individuelles ou des plages de pages. Utilisez soit une liste explicite `pages`, soit une plage `page_number` + `pages_count` sur la classe [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Voir [Convertir un document vers un autre format]() pour des exemples exécutables.

### Per-page file output

Générez un fichier de sortie par page — utile pour les présentations, les PDF multipages et le rendu de documents en images. Parcourez l'attribut `page_number` tout en maintenant `pages_count = 1`. Voir [Convertir un document en plusieurs fichiers de pages]().

### Auto-detect source document format

Lorsqu'un fichier source arrive sous forme de flux d'octets sans nom de fichier, GroupDocs.Conversion détecte automatiquement le format en inspectant l'en-tête du flux. Voir [Charger un fichier depuis un flux](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Chaque classe d'options de chargement expose des paramètres spécifiques au format :

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Interrogez le moteur pour connaître les formats cibles pris en charge avant d'exécuter un pipeline — au niveau de toute la bibliothèque, par extension, ou pour un document chargé spécifique. Voir [Obtenir les conversions possibles]() pour les trois surcharges.

### Watermark the converted document

Ajoutez un filigrane texte lors de la conversion — contrôlez la couleur, la taille, la rotation, la transparence et le placement en arrière‑plan / premier plan. Voir [Ajouter un filigrane au document converti]().

### Convert files inside a container

Ouvrez les conteneurs ZIP, RAR, 7Z, OST ou PST, convertissez le contenu et écrivez un document de sortie consolidé en un seul appel. Voir [Convertir les fichiers au sein des conteneurs de documents]().

## Document Information Extraction

GroupDocs.Conversion peut lire les métadonnées d'un document source sans le convertir réellement — format, nombre de pages ou de diapositives, auteur, date de création, dimensions, table des matières et détails spécifiques au format. Voir [Obtenir les informations du document]() pour les neuf variantes :

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Le constructeur Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) accepte à la fois un chemin de fichier et un objet binaire de type fichier, vous permettant de charger des documents depuis :

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

Le stockage cloud (Amazon S3, Azure Blob Storage, Google Cloud Storage) fonctionne en récupérant les octets dans un tampon `BytesIO` et en le transmettant au constructeur du [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

## Logging and Diagnostics

Connectez un [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) via [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) pour tracer le pipeline de conversion — sélection du chargeur, démarrage et achèvement de la conversion, ainsi que les éventuels avertissements émis par le moteur. Voir [Logging and Diagnostics]().

## AI and LLM Integration

GroupDocs.Conversion est conçu pour être un composant de premier ordre des pipelines de documents IA. Le paquet pip `groupdocs-conversion-net` inclut un fichier `AGENTS.md` dans la roue afin que les assistants de codage IA puissent découvrir automatiquement la surface de l’API, et GroupDocs exploite un [MCP server](https://docs.groupdocs.com/mcp) public pour les recherches de documentation à la demande. Voir [Agents and LLM Integration]() pour l’histoire complète — y compris comment chaîner GroupDocs.Conversion avec GroupDocs.Markdown pour une entrée RAG propre.

## On-Premise Deployment

Aucun appel cloud, aucun trafic réseau sortant, aucune dépendance logicielle tierce au‑delà de ce que le système d’exploitation fournit déjà. La roue est autonome sous Windows et fournit ses propres bibliothèques d’exécution natives sous Linux et macOS. Voir [System Requirements]() pour la courte liste des paquets natifs optionnels (ICU, fontconfig, polices de base Microsoft).
