---
title: EmailLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading Email documents.
type: docs
weight: 15
url: /java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Options for loading Email documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailLoadOptions()](#EmailLoadOptions--) | Initializes new instance of [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDisplayHeader()](#getDisplayHeader--) | Option to display or hide the email header. |
| [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Option to display or hide the email header. |
| [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Option to display or hide "from" email address. |
| [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Option to display or hide "from" email address. |
| [getDisplayEmailAddress()](#getDisplayEmailAddress--) | Option to display or hide email address. |
| [setDisplayEmailAddress(boolean value)](#setDisplayEmailAddress-boolean-) | Option to display or hide email address. |
| [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Option to display or hide "to" email address. |
| [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Option to display or hide "to" email address. |
| [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Option to display or hide "Cc" email address. |
| [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Option to display or hide "Cc" email address. |
| [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Option to display or hide "Bcc" email address. |
| [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Option to display or hide "Bcc" email address. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. |
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Timeout for loading external resources |
| [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Timeout for loading external resources (setter) |
| [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. |
| [deepClone()](#deepClone--) | Clones current instance. |
| [getFieldTextMap()](#getFieldTextMap--) | Gets the mapping between email message  and field text representation |
| [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Sets the mapping between email message  and field text representation |
| [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Defines whether need to keep original date header string in mail message when saving or not (Default value is true) |
| [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Defines whether need to keep original date header string in mail message when saving or not |
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


Initializes new instance of [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) class.

### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Input document file type

**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Option to display or hide the email header. Default: true.

**Returns:**
boolean
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Option to display or hide the email header. Default: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Option to display or hide "from" email address. Default: true.

**Returns:**
boolean
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Option to display or hide "from" email address. Default: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayEmailAddress() {#getDisplayEmailAddress--}
```
public final boolean getDisplayEmailAddress()
```


Option to display or hide email address. Default: true.

**Returns:**
boolean
### setDisplayEmailAddress(boolean value) {#setDisplayEmailAddress-boolean-}
```
public final void setDisplayEmailAddress(boolean value)
```


Option to display or hide email address. Default: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Option to display or hide "to" email address. Default: true.

**Returns:**
boolean
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Option to display or hide "to" email address. Default: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Option to display or hide "Cc" email address. Default: false.

**Returns:**
boolean
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Option to display or hide "Cc" email address. Default: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Option to display or hide "Bcc" email address. Default: false.

**Returns:**
boolean
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Option to display or hide "Bcc" email address. Default: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. This property defines the time zone difference, between the localtime and UTC.

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


Timeout for loading external resources

**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Timeout for loading external resources (setter)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. This property defines the time zone difference, between the localtime and UTC.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clones current instance.

**Returns:**
java.lang.Object - 
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


Gets the mapping between email message  and field text representation

**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - mapping
### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Sets the mapping between email message  and field text representation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | mapping |

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Defines whether need to keep original date header string in mail message when saving or not (Default value is true)

**Returns:**
boolean - preserve original date if true
### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Defines whether need to keep original date header string in mail message when saving or not

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| preserveOriginalDate | boolean | preserve original date |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Gets option to control whether the documents container itself must be converted

**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Option to control whether the owned documents in the documents container must be converted

**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Option to control how many levels in depth to perform conversion

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| depth | int |  |

