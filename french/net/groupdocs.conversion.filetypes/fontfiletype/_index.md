---
title: "FontFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les documents de police Inclut les types suivants Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 En savoir plus sur les formats de police icihttps//docs.fileformat.com/font/."
type: docs
weight: 1150
url: /fr/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Définit les documents de police Inclut les types suivants : [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) En savoir plus sur les formats de police [ici](https://docs.fileformat.com/font/).

```csharp
public sealed class FontFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FontFileType](fontfiletype)() | Constructeur de sérialisation |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Un fichier avec l'extension .cff est un Compact Font Format et est également connu sous le nom de PostScript Type 1, ou CIDFont. CFF agit comme un conteneur pour stocker plusieurs polices ensemble dans une unité unique appelée FontSet. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Un fichier avec l'extension .eot est une police OpenType intégrée dans un document. Elles sont principalement utilisées dans les fichiers web tels qu'une page Web. Elle a été créée par Microsoft et est prise en charge par les produits Microsoft, y compris les présentations PowerPoint au format .pps. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Un fichier avec l'extension .otf fait référence au format de police OpenType. Le format de police OTF est plus évolutif et étend les fonctionnalités existantes des formats TTF pour la typographie numérique. Développé par Microsoft et Adobe, OTF combine les caractéristiques des formats de police PostScript et TrueType. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Un fichier avec l'extension .ttf représente des fichiers de police basés sur la technologie de police selon les spécifications TrueType. Il a été initialement conçu et lancé par Apple Computer, Inc pour Mac OS et a ensuite été adopté par Microsoft pour Windows OS. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Les polices Type 1 sont une technologie Adobe obsolète qui était largement utilisée dans les logiciels d'édition assistée par ordinateur et les imprimantes compatibles PostScript. Bien que les polices Type 1 ne soient pas prises en charge sur de nombreuses plateformes modernes, navigateurs web et systèmes d'exploitation mobiles, elles restent supportées sur certains systèmes d'exploitation. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Un fichier avec l'extension .woff est un fichier de police web basé sur le Web Open Font Format (WOFF). Il possède un conteneur compressé spécifique au format, basé soit sur TrueType (.TTF) soit sur OpenType (.OTT). En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Un fichier avec l'extension .woff est un fichier de police web basé sur le Web Open Font Format (WOFF). Il possède un conteneur compressé spécifique au format, basé soit sur TrueType (.TTF) soit sur OpenType (.OTT). En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/font/woff/). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
