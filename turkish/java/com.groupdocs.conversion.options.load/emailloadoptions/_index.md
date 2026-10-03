---
title: "EmailLoadOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "E-posta belgelerini yükleme seçenekleri."
type: docs
weight: 18
url: /tr/java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

E-posta belgelerini yükleme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [EmailLoadOptions()](#EmailLoadOptions--) | Yeni bir [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) sınıfının örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | E-posta başlığını gösterme veya gizleme seçeneği. |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | E-posta başlığını gösterme veya gizleme seçeneği. |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | E-posta "from" adresini gösterme veya gizleme seçeneği. |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | E-posta "from" adresini gösterme veya gizleme seçeneği. |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | E-posta "to" adresini gösterme veya gizleme seçeneği. |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | E-posta "to" adresini gösterme veya gizleme seçeneği. |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | E-posta "Cc" adresini gösterme veya gizleme seçeneği. |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | E-posta "Cc" adresini gösterme veya gizleme seçeneği. |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | E-posta "Bcc" adresini gösterme veya gizleme seçeneği. |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | E-posta "Bcc" adresini gösterme veya gizleme seçeneği. |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Mesaj tarihleri için Koordinatlı Evrensel Zaman (UTC) ofsetini alır veya ayarlar. |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Harici kaynakları yükleme zaman aşımı |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Harici kaynakları yükleme zaman aşımı (ayarlayıcı) |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Mesaj tarihleri için Koordinatlı Evrensel Zaman (UTC) ofsetini alır veya ayarlar. |
|
|  | [deepClone()](#deepClone--) | Mevcut örneği klonlar. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | E-posta mesajı ile alan metni temsili arasındaki eşlemeyi alır |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | E-posta mesajı ile alan metni temsili arasındaki eşlemeyi ayarlar |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Kaydederken posta mesajında orijinal tarih başlığı dizesinin tutulup tutulmayacağını tanımlar (Varsayılan değer true'tır) |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Kaydederken posta mesajında orijinal tarih başlığı dizesinin tutulup tutulmayacağını tanımlar |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | Başlıkta ekleri gösterme veya gizleme seçeneğini alır. |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | Başlıkta ekleri gösterme veya gizleme seçeneğini ayarlar. |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | Başlıkta konuyu gösterme veya gizleme seçeneğini alır. |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | Başlıkta konuyu gösterme veya gizleme seçeneğini ayarlar |
|
|  | [isDisplaySent()](#isDisplaySent--) | Başlıkta gönderim tarih/saatini gösterme veya gizleme seçeneğini alır. |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | Başlıkta gönderim tarih/saatini gösterme veya gizleme seçeneğini ayarlar. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Doğru ise http kaynak yüklemesini atlar |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


Yeni bir [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) sınıfının örneğini başlatır.


### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Girdi belge dosya türü


**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


E-posta başlığını gösterme veya gizleme seçeneği. Varsayılan: true.


**Returns:**
boolean
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


E-posta başlığını gösterme veya gizleme seçeneği. Varsayılan: true.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


"From" e-posta adresini gösterme veya gizleme seçeneği. Varsayılan: true.


**Returns:**
boolean
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


"From" e-posta adresini gösterme veya gizleme seçeneği. Varsayılan: true.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


"To" e-posta adresini gösterme veya gizleme seçeneği. Varsayılan: true.


**Returns:**
boolean
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


"To" e-posta adresini gösterme veya gizleme seçeneği. Varsayılan: true.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


"Cc" e-posta adresini gösterme veya gizleme seçeneği. Varsayılan: false.


**Returns:**
boolean
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


"Cc" e-posta adresini gösterme veya gizleme seçeneği. Varsayılan: false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


"Bcc" e-posta adresini gösterme veya gizleme seçeneği. Varsayılan: false.


**Returns:**
boolean
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


"Bcc" e-posta adresini gösterme veya gizleme seçeneği. Varsayılan: false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Mesaj tarihleri için Koordinatlı Evrensel Zaman (UTC) ofsetini alır veya ayarlar. Bu özellik, yerel zaman ile UTC arasındaki saat dilimi farkını tanımlar.


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


Harici kaynakları yükleme zaman aşımı


**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Harici kaynakları yükleme zaman aşımı (ayarlayıcı)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Mesaj tarihleri için Koordinatlı Evrensel Zaman (UTC) ofsetini alır veya ayarlar. Bu özellik, yerel zaman ile UTC arasındaki saat dilimi farkını tanımlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mevcut örneği klonlar.


**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


E-posta mesajı ile alan metni temsili arasındaki eşlemeyi alır


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - eşleme

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


E-posta mesajı ile alan metni temsili arasındaki eşlemeyi ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | eşleme |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Kaydederken posta mesajında orijinal tarih başlığı dizesinin tutulup tutulmayacağını tanımlar (Varsayılan değer true'tır)


**Returns:**
boolean - doğru ise orijinal tarihi koru

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Kaydederken posta mesajında orijinal tarih başlığı dizesinin tutulup tutulmayacağını tanımlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | preserveOriginalDate | boolean | orijinal tarihi koru |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Belge konteynerinin kendisinin dönüştürülüp dönüştürülmeyeceğini kontrol etmek için seçeneği alır


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Belge konteynerindeki sahip olunan belgelerin dönüştürülüp dönüştürülmeyeceğini kontrol etme seçeneği


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Dönüştürmenin kaç derinlik seviyesinde yapılacağını kontrol etme seçeneği


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| depth | int |  |

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


Başlıkta ekleri gösterme veya gizleme seçeneğini alır. Varsayılan: true.


**Returns:**
boolean
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


Başlıkta ekleri gösterme veya gizleme seçeneğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| displayAttachments | boolean |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


Başlıkta konuyu gösterme veya gizleme seçeneğini alır. Varsayılan: true.


**Returns:**
boolean
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


Başlıkta konuyu gösterme veya gizleme seçeneğini ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| displaySubject | boolean |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


Başlıkta gönderim tarih/saatini gösterme veya gizleme seçeneğini alır. Varsayılan: true.


**Returns:**
boolean
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


Başlıkta gönderim tarih/saatini gösterme veya gizleme seçeneğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| displaySent | boolean |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Doğru ise http kaynak yüklemesini atlar


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| skipExternalResources | boolean |  |

