---
title: "TypeDeFichier3D"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les documents 3D Inclut les types suivants Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb En savoir plus sur les formats 3D icihttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /fr/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Définit les documents 3D Inclut les types suivants : [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) En savoir plus sur les formats 3D [ici](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Constructeur de sérialisation |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Un fichier AMF consiste en des directives pour la description d'objets afin d'être utilisé par les processus de fabrication additive. Il contient une balise XML d'ouverture et se termine par un élément. Ceci est précédé d'une ligne de déclaration XML spécifiant la version XML et le codage du fichier. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Un fichier avec l'extension .ase est un format de fichier Autodesk ASCII Scene Export qui est une représentation ASCII d'une scène, contenant des informations 2D ou 3D lors de l'exportation des données de scène avec Autodesk. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Un fichier DAE est un format de fichier Digital Asset Exchange utilisé pour l'échange de données entre applications 3D interactives. Ce format de fichier est basé sur le schéma XML COLLADA (COLLAborative Design Activity) qui est un schéma XML standard ouvert pour l'échange d'actifs numériques entre les applications logicielles graphiques. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Un fichier avec l'extension .drc est un format de fichier 3D compressé créé avec la bibliothèque Google Draco. Google propose Draco comme bibliothèque open source pour compresser et décompresser des maillages géométriques 3D et des nuages de points, et améliore le stockage et la transmission des graphiques 3D. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, est un format de fichier 3D populaire qui a été initialement développé par Kaydara pour MotionBuilder. Il a été acquis par Autodesk Inc en 2006 et est maintenant l'un des principaux formats d'échange 3D utilisés par de nombreux outils 3D. FBX est disponible à la fois en format binaire et ASCII. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB est la représentation du format de fichier binaire des modèles 3D enregistrés au format GL Transmission Format (glTF). Ce format binaire stocke l'actif glTF (JSON, .bin et images) dans un blob binaire. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) est un format de fichier 3D qui stocke les informations de modèle 3D au format JSON. L'utilisation du JSON minimise à la fois la taille des actifs 3D et le traitement en temps réel nécessaire pour décompresser et utiliser ces actifs. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) est un format de données 3D efficace, axé sur l'industrie et flexible, normalisé ISO, développé par Siemens PLM Software. Les domaines de CAO mécanique de l'aérospatiale, de l'industrie automobile et des équipements lourds utilisent JT comme leur principal format de visualisation 3D. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | Un fichier avec l'extension .ma est un fichier de projet 3D créé avec l'application Autodesk Maya. Il contient une longue liste de commandes textuelles pour spécifier des informations sur le fichier. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | Un fichier avec l'extension .mb est un fichier projet binaire créé avec l'application Autodesk Maya. Contrairement au format de fichier MA, qui est au format ASCII, les fichiers MB sont stockés au format binaire. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | Les fichiers OBJ sont utilisés par l'application Advanced Visualizer de Wavefront pour définir et stocker les objets géométriques. La transmission en avant et en arrière des données géométriques est rendue possible grâce aux fichiers OBJ. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, représente un format de fichier 3D qui stocke des objets graphiques décrits comme une collection de polygones. Le but de ce format de fichier était de créer un type de fichier simple et facile, suffisamment général pour être utile à un large éventail de modèles. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | Les fichiers de données RVM sont liés à AVEVA PDMS. Le fichier RVM est un fichier de projet Modèle du système de gestion de conception d'usine AVEVA. Le système de gestion de conception d'usine (PDMS) d'AVEVA est le système de conception 3D le plus populaire, utilisant une technologie centrée sur les données pour gérer les projets. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Un fichier avec l'extension .3ds représente le format de fichier maillage 3D Sudio (DOS) utilisé par Autodesk 3D Studio. Autodesk 3D Studio est présent sur le marché des formats de fichiers 3D depuis les années 1990 et a maintenant évolué vers 3D Studio MAX pour le travail de modélisation, d'animation et de rendu 3D. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, est utilisé par les applications pour rendre des modèles d'objets 3D vers une variété d'autres applications, plateformes, services et imprimantes. Il a été créé pour éviter les limitations et problèmes des autres formats de fichiers 3D, comme STL, lors du travail avec les dernières versions d'imprimantes 3D. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) est un format de fichier compressé et une structure de données pour les graphiques informatiques 3D. Il contient des informations de modèle 3D telles que des maillages triangulaires, l'éclairage, l'ombrage, les données de mouvement, les lignes et les points avec couleur et structure. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Un fichier avec l'extension .usd est un format de fichier Universal Scene Description qui encode des données dans le but d'échanger et d'augmenter les données entre les applications de création de contenu numérique. Développé par Pixar, USD offre la possibilité d'échanger des actifs élémentaires (tels que des modèles) ou des animations. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Un fichier avec l'extension .usdz est une archive ZIP non compressée et non chiffrée pour le format de fichier USD (Universal Scene Description) qui contient et sert de proxy pour des fichiers d'autres formats (tels que des textures et des animations) intégrés dans l'archive et les exécute directement avec le runtime USD sans besoin de décompression. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Le Virtual Reality Modeling Language (VRML) est un format de fichier pour la représentation d'objets 3D interactifs sur le World Wide Web (www). Il est utilisé pour créer des représentations tridimensionnelles de scènes complexes telles que des illustrations, des définitions et des présentations de réalité virtuelle. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Un fichier avec l'extension .x fait référence au format de fichier hérité DirectX 3D Graphics qui a été introduit avec Microsoft DirectX 2.0. Il était utilisé pour le rendu graphique 3D dans les jeux et spécifie les structures pour les maillages, textures, animations et objets définis par l'utilisateur. Il est obsolète depuis 2014, le format de fichier Autodesk FBX étant plus adapté comme format moderne. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/3d/x). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
