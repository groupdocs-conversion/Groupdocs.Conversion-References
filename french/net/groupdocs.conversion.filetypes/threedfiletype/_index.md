---
title: ThreeDFileType
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Définit les documents 3D Inclut les types suivants  Fbx./threedfiletype/fbx En savoir plus sur les formats 3Dicihttps//wiki.fileformat.com/3d .
type: docs
weight: 940
url: /fr/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Définit les documents 3D Inclut les types suivants : [`Fbx`](./fbx) En savoir plus sur les formats 3D[ici](https://wiki.fileformat.com/3d) .

```csharp
public sealed class ThreeDFileType : FileType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Constructeur de sérialisation |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Un fichier AMF est constitué de lignes directrices pour la description des objets afin d'être utilisés par les processus de fabrication additive. Il contient une balise XML d'ouverture et se termine par un élément. Elle est précédée d'une ligne de déclaration XML spécifiant la version XML et l'encodage du fichier. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Un fichier avec une extension .ase est un format de fichier Autodesk ASCII Scene Export qui est une représentation ASCII d'une scène, contenant des informations 2D ou 3D lors de l'exportation de données de scène à l'aide d'Autodesk. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Un fichier DAE est un format de fichier Digital Asset Exchange utilisé pour échanger des données entre des applications 3D interactives. Ce format de fichier est basé sur le schéma XML COLLADA (COLLAborative Design Activity) qui est un schéma XML standard ouvert pour l'échange d'actifs numériques entre les applications logicielles graphiques. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Un fichier avec l'extension .drc est un format de fichier 3D compressé créé avec la bibliothèque Google Draco. Google propose Draco en tant que bibliothèque open source pour compresser et décompresser les maillages géométriques 3D et les nuages de points, et améliore le stockage et la transmission des graphiques 3D. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, est un format de fichier 3D populaire développé à l'origine par Kaydara pour MotionBuilder. Il a été acquis par Autodesk Inc en 2006 et est aujourd'hui l'un des principaux formats d'échange 3D utilisé par de nombreux outils 3D. FBX est disponible au format de fichier binaire et ASCII. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) est un format de fichier 3D qui stocke les informations du modèle 3D au format JSON. L'utilisation de JSON minimise à la fois la taille des actifs 3D et le traitement d'exécution nécessaire pour décompresser et utiliser ces actifs. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) est un format de données 3D normalisé ISO efficace, flexible et axé sur l'industrie, développé par Siemens PLM Software. Les domaines de CAO mécanique de l'aérospatiale, de l'industrie automobile et de l'équipement lourd utilisent JT comme format de visualisation 3D le plus utilisé. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | Les fichiers OBJ sont utilisés par l'application Advanced Visualizer de Wavefront pour définir et stocker les objets géométriques. La transmission en amont et en aval des données géométriques est rendue possible grâce aux fichiers OBJ. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, représente un format de fichier 3D qui stocke des objets graphiques décrits comme une collection de polygones. Le but de ce format de fichier était d'établir un type de fichier simple et facile qui est suffisamment général pour être utile pour une large gamme de modèles. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | Les fichiers de données RVM sont liés à AVEVA PDMS. Le fichier RVM est un fichier de projet AVEVA Plant Design Management System Model. Le système de gestion de la conception d'usine (PDMS) d'AVEVA est le système de conception 3D le plus populaire utilisant une technologie centrée sur les données pour la gestion de projets. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Un fichier avec l'extension .3ds représente le format de fichier de maillage 3D Sudio (DOS) utilisé par Autodesk 3D Studio. Autodesk 3D Studio est présent sur le marché des formats de fichiers 3D depuis les années 1990 et a maintenant évolué vers 3D Studio MAX pour travailler avec la modélisation, l'animation et le rendu 3D. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, est utilisé par les applications pour restituer des modèles d'objets 3D à une variété d'autres applications, plates-formes, services et imprimantes. Il a été conçu pour éviter les limitations et les problèmes d'autres formats de fichiers 3D, comme STL, pour travailler avec les dernières versions d'imprimantes 3D. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) est un format de fichier compressé et une structure de données pour l'infographie 3D. Il contient des informations sur le modèle 3D telles que les maillages triangulaires, l'éclairage, l'ombrage, les données de mouvement, les lignes et les points avec couleur et structure. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Un fichier avec l'extension .usd est un format de fichier Universal Scene Description qui encode les données dans le but d'échanger et d'augmenter les données entre les applications de création de contenu numérique. Développé par Pixar, USD offre la possibilité d'échanger des actifs élémentaires (tels que des modèles) ou des animations. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Un fichier avec .usdz est une archive ZIP non compressée et non cryptée pour le format de fichier USD (Universal Scene Description) qui contient et proxies pour les fichiers d'autres formats (tels que les textures et les animations) intégrés dans l'archive et les exécute directement avec le Exécution en USD sans avoir besoin de déballer. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Le langage de modélisation de la réalité virtuelle (VRML) est un format de fichier pour la représentation d'objets du monde 3D interactifs sur le World Wide Web (www). Il trouve son utilisation dans la création de représentations tridimensionnelles de scènes complexes telles que des illustrations, des définitions et des présentations de réalité virtuelle. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Un fichier avec l'extension .x fait référence au format de fichier hérité DirectX 3D Graphics qui a été introduit avec Microsoft DirectX 2.0. Il a été utilisé pour le rendu graphique 3D dans les jeux et spécifie les structures des maillages, des textures, des animations et des objets définis par l'utilisateur. Il est obsolète depuis 2014 car le format de fichier Autodesk FBX sert mieux comme format plus moderne. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/3d/x) . |

### Voir également

* class [FileType](../filetype)
* espace de noms [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
