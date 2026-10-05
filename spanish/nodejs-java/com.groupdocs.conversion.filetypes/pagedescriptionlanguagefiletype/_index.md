---
title: "PageDescriptionLanguageFileType"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Define documentos de descripción de página."
type: docs
weight: 20
url: /es/nodejs-java/com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PageDescriptionLanguageFileType extends FileType implements Serializable
```

Define documentos de descripción de página. Incluye los siguientes tipos: [Svg](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Svg), [Eps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Eps), [Cgm](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Cgm), [Xps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Xps), [Tex](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Tex), [Ps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Ps), [Pcl](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Pcl), [Oxps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Oxps),
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PageDescriptionLanguageFileType()](#PageDescriptionLanguageFileType--) | Constructor de serialización |
## Campos

| Campo | Descripción |
| --- | --- |
| [Svg](#Svg) | Un archivo SVG es un archivo de Gráficos Vectoriales Escalares que utiliza un formato de texto basado en XML para describir la apariencia de una imagen. |
| [Eps](#Eps) | Los archivos con extensión EPS describen esencialmente un programa en lenguaje Encapsulated PostScript que describe la apariencia de una sola página. |
| [Cgm](#Cgm) | Computer Graphics Metafile (CGM) es un formato de metarchivo gratuito, independiente de la plataforma, estándar internacional para almacenar e intercambiar gráficos vectoriales (2D), gráficos rasterizados y texto. |
| [Xps](#Xps) | Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications creados por Microsoft. |
| [Tex](#Tex) | TeX es un lenguaje que comprende características de programación y de marcado, utilizado para componer documentos. |
| [Ps](#Ps) | PostScript (PS) es un lenguaje de descripción de página de propósito general utilizado en el ámbito de la publicación de escritorio y electrónica. |
| [Pcl](#Pcl) | PCL significa Printer Command Language, que es un lenguaje de descripción de página introducido por Hewlett Packard (HP). |
| [Oxps](#Oxps) | El formato de archivo OXPS se conoce como Open XML Paper Specification. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PageDescriptionLanguageFileType() {#PageDescriptionLanguageFileType--}
```
public PageDescriptionLanguageFileType()
```


Constructor de serialización

### Svg {#Svg}
```
public static final PageDescriptionLanguageFileType Svg
```


Un archivo SVG es un archivo de Gráficos Vectoriales Escalares que utiliza un formato de texto basado en XML para describir la apariencia de una imagen. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### Eps {#Eps}
```
public static final PageDescriptionLanguageFileType Eps
```


Los archivos con extensión EPS describen esencialmente un programa en lenguaje Encapsulated PostScript que describe la apariencia de una sola página. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### Cgm {#Cgm}
```
public static final PageDescriptionLanguageFileType Cgm
```


Computer Graphics Metafile (CGM) es un formato de metarchivo gratuito, independiente de la plataforma, estándar internacional para almacenar e intercambiar gráficos vectoriales (2D), gráficos rasterizados y texto. CGM utiliza un enfoque orientado a objetos y muchas funciones para la producción de imágenes. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### Xps {#Xps}
```
public static final PageDescriptionLanguageFileType Xps
```


Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications creados por Microsoft. Este formato fue desarrollado por Microsoft como reemplazo del formato de archivo EMF y es similar al formato de archivo PDF, pero utiliza XML en el diseño, la apariencia y la información de impresión de un documento. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### Tex {#Tex}
```
public static final PageDescriptionLanguageFileType Tex
```


TeX es un lenguaje que comprende características de programación y de marcado, utilizado para componer documentos. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### Ps {#Ps}
```
public static final PageDescriptionLanguageFileType Ps
```


PostScript (PS) es un lenguaje de descripción de página de propósito general utilizado en el ámbito de la publicación de escritorio y electrónica. El objetivo principal de PostScript (PS) es facilitar el diseño gráfico bidimensional. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### Pcl {#Pcl}
```
public static final PageDescriptionLanguageFileType Pcl
```


PCL significa Printer Command Language, que es un lenguaje de descripción de página introducido por Hewlett Packard (HP). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### Oxps {#Oxps}
```
public static final PageDescriptionLanguageFileType Oxps
```


El formato de archivo OXPS se conoce como Open XML Paper Specification. Es un lenguaje de descripción de página y formato de documento. Microsoft es el desarrollador de este formato. El formato de archivo OXPS es muy similar a los archivos PDF. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/page-description-language/oxps

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
