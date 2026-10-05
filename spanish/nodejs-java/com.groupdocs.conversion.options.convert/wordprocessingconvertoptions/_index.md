---
title: "WordProcessingConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para la conversión al tipo de archivo WordProcessing."
type: docs
weight: 48
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

Opciones para la conversión al tipo de archivo WordProcessing.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Inicializa una nueva instancia de la clase [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDpi()](#getDpi--) | DPI de página deseado después de la conversión. |
| [setDpi(int value)](#setDpi-int-) | DPI de página deseado después de la conversión. |
| [getPassword()](#getPassword--) | Establezca esta propiedad si desea proteger el documento convertido con una contraseña. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Establezca esta propiedad si desea proteger el documento convertido con una contraseña. |
| [getRtfOptions()](#getRtfOptions--) | Opciones de conversión específicas de RTF |
| [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | Opciones de conversión específicas de RTF |
| [getZoom()](#getZoom--) | Especifica el nivel de zoom en porcentaje. |
| [setZoom(int value)](#setZoom-int-) | Especifica el nivel de zoom en porcentaje. |
| [getMarginTop()](#getMarginTop--) | Margen superior de página deseado en píxeles después de la conversión. |
| [setMarginTop(int value)](#setMarginTop-int-) | Margen superior de página deseado en píxeles después de la conversión. |
| [getMarginBottom()](#getMarginBottom--) | Margen inferior de página deseado en píxeles después de la conversión. |
| [setMarginBottom(int value)](#setMarginBottom-int-) | Margen inferior de página deseado en píxeles después de la conversión. |
| [getMarginLeft()](#getMarginLeft--) | Margen izquierdo de página deseado en píxeles después de la conversión. |
| [setMarginLeft(int value)](#setMarginLeft-int-) | Margen izquierdo de página deseado en píxeles después de la conversión. |
| [getMarginRight()](#getMarginRight--) | Margen derecho de página deseado en píxeles después de la conversión. |
| [setMarginRight(int value)](#setMarginRight-int-) | Margen derecho de página deseado en píxeles después de la conversión. |
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPdfRecognitionMode()](#getPdfRecognitionMode--) |  |
| [setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)](#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-) |  |
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


Inicializa una nueva instancia de la clase [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions).

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

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


Opciones de conversión específicas de RTF

**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


Opciones de conversión específicas de RTF

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100. El zoom predeterminado es compatible hasta Microsoft Word 2010. A partir de Microsoft Word 2013 el zoom predeterminado ya no se establece en el documento, sino que parece usar el factor de zoom del último documento abierto.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100. El zoom predeterminado es compatible hasta Microsoft Word 2010. A partir de Microsoft Word 2013 el zoom predeterminado ya no se establece en el documento, sino que parece usar el factor de zoom del último documento abierto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


Obtiene el modo de reconocimiento al convertir desde pdf

**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


Establece el modo de reconocimiento al convertir desde pdf

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

