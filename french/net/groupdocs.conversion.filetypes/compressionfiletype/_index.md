---
title: CompressionFileType
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Définit les formats de compression. Inclut les types de fichiers suivants  Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . En savoir plus sur les formats de compressionicihttps//docs.fileformat.com/compression/ .
type: docs
weight: 810
url: /fr/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Définit les formats de compression. Inclut les types de fichiers suivants : [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . En savoir plus sur les formats de compression[ici](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Constructeur de sérialisation |

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
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 sont des fichiers compressés générés à l'aide de la méthode de compression open source BZIP2, principalement sur le système UNIX ou Linux. Il est utilisé pour la compression d'un seul fichier et n'est pas destiné à l'archivage de plusieurs fichiers. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Un fichier avec une extension .cab appartient à un fichier cabinet Windows qui appartient à la catégorie des fichiers système. Il s'agit d'un fichier enregistré au format de fichier d'archive dans les versions de Microsoft Windows prenant en charge les algorithmes de données compressées, tels que LZX, Quantum et ZIP. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio est un utilitaire général d'archivage de fichiers et son format de fichier associé. Il est principalement installé sur les systèmes d'exploitation informatiques de type Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Un fichier GZ est une archive compressée créée à l'aide de l'algorithme de compression standard gzip (GNU zip). Il peut contenir plusieurs fichiers compressés, répertoires et stubs de fichiers. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Un fichier Gzip est une archive compressée créée à l'aide de l'algorithme de compression standard gzip (GNU zip). Il peut contenir plusieurs fichiers compressés, répertoires et stubs de fichiers. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Un fichier avec l'extension .lz est un fichier d'archive compressé créé avec Lzip, qui est un outil de ligne de commande gratuit pour la compression. Il prend en charge la concaténation pour compresser les fichiers de support. Les fichiers LZ ont un type de média application/lzip et prennent en charge des taux de compression plus élevés que BZ2. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Un fichier avec l'extension .lzma est un fichier d'archive compressé créé à l'aide de la méthode de compression LZMA (algorithme de chaîne de Lempel-Ziv-Markov). Ceux-ci sont principalement trouvés/utilisés sur le système d'exploitation Unix et sont similaires à d'autres algorithmes de compression tels que ZIP pour minimiser la taille des fichiers. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Les fichiers avec l'extension .rar sont des fichiers d'archive créés pour stocker des informations sous forme compressée ou normale. RAR, qui signifie Roshal ARchive file format. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z est un format d'archivage permettant de compresser des fichiers et des dossiers avec un taux de compression élevé. Il est basé sur une architecture Open Source qui permet d'utiliser n'importe quel algorithme de compression et de chiffrement. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Les fichiers avec l'extension .tar sont des archives créées avec un utilitaire basé sur Unix pour collecter un ou plusieurs fichiers. Plusieurs fichiers sont stockés dans un format non compressé avec la prise en charge de l'ajout de fichiers ainsi que de dossiers à l'archive. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ est un format de fichier compressé qui utilise l'algorithme de compression LZMA2. Il a été conçu pour remplacer les formats populaires gzip et bzip2 et offre un certain nombre d'avantages par rapport à ces anciennes normes. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Le fichier AZ est une catégorie de fichiers appartenant aux fichiers de données compressés UNIX. Les fichiers Unix compressés sont le type d'extension le plus populaire et le plus largement utilisé du fichier Z. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Un fichier avec l'extension .zip est une archive qui peut contenir un ou plusieurs fichiers ou répertoires. L'archive peut avoir une compression appliquée aux fichiers inclus afin de réduire la taille du fichier ZIP. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/compression/zip/) . |

### Voir également

* class [FileType](../filetype)
* espace de noms [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
