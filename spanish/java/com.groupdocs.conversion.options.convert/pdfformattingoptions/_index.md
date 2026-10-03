---
title: "PdfFormattingOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Define las opciones de formato Pdf."
type: docs
weight: 28
url: /es/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Define las opciones de formato Pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | Especifica si la posición de la ventana del documento se centrará en la pantalla. |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Especifica si la posición de la ventana del documento se centrará en la pantalla. |
|
|  | [getDirection()](#getDirection--) | Establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | Especifica si la barra de título de la ventana del documento debe mostrar el título del documento. |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Especifica si la barra de título de la ventana del documento debe mostrar el título del documento. |
|
|  | [getFitWindow()](#getFitWindow--) | Especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | Especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | Especifica si la barra de menú debe ocultarse cuando el documento está activo. |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Especifica si la barra de menú debe ocultarse cuando el documento está activo. |
|
|  | [getHideToolBar()](#getHideToolBar--) | Especifica si la barra de herramientas debe ocultarse cuando el documento está activo. |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Especifica si la barra de herramientas debe ocultarse cuando el documento está activo. |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | Especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa. |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa. |
|
|  | [getPageLayout()](#getPageLayout--) | Establece el diseño de página que se utilizará cuando se abra el documento. |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Establece el diseño de página que se utilizará cuando se abra el documento. |
|
|  | [getPageMode()](#getPageMode--) | Establece el modo de página, especificando cómo debe mostrarse el documento al abrirse. |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Establece el modo de página, especificando cómo debe mostrarse el documento al abrirse. |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Especifica si la posición de la ventana del documento se centrará en la pantalla. Predeterminado: false.


**Returns:**
booleano
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Especifica si la posición de la ventana del documento se centrará en la pantalla. Predeterminado: false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). Predeterminado: L2R.


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). Predeterminado: L2R.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Especifica si la barra de título de la ventana del documento debe mostrar el título del documento. Predeterminado: false.


**Returns:**
booleano
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Especifica si la barra de título de la ventana del documento debe mostrar el título del documento. Predeterminado: false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. Predeterminado: false.


**Returns:**
booleano
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. Predeterminado: false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Especifica si la barra de menú debe ocultarse cuando el documento está activo. Predeterminado: false.


**Returns:**
booleano
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Especifica si la barra de menú debe ocultarse cuando el documento está activo. Predeterminado: false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Especifica si la barra de herramientas debe ocultarse cuando el documento está activo. Predeterminado: false.


**Returns:**
booleano
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Especifica si la barra de herramientas debe ocultarse cuando el documento está activo. Predeterminado: false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. Predeterminado: false.


**Returns:**
booleano
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. Predeterminado: false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Establece el diseño de página que se utilizará cuando se abra el documento.


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Establece el diseño de página que se utilizará cuando se abra el documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Establece el modo de página, especificando cómo debe mostrarse el documento al abrirse.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Establece el modo de página, especificando cómo debe mostrarse el documento al abrirse.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

