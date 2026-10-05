---
title: "PersonalStorageLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Kişisel depolama belgelerini yükleme seçenekleri."
type: docs
weight: 32
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Kişisel depolama belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | class'ın yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFolder()](#getFolder--) | İşlenecek klasör, varsayılan olarak Gelen Kutusu'dur |
| [setFolder(String folder)](#setFolder-java.lang.String-) | İşlenecek klasörü ayarla |
| [isConvertOwner()](#isConvertOwner--) | \{@inheritDoc\} Sahip dönüştürülmeyecek |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getDepth()](#getDepth--) | \{@inheritDoc\} |
| [setDepth(int depth)](#setDepth-int-) | \{@inheritDoc\} |
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


class'ın yeni bir örneğini başlatır.

### getFolder() {#getFolder--}
```
public String getFolder()
```


İşlenecek klasör, varsayılan olarak Gelen Kutusu'dur

**Returns:**
java.lang.String - İşlenecek klasör
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


İşlenecek klasörü ayarla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| klasör | java.lang.String | klasör |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Belgelerin kapsayıcısının kendisinin dönüştürülüp dönüştürülmeyeceğini kontrol eden seçeneği alır Sahip dönüştürülmeyecek

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

