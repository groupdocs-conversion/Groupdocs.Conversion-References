---
title: "TxtLoadOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Txt belgelerini yükleme seçenekleri."
type: docs
weight: 34
url: /tr/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Txt belgelerini yükleme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Düz metin belgesi dönüştürüldüğünde numaralı liste öğelerinin nasıl tanındığını belirtmeye izin verir. |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Düz metin belgesi dönüştürüldüğünde numaralı liste öğelerinin nasıl tanındığını belirtmeye izin verir. |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Sondaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Sondaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Başlangıçtaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Başlangıçtaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
|
|  | [getEncoding()](#getEncoding--) | Txt belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Txt belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


[TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) sınıfının yeni bir örneğini başlatır.


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Girdi belge dosya türü


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Düz metin belgesi dönüştürüldüğünde numaralı liste öğelerinin nasıl tanındığını belirtmeye izin verir.
Varsayılan değer true'dur.

<br />

*** ** * ** ***

Bu seçenek false olarak ayarlanırsa, listeler tanıma algoritması, liste numaraları şu ile bittiğinde liste paragraflarını algılar
ya nokta, sağ köşeli parantez ya da madde işareti sembolleri (örneğin "\\u2022", "\\*", "-" veya "o").

Bu seçenek true olarak ayarlanırsa, boşluk karakterleri de liste numarası sınırlayıcıları olarak kullanılır:
Arapça stil numaralandırma (1., 1.1.2.) için liste tanıma algoritması, boşluk karakterleri ve nokta (".") sembollerini birlikte kullanır.

<br />



**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Düz metin belgesi dönüştürüldüğünde numaralı liste öğelerinin nasıl tanındığını belirtmeye izin verir.
Varsayılan değer true'dur.

<br />

*** ** * ** ***

Bu seçenek false olarak ayarlanırsa, listeler tanıma algoritması, liste numaraları şu ile bittiğinde liste paragraflarını algılar
ya nokta, sağ köşeli parantez ya da madde işareti sembolleri (örneğin "\\u2022", "\\*", "-" veya "o").

Bu seçenek true olarak ayarlanırsa, boşluk karakterleri de liste numarası sınırlayıcıları olarak kullanılır:
Arapça stil numaralandırma (1., 1.1.2.) için liste tanıma algoritması, boşluk karakterleri ve nokta (".") sembollerini birlikte kullanır.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Sondaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar.
Varsayılan değer [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Sondaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar.
Varsayılan değer [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Başlangıçtaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar.
Varsayılan değer [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Başlangıçtaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar.
Varsayılan değer [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Txt belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. Null olabilir. Varsayılan değer null'dur.


**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Txt belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. Null olabilir. Varsayılan değer null'dur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset |  |

