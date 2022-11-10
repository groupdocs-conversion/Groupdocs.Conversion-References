---
title: WordProcessingFileType
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Définit les fichiers de traitement de texte contenant des informations utilisateur au format texte brut ou texte enrichi. Un format de fichier texte brut contient du texte non formaté et aucun paramètre de police ou de page etc. ne peut être appliqué. En revanche un format de fichier texte riche permet des options de formatage telles que la définition du type de police des styles gras italique souligné etc. des marges de page des entêtes des puces et des numéros et plusieurs autres fonctionnalités de formatage. Inclut les types de fichiers suivants  Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi./wordprocessingfiletype/mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log./wordprocessingfiletype/log . En savoir plus sur les formats de traitement de texteicihttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 960
url: /fr/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Définit les fichiers de traitement de texte contenant des informations utilisateur au format texte brut ou texte enrichi. Un format de fichier texte brut contient du texte non formaté et aucun paramètre de police ou de page, etc. ne peut être appliqué. En revanche, un format de fichier texte riche permet des options de formatage telles que la définition du type de police, des styles (gras, italique, souligné, etc.), des marges de page, des en-têtes, des puces et des numéros, et plusieurs autres fonctionnalités de formatage. Inclut les types de fichiers suivants : [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`Mobi`](./mobi) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . [`Log`](./log) . En savoir plus sur les formats de traitement de texte[ici](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Constructeur de sérialisation |

## Propriétés

| Nom | La description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension de fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |

## Méthodes

| Nom | La description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Détermine si deux instances d'objet sont égales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sert de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Azw3](../../groupdocs.conversion.filetypes/wordprocessingfiletype/azw3) | AZW3, également connu sous le nom de Kindle Format 8 (KF8), est la version modifiée du format de fichier numérique AZW ebook développé pour les appareils Amazon Kindle. Le format est une amélioration des anciens fichiers AZW et est utilisé sur les appareils Kindle Fire uniquement avec une rétrocompatibilité pour le format de fichier ancêtre, c'est-à-dire MOBI et AZW. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/ebook/azw3/) . |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Les fichiers avec l'extension .doc représentent des documents générés par Microsoft Word ou d'autres documents de traitement de texte au format de fichier binaire. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | Les fichiers DOCM sont des documents générés par Microsoft Word 2007 ou version ultérieure avec la possibilité d'exécuter des macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX est un format bien connu pour les documents Microsoft Word. Introduit à partir de 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée de binaire simple à une combinaison de fichiers XML et binaires. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Les fichiers avec l'extension .DOT sont des fichiers modèles créés par Microsoft Word pour avoir des paramètres pré-formatés pour la génération d'autres fichiers DOC ou DOCX. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Un fichier avec l'extension DOTM représente un fichier modèle créé avec Microsoft Word 2007 ou supérieur. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Les fichiers avec l'extension DOTX sont des fichiers modèles créés par Microsoft Word pour avoir des paramètres pré-formatés pour la génération d'autres fichiers DOCX. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Log](../../groupdocs.conversion.filetypes/wordprocessingfiletype/log) | Un fichier avec l'extension .LOG représente un document texte contenant du texte brut sous forme de lignes. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Les fichiers texte créés avec les dialectes du langage Markdown sont enregistrés avec l'extension de fichier .MD ou .MARKDOWN. Les fichiers MD sont enregistrés au format texte brut qui utilise le langage Markdown qui comprend également des symboles de texte en ligne, définissant la manière dont un texte peut être formaté, comme les indentations, le formatage des tableaux, les polices et les en-têtes. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/wordprocessingfiletype/mobi) | Le format de fichier MOBI est l'un des formats de fichier ebook les plus largement utilisés. Le format est une amélioration de l'ancien format OEB (Open Ebook Format) et a été utilisé comme format propriétaire pour Mobipocket Reader. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/ebook/mobi) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | Les fichiers ODT sont des types de documents créés avec des applications de traitement de texte basées sur le format de fichier texte OpenDocument. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Les fichiers avec l'extension OTT représentent des modèles de documents générés par des applications conformes au format standard OpenDocument d'OASIS. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Introduit et documenté par Microsoft, le format RTF (Rich Text Format) représente une méthode de codage de texte et de graphiques formatés à utiliser dans les applications. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Sql](../../groupdocs.conversion.filetypes/wordprocessingfiletype/sql) | Un fichier avec l'extension .SQL représente un document texte contenant sql. |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Un fichier avec l'extension .TXT représente un document texte qui contient du texte brut sous forme de lignes. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/txt) . |

### Voir également

* class [FileType](../filetype)
* espace de noms [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
