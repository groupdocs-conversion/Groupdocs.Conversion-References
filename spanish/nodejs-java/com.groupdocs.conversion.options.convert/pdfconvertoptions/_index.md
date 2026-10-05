---
title: "PdfConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para la conversión al tipo de archivo Pdf."
type: docs
weight: 25
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Opciones para la conversión al tipo de archivo Pdf.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfConvertOptions()](#PdfConvertOptions--) | Inicializa una nueva instancia de la clase [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDpi()](#getDpi--) | DPI de página deseado después de la conversión. |
| [setDpi(int value)](#setDpi-int-) | DPI de página deseado después de la conversión. |
| [getPassword()](#getPassword--) | Establezca esta propiedad si desea proteger el documento convertido con una contraseña. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Establezca esta propiedad si desea proteger el documento convertido con una contraseña. |
| [getMarginTop()](#getMarginTop--) | Margen superior de página deseado en píxeles después de la conversión. |
| [setMarginTop(int value)](#setMarginTop-int-) | Margen superior de página deseado en píxeles después de la conversión. |
| [getMarginBottom()](#getMarginBottom--) | Margen inferior de página deseado en píxeles después de la conversión. |
| [setMarginBottom(int value)](#setMarginBottom-int-) | Margen inferior de página deseado en píxeles después de la conversión. |
| [getMarginLeft()](#getMarginLeft--) | Margen izquierdo de página deseado en píxeles después de la conversión. |
| [setMarginLeft(int value)](#setMarginLeft-int-) | Margen izquierdo de página deseado en píxeles después de la conversión. |
| [getMarginRight()](#getMarginRight--) | Margen derecho de página deseado en píxeles después de la conversión. |
| [setMarginRight(int value)](#setMarginRight-int-) | Margen derecho de página deseado en píxeles después de la conversión. |
| [getPdfOptions()](#getPdfOptions--) | Opciones de conversión específicas de Pdf |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Opciones de conversión específicas de Pdf |
| [getRotate()](#getRotate--) | Rotación de página |
| [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Rotación de página |
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
public final int getMarginTop()
```


Margen superior de página deseado en píxeles después de la conversión.

**Returns:**
int
### setMarginTop(int value) {#setMarginTop-int-}
```
public final void setMarginTop(int value)
```


Margen superior de página deseado en píxeles después de la conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMarginBottom() {#getMarginBottom--}
```
public final int getMarginBottom()
```


Margen inferior de página deseado en píxeles después de la conversión.

**Returns:**
int
### setMarginBottom(int value) {#setMarginBottom-int-}
```
public final void setMarginBottom(int value)
```


Margen inferior de página deseado en píxeles después de la conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMarginLeft() {#getMarginLeft--}
```
public final int getMarginLeft()
```


Margen izquierdo de página deseado en píxeles después de la conversión.

**Returns:**
int
### setMarginLeft(int value) {#setMarginLeft-int-}
```
public final void setMarginLeft(int value)
```


Margen izquierdo de página deseado en píxeles después de la conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMarginRight() {#getMarginRight--}
```
public final int getMarginRight()
```


Margen derecho de página deseado en píxeles después de la conversión.

**Returns:**
int
### setMarginRight(int value) {#setMarginRight-int-}
```
public final void setMarginRight(int value)
```


Margen derecho de página deseado en píxeles después de la conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Opciones de conversión específicas de Pdf

**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Opciones de conversión específicas de Pdf

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

