---
title: FontFileType
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Définit les documents de police Inclut les types suivants  Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 En savoir plus sur les formats de policeicihttps//docs.fileformat.com/font/ .
type: docs
weight: 950
url: /fr/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Définit les documents de police Inclut les types suivants : [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) En savoir plus sur les formats de police[ici](https://docs.fileformat.com/font/) .

```csharp
public sealed class FontFileType : FileType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [FontFileType](fontfiletype)() | Constructeur de sérialisation |

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
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Détermine si deux instances d'objet sont égales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sert de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Un fichier avec l'extension .cff est un format de police compact et est également connu sous le nom de PostScript Type 1 ou CIDFont. CFF agit comme un conteneur pour stocker plusieurs polices ensemble dans une seule unité appelée FontSet. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/font/cff/) . |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Un fichier avec l'extension .eot est une police OpenType intégrée dans un document. Ceux-ci sont principalement utilisés dans les fichiers Web tels qu'une page Web. Il a été créé par Microsoft et est pris en charge par les produits Microsoft, y compris le fichier .pps de présentation PowerPoint. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/font/eot/) . |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Un fichier avec l'extension .otf fait référence au format de police OpenType. Le format de police OTF est plus évolutif et étend les fonctionnalités existantes des formats TTF pour la typographie numérique. Développé par Microsoft et Adobe, OTF combine les fonctionnalités des formats de police PostScript et TrueType. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/font/otf/) . |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Un fichier avec l'extension .ttf représente des fichiers de police basés sur la technologie de police des spécifications TrueType. Il a été initialement conçu et lancé par Apple Computer, Inc pour Mac OS et a ensuite été adopté par Microsoft pour Windows OS. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/font/ttf/) . |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Les polices de type 1 sont une technologie Adobe obsolète qui était largement utilisée dans les logiciels de publication assistée par ordinateur et les imprimantes pouvant utiliser PostScript. Bien que les polices de type 1 ne soient pas prises en charge sur de nombreuses plates-formes, navigateurs Web et systèmes d'exploitation mobiles modernes, elles sont toujours prises en charge sur certains systèmes d'exploitation. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/font/type1/) . |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Un fichier avec l'extension .woff est un fichier de polices Web basé sur le Web Open Font Format (WOFF). Il a un conteneur compressé spécifique au format basé sur les types de police TrueType (.TTF) ou OpenType (.OTT). En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/font/woff/) . |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Un fichier avec l'extension .woff est un fichier de polices Web basé sur le Web Open Font Format (WOFF). Il a un conteneur compressé spécifique au format basé sur les types de police TrueType (.TTF) ou OpenType (.OTT). En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/font/woff/) . |

### Voir également

* class [FileType](../filetype)
* espace de noms [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
