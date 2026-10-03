---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents WordProcessing."
type: docs
weight: 2950
url: /fr/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Options de chargement des documents WordProcessing.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Initialise une nouvelle instance de la classe [`WordProcessingLoadOptions`](../wordprocessingloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | Lorsque vrai (par défaut), les paragraphes et les runs dont le texte est majoritairement de droite à gauche verront leurs indicateurs bidi réparés avant la conversion. Cela correspond à l'heuristique appliquée par Microsoft Word et LibreOffice et corrige le rendu des documents arabes/hébreux générés par des générateurs (notamment Google Docs) qui produisent du OOXML sans &lt;w:bidi/&gt; et avec &lt;w:rtl w:val=\"0\"/&gt; sur les runs contenant uniquement du script RTL. Réglez sur false pour préserver une interprétation stricte du OOXML du balisage source. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Options des signets |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | Supprime les propriétés de métadonnées intégrées du document. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | Supprime les propriétés de métadonnées personnalisées du document. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | Spécifie comment les commentaires doivent être affichés dans le document de sortie. La valeur par défaut est ShowInBalloons. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | Implémente [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Valeur par défaut : false |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | Implémente [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Valeur par défaut : true |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Définit la police par défaut pour un document WordProcessing. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | Implémente [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Valeur par défaut : 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | Si EmbedTrueTypeFonts est true, GroupDocs.Conversion intègre les polices TrueType dans le document de sortie. Valeur par défaut : true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | Remplace automatiquement les polices manquantes en fonction de FontConfig dans le système. Valeur par défaut : false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | Remplace automatiquement les polices manquantes en fonction de FontInfo dans le document. Valeur par défaut : false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | Remplace automatiquement les polices manquantes en fonction du nom de la police. Valeur par défaut : false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Remplace des polices spécifiques lors de la conversion d'un document WordsProcessing. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | Transforme les polices existantes après le chargement du document et la substitution des polices. Les transformations de polices peuvent modifier toutes les polices du document, y compris celles qui ont été chargées avec succès. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Masque le balisage et le suivi des modifications pour les documents Word. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | Définit les options de césure pour les documents WordProcessing. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Conserve la valeur originale du champ date. Valeur par défaut : false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | Paramètres des marges de page |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | Active ou désactive la génération de la numérotation des pages dans le document converti. Valeur par défaut : false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Définit le mot de passe pour déprotéger le document protégé. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | Détermine si la structure du document doit être préservée lors de la conversion en PDF (par défaut, false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Spécifie s'il faut conserver les champs de formulaire Microsoft Word en tant que champs de formulaire dans le PDF ou les convertir en texte. Par défaut, false. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | Affiche le nom complet du commentateur dans les commentaires. Par défaut, false. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | Paramètres de taille de page |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | Implémente [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Met à jour les champs après le chargement. Valeur par défaut : false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Met à jour la mise en page après le chargement. Valeur par défaut : false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Spécifie s'il faut utiliser un formateur de texte pour un meilleur affichage du crénage. Par défaut, false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | Implémente [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Remarques

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• Gère les polices manquantes ou indisponibles en utilisant FontSubstitutes, DefaultFont et la substitution système

• Ordre de traitement : FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• Modifie toutes les polices existantes dans le document chargé en utilisant FontReplacements

• Appliqué après que toutes les substitutions de polices sont terminées

### Voir aussi

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
