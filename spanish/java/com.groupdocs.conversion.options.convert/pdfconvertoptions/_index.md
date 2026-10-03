---
title: "PdfConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para la conversión a tipo de archivo Pdf."
type: docs
weight: 25
url: /es/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Opciones para la conversión a tipo de archivo Pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | Inicializa una nueva instancia de la clase [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getDpi()](#getDpi--) | DPI de página deseado después de la conversión. |
|
|  | [setDpi(int value)](#setDpi-int-) | DPI de página deseado después de la conversión. |
|
|  | [getPassword()](#getPassword--) | Establezca esta propiedad si desea proteger el documento convertido con una contraseña. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Establezca esta propiedad si desea proteger el documento convertido con una contraseña. |
|
|  | [getMarginTop()](#getMarginTop--) | Margen superior de página deseado en puntos después de la conversión. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Margen superior de página deseado en puntos después de la conversión. |
|
|  | [getMarginBottom()](#getMarginBottom--) | Margen inferior de página deseado en puntos después de la conversión. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Margen inferior de página deseado en puntos después de la conversión. |
|
|  | [getMarginLeft()](#getMarginLeft--) | Margen izquierdo de página deseado en puntos después de la conversión. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Margen izquierdo de página deseado en puntos después de la conversión. |
|
|  | [getMarginRight()](#getMarginRight--) | Margen derecho de página deseado en puntos después de la conversión. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Margen derecho de página deseado en puntos después de la conversión. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Opciones de conversión específicas de PDF |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Opciones de conversión específicas de PDF |
|
|  | [getRotate()](#getRotate--) | Rotación de página |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Rotación de página |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
### PdfConvertOptions() {#PdfConvertOptions--}
```
public PdfConvertOptions()
```


Inicializa una nueva instancia de la clase [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions).


### getDpi() {#getDpi--}
```
public final int getDpi()
```


DPI de página deseado después de la conversión. La resolución predeterminada es: 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


DPI de página deseado después de la conversión. La resolución predeterminada es: 96 dpi.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Establezca esta propiedad si desea proteger el documento convertido con una contraseña.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Establezca esta propiedad si desea proteger el documento convertido con una contraseña.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Margen superior de página deseado en puntos después de la conversión.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Margen superior de página deseado en puntos después de la conversión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Margen inferior de página deseado en puntos después de la conversión.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Margen inferior de página deseado en puntos después de la conversión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Margen izquierdo de página deseado en puntos después de la conversión.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Margen izquierdo de página deseado en puntos después de la conversión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Margen derecho de página deseado en puntos después de la conversión.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Margen derecho de página deseado en puntos después de la conversión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Opciones de conversión específicas de PDF


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Opciones de conversión específicas de PDF


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


Rotación de página


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


Rotación de página


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

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


Establece el tamaño de página deseado después de la conversión


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Ancho de página especificado en puntos si está configurado a PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Establece el ancho de página deseado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Altura de página especificada en puntos si está configurado a PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Establece la altura de página deseada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageHeight | float |  |

