---
title: "GmlLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents Gml."
type: docs
weight: 2550
url: /fr/net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

Options de chargement des documents Gml.

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | Initialise une nouvelle instance de la classe [`GmlLoadOptions`](../gmlloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | Type de fichier du document d'entrée. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Définit la hauteur de page souhaitée pour la conversion du document GIS. La valeur par défaut est 1000. |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | Détermine si la conversion est autorisée à charger le schéma XML depuis Internet. Si la valeur est false, les schémas avec des URI absolus qui ne commencent pas par ‘file://’ ne seront pas chargés. La valeur par défaut est false. |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | Détermine si la conversion est autorisée à analyser les attributs dans un fichier Gml dont le schéma XML est manquant ou ne peut pas être chargé. Si la valeur est true, le lecteur de conversion n’exige pas la présence d’un schéma XML. La valeur par défaut est false. |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | Liste d’URI séparées par des espaces. La première URI de chaque paire est l’URI de l’espace de noms, la seconde URI est le chemin vers le schéma XML de l’espace de noms. Si la valeur est null, la conversion tentera de lire schemaLocation à partir de l’élément racine du document. La valeur par défaut est null. |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Définit la largeur de page souhaitée pour la conversion du document GIS. La valeur par défaut est 1000. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
