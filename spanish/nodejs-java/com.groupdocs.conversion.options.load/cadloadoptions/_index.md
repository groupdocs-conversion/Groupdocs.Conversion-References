---
title: "CadLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para cargar documentos CAD."
type: docs
weight: 12
url: /es/nodejs-java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

Opciones para cargar documentos CAD.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CadLoadOptions()](#CadLoadOptions--) | Inicializa una nueva instancia de la clase [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getWidth()](#getWidth--) | Establece el ancho de página deseado para convertir el documento CAD |
| [setWidth(int value)](#setWidth-int-) | Establece el ancho de página deseado para convertir el documento CAD |
| [getHeight()](#getHeight--) | Establece la altura de página deseada para convertir el documento CAD |
| [setHeight(int value)](#setHeight-int-) | Establece la altura de página deseada para convertir el documento CAD |
| [getLayoutNames()](#getLayoutNames--) | Especifica qué diseños CAD se convertirán |
| [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Especifica qué diseños CAD se convertirán |
| [getDrawType()](#getDrawType--) | Obtiene el tipo de dibujo. |
| [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Establece el tipo de dibujo. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene un color de fondo. |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Establece un color de fondo. |
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


Inicializa una nueva instancia de la clase [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions).

### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


Tipo de archivo del documento de entrada

**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Establece el ancho de página deseado para convertir el documento CAD

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Establece el ancho de página deseado para convertir el documento CAD

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Establece la altura de página deseada para convertir el documento CAD

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Establece la altura de página deseada para convertir el documento CAD

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


Especifica qué diseños CAD se convertirán

**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


Especifica qué diseños CAD se convertirán

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


Obtiene el tipo de dibujo.

**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


Establece el tipo de dibujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Obtiene un color de fondo.

**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Establece un color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

