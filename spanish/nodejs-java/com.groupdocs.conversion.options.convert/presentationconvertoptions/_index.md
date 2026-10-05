---
title: "PresentationConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Describe las opciones para la conversión al tipo de archivo Presentation."
type: docs
weight: 33
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Describe las opciones para la conversión al tipo de archivo Presentation.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationConvertOptions()](#PresentationConvertOptions--) | Inicializa una nueva instancia de la clase [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPassword()](#getPassword--) | Establezca esta propiedad si desea proteger el documento convertido con una contraseña. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Establezca esta propiedad si desea proteger el documento convertido con una contraseña. |
| [getZoom()](#getZoom--) | Especifica el nivel de zoom en porcentaje. |
| [setZoom(int value)](#setZoom-int-) | Especifica el nivel de zoom en porcentaje. |
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Inicializa una nueva instancia de la clase [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions).

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

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100. El zoom predeterminado es compatible hasta Microsoft Powerpoint 2010. A partir de Microsoft Powerpoint 2013, el zoom predeterminado ya no se establece en el documento; en su lugar, parece usar el factor de zoom del último documento abierto.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100. El zoom predeterminado es compatible hasta Microsoft Powerpoint 2010. A partir de Microsoft Powerpoint 2013, el zoom predeterminado ya no se establece en el documento; en su lugar, parece usar el factor de zoom del último documento abierto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

