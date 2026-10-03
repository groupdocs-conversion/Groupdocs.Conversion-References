---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents Pdf."
type: docs
weight: 2740
url: /fr/net/groupdocs.conversion.options.load/pdfloadoptions/
---
## PdfLoadOptions class

Options de chargement des documents Pdf.

```csharp
public sealed class PdfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageNumberingLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfLoadOptions](pdfloadoptions)() | Initialise une nouvelle instance de la classe [`PdfLoadOptions`](../pdfloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearbuiltindocumentproperties) { get; set; } | Supprime les propriétés de métadonnées intégrées du document. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearcustomdocumentproperties) { get; set; } | Supprime les propriétés de métadonnées personnalisées du document. |
| [ConvertOwned](../../groupdocs.conversion.options.load/pdfloadoptions/convertowned) { get; set; } | Implémente [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Valeur par défaut : false |
| [ConvertOwner](../../groupdocs.conversion.options.load/pdfloadoptions/convertowner) { get; set; } | Implémente [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Valeur par défaut : true |
| [DefaultFont](../../groupdocs.conversion.options.load/pdfloadoptions/defaultfont) { get; set; } | Police par défaut pour le document Pdf. La police suivante sera utilisée si une police est manquante. |
| [Depth](../../groupdocs.conversion.options.load/pdfloadoptions/depth) { get; set; } | Implémente [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Valeur par défaut : 1 |
| [FlattenAllFields](../../groupdocs.conversion.options.load/pdfloadoptions/flattenallfields) { get; set; } | Aplatir tous les champs du formulaire PDF. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/pdfloadoptions/fontsubstitutes) { get; set; } | Substituer des polices spécifiques lors de la conversion du document Pdf. |
| [FontTransformations](../../groupdocs.conversion.options.load/pdfloadoptions/fonttransformations) { get; set; } | Transforme les polices existantes après le chargement du document et la substitution des polices. Les transformations de polices peuvent modifier toutes les polices du document, y compris celles qui ont été chargées avec succès. |
| [Format](../../groupdocs.conversion.options.load/pdfloadoptions/format) { get; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [HidePdfAnnotations](../../groupdocs.conversion.options.load/pdfloadoptions/hidepdfannotations) { get; set; } | Masquer les annotations dans les documents PDF. |
| [PageNumbering](../../groupdocs.conversion.options.load/pdfloadoptions/pagenumbering) { get; set; } | Active ou désactive la génération de la numérotation des pages dans le document converti. Valeur par défaut : false |
| [Password](../../groupdocs.conversion.options.load/pdfloadoptions/password) { get; set; } | Définit le mot de passe pour déprotéger le document protégé. |
| [RemoveEmbeddedFiles](../../groupdocs.conversion.options.load/pdfloadoptions/removeembeddedfiles) { get; set; } | Supprimer les fichiers intégrés. |
| [RemoveJavascript](../../groupdocs.conversion.options.load/pdfloadoptions/removejavascript) { get; set; } | Supprimer le javascript. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pdfloadoptions/resetfontfolders) { get; set; } | Réinitialise les dossiers de polices avant de charger le document |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
