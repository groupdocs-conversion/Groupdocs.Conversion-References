---
title: "FontFileType"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Define documentos de fuentes."
type: docs
weight: 17
url: /es/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Define documentos de fuentes.
Incluye los siguientes tipos:
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
Aprende más sobre los formatos de fuentes [aquí](../https://wiki.fileformat.com/font).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | Constructor de serialización |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Ttf](#Ttf) | Un archivo con extensión .ttf representa archivos de fuentes basados en la tecnología de fuentes de especificaciones TrueType. |
|
|  | [Eot](#Eot) | Un archivo con extensión .eot es una fuente OpenType que está incrustada en un documento. |
|
|  | [Otf](#Otf) | Un archivo con extensión .otf se refiere al formato de fuente OpenType. |
|
|  | [Cff](#Cff) | Un archivo con extensión .cff es un Compact Font Format y también se conoce como PostScript Type 1, o CIDFont. |
|
|  | [Type1](#Type1) | Las fuentes Type 1 son una tecnología de Adobe obsoleta que se utilizó ampliamente en el software de publicación de escritorio y en impresoras que podían usar PostScript. |
|
|  | [Woff](#Woff) | Un archivo con extensión .woff es una fuente web basada en el Web Open Font Format (WOFF). |
|
|  | [Woff2](#Woff2) | Un archivo con extensión .woff es una fuente web basada en el Web Open Font Format (WOFF). |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Constructor de serialización


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


Un archivo con extensión .ttf representa fuentes basadas en la tecnología de fuentes según las especificaciones TrueType. Fue diseñado e introducido inicialmente por Apple Computer, Inc para Mac OS y posteriormente adoptado por Microsoft para Windows OS. Obtén más información sobre este formato de archivo [aquí](../https://docs.fileformat.com/font/ttf/).


### Eot {#Eot}
```
public static final FontFileType Eot
```


Un archivo con extensión .eot es una fuente OpenType que está incrustada en un documento. Estas se utilizan principalmente en archivos web como una página web. Fue creado por Microsoft y es compatible con productos de Microsoft, incluido el archivo de presentación PowerPoint .pps. Obtén más información sobre este formato de archivo [aquí](../https://docs.fileformat.com/font/eot/).


### Otf {#Otf}
```
public static final FontFileType Otf
```


Un archivo con extensión .otf se refiere al formato de fuente OpenType. El formato de fuente OTF es más escalable y amplía las características existentes de los formatos TTF para la tipografía digital. Desarrollado por Microsoft y Adobe, OTF combina las características de los formatos de fuentes PostScript y TrueType. Obtén más información sobre este formato de archivo [aquí](../https://docs.fileformat.com/font/otf/).


### Cff {#Cff}
```
public static final FontFileType Cff
```


Un archivo con extensión .cff es un Compact Font Format y también se conoce como PostScript Type 1, o CIDFont. CFF actúa como un contenedor para almacenar múltiples fuentes juntas en una única unidad conocida como FontSet. Obtén más información sobre este formato de archivo [aquí](../https://docs.fileformat.com/font/cff/).


### Type1 {#Type1}
```
public static final FontFileType Type1
```


Las fuentes Type 1 son una tecnología de Adobe obsoleta que se utilizó ampliamente en el software de publicación de escritorio y en impresoras que podían usar PostScript. Aunque las fuentes Type 1 no son compatibles con muchas plataformas modernas, navegadores web y sistemas operativos móviles, todavía son compatibles en algunos sistemas operativos. Obtén más información sobre este formato de archivo [aquí](../https://docs.fileformat.com/font/type1/).


### Woff {#Woff}
```
public static final FontFileType Woff
```


Un archivo con extensión .woff es una fuente web basada en el Web Open Font Format (WOFF). Tiene un contenedor comprimido específico del formato basado en fuentes TrueType (.TTF) u OpenType (.OTT). Obtén más información sobre este formato de archivo [aquí](../https://docs.fileformat.com/font/woff/).


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


Un archivo con extensión .woff es una fuente web basada en el Web Open Font Format (WOFF). Tiene un contenedor comprimido específico del formato basado en fuentes TrueType (.TTF) u OpenType (.OTT). Obtén más información sobre este formato de archivo [aquí](../https://docs.fileformat.com/font/woff/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predeterminadas preparadas para el tipo de archivo de origen


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opciones de conversión predeterminadas preparadas para el tipo de archivo


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
