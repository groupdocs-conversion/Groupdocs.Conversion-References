---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les fichiers de traitement de texte qui contiennent des informations utilisateur en texte brut ou en format texte enrichi. Un format de fichier texte brut contient du texte non formaté et aucune police ou réglage de page, etc. ne peut être appliqué. En revanche, un format de texte enrichi permet des options de mise en forme telles que le réglage des polices, des styles, gras, italique, souligné, etc., les marges de page, les titres, les puces et les numéros ainsi que plusieurs autres fonctionnalités de mise en forme. Inclut les types de fichiers suivants Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. En savoir plus sur les formats de traitement de texte icihttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /fr/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Définit les fichiers de traitement de texte qui contiennent des informations utilisateur en texte brut ou au format texte enrichi. Un format de fichier texte brut contient du texte non formaté et aucun réglage de police ou de page, etc. ne peut être appliqué. En revanche, un format de texte enrichi permet des options de mise en forme telles que le réglage du type de police, les styles (gras, italique, souligné, etc.), les marges de page, les titres, les puces et les numéros, ainsi que plusieurs autres fonctionnalités de mise en forme. Inclut les types de fichiers suivants : [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). En savoir plus sur les formats de traitement de texte [ici](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Constructeur de sérialisation |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Les fichiers avec l'extension .doc représentent des documents générés par Microsoft Word ou d'autres traitements de texte au format binaire. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | Les fichiers DOCM sont des documents générés par Microsoft Word 2007 ou ultérieur avec la capacité d'exécuter des macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX est un format bien connu pour les documents Microsoft Word. Introduit en 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée du binaire brut à une combinaison de fichiers XML et binaires. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Les fichiers avec l'extension .DOT sont des modèles créés par Microsoft Word pour disposer de paramètres préformatés lors de la génération de futurs fichiers DOC ou DOCX. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Un fichier avec l'extension DOTM représente un modèle créé avec Microsoft Word 2007 ou ultérieur. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Les fichiers avec l'extension DOTX sont des modèles créés par Microsoft Word pour disposer de paramètres préformatés lors de la génération de futurs fichiers DOCX. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word est Office Open XML WordprocessingML stocké dans un fichier XML plat au lieu d'un package ZIP. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Les fichiers texte créés avec les dialectes du langage Markdown sont enregistrés avec l'extension .MD ou .MARKDOWN. Les fichiers MD sont enregistrés au format texte brut qui utilise le langage Markdown, lequel inclut également des symboles de texte en ligne, définissant comment un texte peut être formaté comme les retraits, la mise en forme de tableaux, les polices et les en-têtes. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | Les fichiers ODT sont un type de documents créés avec des applications de traitement de texte basées sur le format de fichier OpenDocument Text. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Les fichiers avec l'extension OTT représentent des documents modèles générés par des applications conformes au format standard OpenDocument de l'OASIS. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Introduit et documenté par Microsoft, le Rich Text Format (RTF) représente une méthode d'encodage du texte formaté et des graphiques pour une utilisation dans les applications. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Un fichier avec l'extension .TXT représente un document texte contenant du texte brut sous forme de lignes. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/txt). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
