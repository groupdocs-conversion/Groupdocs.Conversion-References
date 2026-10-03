---
title: "CadLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos CAD."
type: docs
weight: 12
url: /es/java/com.groupdocs.conversion.options.load/cadloadoptions/
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
|  | [CadLoadOptions()](#CadLoadOptions--) | Inicializa una nueva instancia de la clase [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getLayoutNames()](#getLayoutNames--) | Especifica qué diseños CAD se convertirán |
|
|  | [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Especifica qué diseños CAD se convertirán |
|
|  | [getDrawType()](#getDrawType--) | Obtiene el tipo de dibujo. |
|
|  | [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Establece el tipo de dibujo. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Obtiene un color de fondo. |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Establece un color de fondo. |
|
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
|  | [getCtbSources()](#getCtbSources--) | Obtiene las fuentes CTB. |
|
|  | [setCtbSources(Map<String,InputStream> ctbSources)](#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--) | Establece las fuentes CTB. |
|
|  | [getDrawColor()](#getDrawColor--) | Obtiene el color de primer plano. |
|
|  | [setDrawColor(System.Drawing.Color drawColor)](#setDrawColor-com.aspose.ms.System.Drawing.Color-) | Establece el color de primer plano. |
|
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

### getCtbSources() {#getCtbSources--}
```
public Map<String,InputStream> getCtbSources()
```


Obtiene las fuentes CTB.


**Returns:**
java.util.Map<java.lang.String,java.io.InputStream>
### setCtbSources(Map<String,InputStream> ctbSources) {#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--}
```
public void setCtbSources(Map<String,InputStream> ctbSources)
```


Establece las fuentes CTB.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ctbSources | java.util.Map<java.lang.String,java.io.InputStream> |  |

### getDrawColor() {#getDrawColor--}
```
public System.Drawing.Color getDrawColor()
```


Obtiene el color de primer plano.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setDrawColor(System.Drawing.Color drawColor) {#setDrawColor-com.aspose.ms.System.Drawing.Color-}
```
public void setDrawColor(System.Drawing.Color drawColor)
```


Establece el color de primer plano.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| drawColor | com.aspose.ms.System.Drawing.Color |  |

