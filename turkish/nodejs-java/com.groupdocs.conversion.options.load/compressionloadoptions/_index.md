---
title: "CompressionLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Sıkıştırma belgelerini yükleme seçenekleri."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/compressionloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class CompressionLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Sıkıştırma belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CompressionLoadOptions()](#CompressionLoadOptions--) | class'ın yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | Sahibi dönüştürülmeyecek |
| [isConvertOwned()](#isConvertOwned--) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
| [getPassword()](#getPassword--) |  |
| [setPassword(String password)](#setPassword-java.lang.String-) | Korunan belgeyi yüklemek için şifreyi ayarla. |
| [getEqualityComponents()](#getEqualityComponents--) |  |
### CompressionLoadOptions() {#CompressionLoadOptions--}
```
public CompressionLoadOptions()
```


class'ın yeni bir örneğini başlatır.

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Sahibi dönüştürülmeyecek

**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Belge konteynerindeki sahip olunan belgelerin dönüştürülüp dönüştürülmeyeceğini kontrol eden seçenek

**Returns:**
boolean
### getDepth() {#getDepth--}
```
public int getDepth()
```


Dönüştürmenin kaç derinlik seviyesinde yapılacağını kontrol eden seçenek

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| derinlik | int |  |

### getPassword() {#getPassword--}
```
public String getPassword()
```




**Returns:**
java.lang.String
### setPassword(String password) {#setPassword-java.lang.String-}
```
public void setPassword(String password)
```


Korunan belgeyi yüklemek için şifreyi ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | java.lang.String | password |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
