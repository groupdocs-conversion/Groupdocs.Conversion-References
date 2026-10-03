---
title: "EmailLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos de correo electrónico."
type: docs
weight: 18
url: /es/java/com.groupdocs.conversion.options.load/emailloadoptions/
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
|  | [EmailLoadOptions()](#EmailLoadOptions--) | Inicializa una nueva instancia de la clase [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | Opción para mostrar u ocultar el encabezado del correo electrónico. |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Opción para mostrar u ocultar el encabezado del correo electrónico. |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Opción para mostrar u ocultar la dirección de correo "from". |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Opción para mostrar u ocultar la dirección de correo "from". |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Opción para mostrar u ocultar la dirección de correo "to". |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Opción para mostrar u ocultar la dirección de correo "to". |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Opción para mostrar u ocultar la dirección de correo "Cc". |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Opción para mostrar u ocultar la dirección de correo "Cc". |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Opción para mostrar u ocultar la dirección de correo "Bcc". |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Opción para mostrar u ocultar la dirección de correo "Bcc". |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Obtiene o establece el desplazamiento de Tiempo Universal Coordinado (UTC) para las fechas de los mensajes. |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Tiempo de espera para cargar recursos externos |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Tiempo de espera para cargar recursos externos (setter) |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Obtiene o establece el desplazamiento de Tiempo Universal Coordinado (UTC) para las fechas de los mensajes. |
|
|  | [deepClone()](#deepClone--) | Clona la instancia actual. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Obtiene el mapeo entre el mensaje de correo electrónico y la representación de texto del campo |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Establece el mapeo entre el mensaje de correo electrónico y la representación de texto del campo |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Define si es necesario mantener la cadena original del encabezado de fecha en el mensaje de correo al guardar o no (el valor predeterminado es true) |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Define si es necesario mantener la cadena original del encabezado de fecha en el mensaje de correo al guardar o no |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | Obtiene la opción para mostrar u ocultar los archivos adjuntos en el encabezado. |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | Establece la opción para mostrar u ocultar los archivos adjuntos en el encabezado. |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | Obtiene la opción para mostrar u ocultar el asunto en el encabezado. |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | Establece la opción para mostrar u ocultar el asunto en el encabezado |
|
|  | [isDisplaySent()](#isDisplaySent--) | Obtiene la opción para mostrar u ocultar la fecha/hora de envío en el encabezado. |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | Establece la opción para mostrar u ocultar la fecha/hora de envío en el encabezado. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Omite la carga de recursos http si es verdadero |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
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
booleano
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Opción para mostrar u ocultar el encabezado del correo electrónico. Predeterminado: true.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Opción para mostrar u ocultar la dirección de correo "from". Predeterminado: true.


**Returns:**
booleano
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Opción para mostrar u ocultar la dirección de correo "from". Predeterminado: true.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Opción para mostrar u ocultar la dirección de correo "to". Predeterminado: true.


**Returns:**
booleano
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Opción para mostrar u ocultar la dirección de correo "to". Predeterminado: true.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Opción para mostrar u ocultar la dirección de correo "Cc". Predeterminado: false.


**Returns:**
booleano
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Opción para mostrar u ocultar la dirección de correo "Cc". Predeterminado: false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Opción para mostrar u ocultar la dirección de correo "Bcc". Predeterminado: false.


**Returns:**
booleano
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Opción para mostrar u ocultar la dirección de correo "Bcc". Predeterminado: false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

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


Tiempo de espera para cargar recursos externos (setter)


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


Obtiene el mapeo entre el mensaje de correo electrónico y la representación de texto del campo


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - mapeo

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Establece el mapeo entre el mensaje de correo electrónico y la representación de texto del campo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | mapeo |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Define si es necesario mantener la cadena original del encabezado de fecha en el mensaje de correo al guardar o no (el valor predeterminado es true)


**Returns:**
boolean - preservar la fecha original si es verdadero

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Define si es necesario mantener la cadena original del encabezado de fecha en el mensaje de correo al guardar o no


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | preserveOriginalDate | booleano | preservar la fecha original |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtiene la opción para controlar si el contenedor de los documentos debe convertirse


**Returns:**
booleano
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOwner | booleano |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opción para controlar si los documentos propios en el contenedor de documentos deben convertirse


**Returns:**
booleano
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOwned | booleano |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Opción para controlar cuántos niveles de profundidad se deben usar para realizar la conversión


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| depth | int |  |

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


Obtiene la opción para mostrar u ocultar los archivos adjuntos en el encabezado. Predeterminado: true.


**Returns:**
booleano
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


Establece la opción para mostrar u ocultar los archivos adjuntos en el encabezado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| displayAttachments | booleano |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


Obtiene la opción para mostrar u ocultar el asunto en el encabezado. Predeterminado: true.


**Returns:**
booleano
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


Establece la opción para mostrar u ocultar el asunto en el encabezado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| displaySubject | booleano |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


Obtiene la opción para mostrar u ocultar la fecha/hora de envío en el encabezado. Predeterminado: true.


**Returns:**
booleano
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


Establece la opción para mostrar u ocultar la fecha/hora de envío en el encabezado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| displaySent | booleano |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Omite la carga de recursos http si es verdadero


**Returns:**
booleano
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| skipExternalResources | booleano |  |

