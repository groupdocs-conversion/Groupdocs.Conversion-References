---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents XML."
type: docs
weight: 2960
url: /fr/net/groupdocs.conversion.options.load/xmlloadoptions/
---
## XmlLoadOptions class

Options de chargement des documents XML.

```csharp
public sealed class XmlLoadOptions : WebLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions)() | Initialise une nouvelle instance de la classe [`XmlLoadOptions`](../xmlloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | Le chemin/base URL pour le html |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | Action pour la configuration des en-têtes de la requête. Le premier paramètre de l'action est l'Uri. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Fournisseur d'identifiants pour l'Uri. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | Implémente [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Obtient ou définit l'encodage à utiliser lors du chargement du document web. Si la propriété est null, l'encodage sera déterminé à partir de l'attribut de jeu de caractères du document. |
| [Format](../../groupdocs.conversion.options.load/xmlloadoptions/format) { get; } | Type de fichier du document d'entrée. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | Contrôle la façon dont le contenu HTML est rendu. Valeur par défaut : AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Paramètres des marges de page |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Paramètres d'orientation de page |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Spécifie les options de mise en page lors du chargement des documents web. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Active ou désactive la génération de la numérotation des pages dans le document converti. Valeur par défaut : false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Délai d'attente pour le chargement des ressources externes |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Paramètres de taille de page |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Implémente [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UseAsDataSource](../../groupdocs.conversion.options.load/xmlloadoptions/useasdatasource) { get; set; } | Utiliser le document Xml comme source de données |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Utiliser le pdf pour la conversion. Valeur par défaut : false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Implémente [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [XslFoFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xslfofactory) { get; set; } | Flux de document XSL-FO pour convertir XML à l'aide d'un fichier de balisage XSL-FO. |
| [XsltFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xsltfactory) { get; set; } | Flux de document XSLT pour convertir XML en effectuant une transformation XSL vers HTML. |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Spécifie le niveau de zoom en pourcentage. Le niveau de zoom est appliqué à la balise &lt;body&gt; du document avant la conversion, en redimensionnant l'apparence visuelle du document. Une valeur de 100% représente la taille originale. La valeur par défaut est 100. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [WebLoadOptions](../webloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
