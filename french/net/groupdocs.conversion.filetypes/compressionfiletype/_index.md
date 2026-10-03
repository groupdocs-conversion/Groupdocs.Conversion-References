---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les formats de compression. Inclut les types de fichiers suivants Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. En savoir plus sur les formats de compression icihttps//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /fr/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Définit les formats de compression. Inclut les types de fichiers suivants : [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). En savoir plus sur les formats de compression [ici](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension du fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Définit si le format prend en charge plusieurs fichiers/dossiers dans une seule archive. |

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
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | Un fichier avec l'extension .aar est une Apple Archive, le conteneur qu'Apple fournit avec macOS pour regrouper les fichiers et dossiers. Chaque entrée est compressée individuellement, le plus souvent avec LZFSE. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | Un fichier avec l'extension .alz est une archive ALZip, un format d'ESTsoft largement utilisé en Corée du Sud. Les entrées peuvent être chiffrées individuellement avec un mot de passe. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | Les fichiers BZ2 sont des fichiers compressés générés à l'aide de la méthode de compression open source BZIP2, principalement sur les systèmes UNIX ou Linux. Ils sont utilisés pour la compression d'un seul fichier et ne sont pas destinés à l'archivage de plusieurs fichiers. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Un fichier avec l'extension .cab appartient à un fichier cabinet Windows, qui fait partie de la catégorie des fichiers système. C'est un fichier enregistré au format d'archive dans les versions de Microsoft Windows qui supportent les algorithmes de données compressées, tels que LZX, Quantum et ZIP. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio est un utilitaire d'archivage de fichiers général et son format de fichier associé. Il est principalement installé sur les systèmes d'exploitation informatiques de type Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Un fichier GZ est une archive compressée créée à l'aide de l'algorithme de compression standard gzip (GNU zip). Il peut contenir plusieurs fichiers compressés, répertoires et fichiers factices. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Un fichier Gzip est une archive compressée créée à l'aide de l'algorithme de compression standard gzip (GNU zip). Il peut contenir plusieurs fichiers compressés, répertoires et fichiers factices. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | Un fichier avec l'extension .iso est un fichier image disque d'archive non compressé qui représente le contenu complet des données sur un disque optique tel qu'un CD ou un DVD. Basé sur la norme ISO-9660, le format de fichier image ISO contient les données du disque ainsi que les informations du système de fichiers qui y sont stockées. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | Un fichier avec l'extension .lzh et .lha correspond généralement à un format de compression d'archive. Ce format de fichier est similaire à d'autres formats de compression comme ZIP, RAR, etc. Le principal objectif de ces formats de fichier est de réduire la taille du fichier pour faciliter l'envoi ainsi que de les regrouper sous forme compressée. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Un fichier avec l'extension .lz est un fichier d'archive compressé créé avec Lzip, qui est un outil gratuit en ligne de commande pour la compression. Il prend en charge la concaténation pour compresser des fichiers de support. Les fichiers LZ ont le type MIME application/lzip et offrent un taux de compression supérieur à celui de BZ2. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | Un fichier avec l'extension .lz4 est un fichier d'archive compressé créé avec des applications/utilitaires qui prennent en charge la compression LZ4. L'algorithme LZ4 met l'accent sur le compromis entre vitesse et taux de compression. Les archives LZ4 compressées peuvent être créées à l'aide de l'utilitaire en ligne de commande LZ4 et décompressées avec le même outil. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Un fichier avec l'extension .lzma est un fichier d'archive compressé créé en utilisant la méthode de compression LZMA (Lempel‑Ziv‑Markov chain Algorithm). Ceux‑ci se trouvent principalement/ sont utilisés sur les systèmes d'exploitation Unix et sont similaires à d'autres algorithmes de compression tels que ZIP pour réduire la taille des fichiers. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Les fichiers avec l'extension .rar sont des fichiers d'archive créés pour stocker des informations sous forme compressée ou normale. RAR, qui signifie Roshal ARchive, est un format de fichier d'archive. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z est un format d'archivage pour compresser des fichiers et dossiers avec un taux de compression élevé. Il repose sur une architecture Open Source qui permet d'utiliser n'importe quel algorithme de compression et de chiffrement. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Les fichiers avec l'extension .tar sont des archives créées avec un utilitaire basé sur Unix pour rassembler un ou plusieurs fichiers. Plusieurs fichiers sont stockés dans un format non compressé avec la possibilité d'ajouter des fichiers ainsi que des dossiers à l'archive. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | Une archive uuencodée est un fichier ou une collection de fichiers qui ont été encodés à l'aide du schéma d'encodage Unix‑to‑Unix (uuencode). Cette méthode d'encodage convertit les données binaires en un format texte, ce qui facilite l'envoi de fichiers sur des canaux qui ne supportent que du texte, comme le courrier électronique. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | Un fichier avec l'extension .wim est une archive Windows Imaging Format, une image disque basée sur des fichiers que Microsoft utilise pour déployer Windows. Une archive unique contient une ou plusieurs images et stocke chaque fichier une seule fois, quel que soit le nombre d'images qui y font référence. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | Un fichier avec l'extension .xar est un eXtensible ARchive, un format construit autour d'une table des matières stockée sous forme XML compressé. Il est utilisé pour distribuer les paquets d'installation macOS et conserve chaque entrée compressée séparément. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ est un format de fichier compressé qui utilise l'algorithme de compression LZMA2. Il a été conçu comme un remplacement des formats populaires gzip et bzip2, et offre un certain nombre d'avantages par rapport à ces normes plus anciennes. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Un fichier Z est une catégorie de fichiers appartenant aux fichiers de données compressées UNIX. Les fichiers Unix compressés sont le type d'extension le plus populaire et le plus largement utilisé du fichier Z. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Un fichier avec l'extension .zip est une archive qui peut contenir un ou plusieurs fichiers ou répertoires. L'archive peut appliquer une compression aux fichiers inclus afin de réduire la taille du fichier ZIP. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | Un fichier ZST est un fichier compressé généré avec l'algorithme de compression Zstandard (zstd). C'est un fichier compressé créé avec une compression sans perte par cet algorithme. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/compression/zst/). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
