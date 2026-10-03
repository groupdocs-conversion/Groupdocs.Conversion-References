---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents Email."
type: docs
weight: 2500
url: /fr/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

Options de chargement des documents Email.

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Initialise une nouvelle instance de la classe [`EmailLoadOptions`](../emailloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | Obtient ou définit la liste des icônes de pièces jointes. La liste peut être personnalisée pour fournir des icônes spécifiques à différents types de fichiers. Par défaut, elle contient les icônes des types de fichiers courants. |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Implémente [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). La valeur par défaut est true |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Implémente [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Valeur par défaut : true |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | Implémente [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | Police par défaut pour le document e‑mail. La police suivante sera utilisée si une police est manquante. |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Implémente [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Valeur par défaut : 1 |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | Option d’afficher ou de masquer les pièces jointes dans l’en‑tête. Valeur par défaut : true. |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | Option d’afficher ou de masquer l’adresse e‑mail « Bcc ». Valeur par défaut : false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | Option d’afficher ou de masquer l’adresse e‑mail « Cc ». Valeur par défaut : false. |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | Option de contrôler si les adresses e‑mail sont affichées à côté des noms. Exemple : « John Doe &lt;john.doe@sample.com&gt; » ou simplement « John Doe. » Valeur par défaut : true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | Option d’afficher ou de masquer l’adresse e‑mail « from ». Valeur par défaut : true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | Option d’afficher ou de masquer l’en‑tête du e‑mail. Valeur par défaut : true. |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | Option d’afficher ou de masquer la date/heure d’envoi dans l’en‑tête. Valeur par défaut : true. |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | Option d’afficher ou de masquer l’objet dans l’en‑tête. Valeur par défaut : true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | Option d’afficher ou de masquer l’adresse e‑mail « to ». Valeur par défaut : true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | Le mappage entre le message e‑mail [`EmailField`](../emailfield) et la représentation textuelle du champ |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | Liste des polices de substitution. |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | Paramètres des marges de page |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | Paramètres d'orientation de page |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | Implémente [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions) |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Définit s’il faut conserver la chaîne d’en‑tête de date originale dans le message e‑mail lors de l’enregistrement ou non (la valeur par défaut est true) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Délai d'attente pour le chargement des ressources externes |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | Paramètres de taille de page |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | Implémente [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Obtient ou définit le décalage par rapport au Temps Universel Coordonné (UTC) pour les dates des messages. Cette propriété définit la différence de fuseau horaire entre l’heure locale et UTC. |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | Obtient ou définit s’il faut utiliser les icônes de pièces jointes par défaut. Valeur par défaut : true. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | Implémente [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Clone l'instance actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
