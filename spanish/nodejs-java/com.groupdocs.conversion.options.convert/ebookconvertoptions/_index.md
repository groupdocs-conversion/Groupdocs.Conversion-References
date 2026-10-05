---
title: "EBookConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para conversión a tipo de archivo EBook."
type: docs
weight: 14
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/ebookconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class EBookConvertOptions extends CommonConvertOptions<EBookFileType> implements IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Opciones para conversión a tipo de archivo EBook.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EBookConvertOptions()](#EBookConvertOptions--) | Inicializa una nueva instancia de  clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
### EBookConvertOptions() {#EBookConvertOptions--}
```
public EBookConvertOptions()
```


Inicializa una nueva instancia de  clase.

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Obtiene el tamaño de página deseado después de la conversión

**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Establecer el tamaño de página deseado después de la conversión

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Ancho de página especificado en puntos si  está configurado a PageSize.Custom

**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Establecer el ancho de página deseado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Altura de página especificada en puntos si  está configurado a PageSize.Custom

**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Establecer la altura de página deseada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageHeight | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Obtiene la orientación de la página después de la conversión

**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Establece la orientación de página deseada después de la conversión

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

