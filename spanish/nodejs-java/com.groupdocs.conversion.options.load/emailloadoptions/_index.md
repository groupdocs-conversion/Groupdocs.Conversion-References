---
title: "EmailLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para cargar documentos de correo electrónico."
type: docs
weight: 19
url: /es/nodejs-java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Opciones para cargar documentos de correo electrónico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmailLoadOptions()](#EmailLoadOptions--) | Inicializa una nueva instancia de la clase [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDisplayHeader()](#getDisplayHeader--) | Opción para mostrar u ocultar el encabezado del correo electrónico. |
| [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Opción para mostrar u ocultar el encabezado del correo electrónico. |
| [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Opción para mostrar u ocultar la dirección de correo "de". |
| [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Opción para mostrar u ocultar la dirección de correo "de". |
| [getDisplayEmailAddress()](#getDisplayEmailAddress--) | Opción para mostrar u ocultar la dirección de correo electrónico. |
| [setDisplayEmailAddress(boolean value)](#setDisplayEmailAddress-boolean-) | Opción para mostrar u ocultar la dirección de correo electrónico. |
| [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Opción para mostrar u ocultar la dirección de correo "para". |
| [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Opción para mostrar u ocultar la dirección de correo "para". |
| [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Opción para mostrar u ocultar la dirección de correo "Cc". |
| [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Opción para mostrar u ocultar la dirección de correo "Cc". |
| [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Opción para mostrar u ocultar la dirección de correo "Bcc". |
| [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Opción para mostrar u ocultar la dirección de correo "Bcc". |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Obtiene o establece la diferencia horaria UTC (Coordinated Universal Time) para las fechas de los mensajes. |
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Tiempo de espera para cargar recursos externos |
| [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Tiempo de espera para cargar recursos externos (establecedor) |
| [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Obtiene o establece la diferencia horaria UTC (Coordinated Universal Time) para las fechas de los mensajes. |
| [deepClone()](#deepClone--) | Clona la instancia actual. |
| [getFieldTextMap()](#getFieldTextMap--) | Obtiene la asignación entre el mensaje de correo electrónico y la representación de texto del campo |
| [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Establece la asignación entre el mensaje de correo electrónico y la representación de texto del campo |
| [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Define si es necesario conservar la cadena del encabezado de fecha original en el mensaje de correo al guardar o no (el valor predeterminado es verdadero) |
| [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Define si es necesario conservar la cadena del encabezado de fecha original en el mensaje de correo al guardar o no |
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


Inicializa una nueva instancia de la clase [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).

### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Tipo de archivo del documento de entrada

**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Opción para mostrar u ocultar el encabezado del correo electrónico. Predeterminado: true.

**Returns:**
boolean
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Opción para mostrar u ocultar el encabezado del correo electrónico. Predeterminado: true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Opción para mostrar u ocultar la dirección de correo "from". Predeterminado: true.

**Returns:**
boolean
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Opción para mostrar u ocultar la dirección de correo "from". Predeterminado: true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getDisplayEmailAddress() {#getDisplayEmailAddress--}
```
public final boolean getDisplayEmailAddress()
```


Opción para mostrar u ocultar la dirección de correo electrónico. Predeterminado: true.

**Returns:**
boolean
### setDisplayEmailAddress(boolean value) {#setDisplayEmailAddress-boolean-}
```
public final void setDisplayEmailAddress(boolean value)
```


Opción para mostrar u ocultar la dirección de correo electrónico. Predeterminado: true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Opción para mostrar u ocultar la dirección de correo "to". Predeterminado: true.

**Returns:**
boolean
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Opción para mostrar u ocultar la dirección de correo "to". Predeterminado: true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Opción para mostrar u ocultar la dirección de correo "Cc". Predeterminado: false.

**Returns:**
boolean
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Opción para mostrar u ocultar la dirección de correo "Cc". Predeterminado: false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Opción para mostrar u ocultar la dirección de correo "Bcc". Predeterminado: false.

**Returns:**
boolean
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Opción para mostrar u ocultar la dirección de correo "Bcc". Predeterminado: false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Obtiene o establece el desplazamiento de Tiempo Universal Coordinado (UTC) para las fechas de los mensajes. Esta propiedad define la diferencia horaria entre la hora local y UTC.

**Returns:**
java.lang.Double
### getTimeZoneOffsetInternal() {#getTimeZoneOffsetInternal--}
```
public System.TimeSpan getTimeZoneOffsetInternal()
```




**Returns:**
com.aspose.ms.System.TimeSpan
### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```


Tiempo de espera para cargar recursos externos

**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Tiempo de espera para cargar recursos externos (establecedor)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Obtiene o establece el desplazamiento de Tiempo Universal Coordinado (UTC) para las fechas de los mensajes. Esta propiedad define la diferencia horaria entre la hora local y UTC.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clona la instancia actual.

**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


Obtiene la asignación entre el mensaje de correo electrónico y la representación de texto del campo

**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - mapeo
### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Establece la asignación entre el mensaje de correo electrónico y la representación de texto del campo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | mapeo |

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Define si es necesario conservar la cadena del encabezado de fecha original en el mensaje de correo al guardar o no (el valor predeterminado es verdadero)

**Returns:**
boolean - preservar la fecha original si es true
### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Define si es necesario conservar la cadena del encabezado de fecha original en el mensaje de correo al guardar o no

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| preserveOriginalDate | boolean | preservar fecha original |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtiene la opción para controlar si el contenedor de documentos debe ser convertido

**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opción para controlar si los documentos propiedad en el contenedor de documentos deben convertirse

**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Opción para controlar cuántos niveles de profundidad se deben convertir

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| profundidad | int |  |

