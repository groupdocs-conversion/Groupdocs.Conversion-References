---
title: "FinanceFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les documents financiers Inclut les types suivants Xbrl./financefiletype/xbrlIXbrl./financefiletype/ixbrlOfx./financefiletype/ofx En savoir plus sur les formats financiers icihttps//docs.fileformat.com/finance/."
type: docs
weight: 1140
url: /fr/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

Définit les documents financiers Inclut les types suivants : [`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx) En savoir plus sur les formats financiers [ici](https://docs.fileformat.com/finance/).

```csharp
public sealed class FinanceFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FinanceFileType](financefiletype)() | Constructeur de sérialisation |

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension du fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implémente [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Servir de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | Dans iXBRL, le contenu de XBRL est encapsulé dans le format de fichier xHTML qui utilise des balises XML. Comme XBRL, il est l'élément racine des fichiers iXBRL. Le format XHTML représente son contenu comme une collection de différents types de documents et modules. Tous les fichiers en XHTML sont basés sur le format de fichier XML et conformes aux normes de documents XML. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/finance/ixbrl/). |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | Open Financial Exchange (OFX) est un format de flux de données pour l'échange d'informations financières qui a évolué à partir du Open Financial Connectivity (OFC) de Microsoft et des formats de fichiers Open Exchange d'Intuit. En savoir plus sur ce format de fichier [ici](https://en.wikipedia.org/wiki/Open_Financial_Exchange). |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL est une norme internationale ouverte pour le reporting d'entreprise numérique largement utilisée dans le monde. C'est un langage basé sur XML qui utilise des éléments XBRL, appelés balises, pour décrire chaque élément de données commerciales afin de formuler des données pour le tri et l'analyse des rapports. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/finance/xbrl/). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
