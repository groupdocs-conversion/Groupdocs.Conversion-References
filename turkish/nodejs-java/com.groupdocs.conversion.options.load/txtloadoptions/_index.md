---
title: "TxtLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Txt belgelerini yükleme seçenekleri."
type: docs
weight: 38
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/txtloadoptions/
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
| [TxtLoadOptions()](#TxtLoadOptions--) | Yeni bir [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Düz metin belgesi dönüştürülürken numaralı liste öğelerinin nasıl tanınacağını belirtmeye olanak tanır. |
| [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Düz metin belgesi dönüştürülürken numaralı liste öğelerinin nasıl tanınacağını belirtmeye olanak tanır. |
| [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Sondaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
| [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Sondaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
| [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Başlangıçtaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
| [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Başlangıçtaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
| [getEncoding()](#getEncoding--) | Txt belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Txt belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. |
| [setEncoding(String charsetName)](#setEncoding-java.lang.String-) | Txt belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. |
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Yeni bir [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) sınıfı örneği başlatır.

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


Düz metin belgesi dönüştürülürken numaralı liste öğelerinin nasıl tanınacağını belirtmeye olanak tanır. Varsayılan değer doğrudur.

--------------------

Bu seçenek false olarak ayarlanırsa, liste tanıma algoritması, liste numaraları nokta, sağ parantez veya madde işareti (ör. \"\\u2022\", \"\\*\", \"-\" veya \"o\") ile bittiğinde liste paragraflarını algılar.

Bu seçenek true olarak ayarlanırsa, boşluk karakterleri de liste numarası ayırıcıları olarak kullanılır: Arapça stil numaralandırma (1., 1.1.2.) için liste tanıma algoritması hem boşlukları hem de nokta (\".\") sembollerini kullanır.

**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Düz metin belgesi dönüştürülürken numaralı liste öğelerinin nasıl tanınacağını belirtmeye olanak tanır. Varsayılan değer doğrudur.

--------------------

Bu seçenek false olarak ayarlanırsa, liste tanıma algoritması, liste numaraları nokta, sağ parantez veya madde işareti (ör. \"\\u2022\", \"\\*\", \"-\" veya \"o\") ile bittiğinde liste paragraflarını algılar.

Bu seçenek true olarak ayarlanırsa, boşluk karakterleri de liste numarası ayırıcıları olarak kullanılır: Arapça stil numaralandırma (1., 1.1.2.) için liste tanıma algoritması hem boşlukları hem de nokta (\".\") sembollerini kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Sondaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan değer [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions\\#Trim)'dir.

**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Sondaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan değer [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions\\#Trim)'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Başlangıçtaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan değer [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions\\#ConvertToIndent)'dir.

**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Başlangıçtaki boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan değer [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions\\#ConvertToIndent)'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Txt belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. Null olabilir. Varsayılan null'dur.

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


Txt belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. Null olabilir. Varsayılan null'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset |  |

### setEncoding(String charsetName) {#setEncoding-java.lang.String-}
```
public final void setEncoding(String charsetName)
```


Txt belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. Null olabilir. Varsayılan null'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| charsetName | java.lang.String |  |

