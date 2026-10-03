---
title: "IPageSizeConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Representa las opciones de conversión que admiten tamaño de página"
type: docs
weight: 54
url: /es/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Representa las opciones de conversión que admiten tamaño de página

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Obtiene el tamaño de página deseado después de la conversión |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Establece el tamaño de página deseado después de la conversión |
|
|  | [getPageWidth()](#getPageWidth--) | Ancho de página especificado en puntos si está configurado a PageSize.Custom |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | Establece el ancho de página deseado |
|
|  | [getPageHeight()](#getPageHeight--) | Altura de página especificada en puntos si está configurado a PageSize.Custom |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | Establece la altura de página deseada |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Obtiene el tamaño de página deseado después de la conversión


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Establece el tamaño de página deseado después de la conversión


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Ancho de página especificado en puntos si está configurado a PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


Establece el ancho de página deseado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Altura de página especificada en puntos si está configurado a PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


Establece la altura de página deseada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageHeight | float |  |

