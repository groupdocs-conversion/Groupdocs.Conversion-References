---
title: "OlmLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Olm belgelerini yükleme seçenekleri."
type: docs
weight: 29
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/olmloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class OlmLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Olm belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OlmLoadOptions()](#OlmLoadOptions--) | Yeni bir [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions) sınıf örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [folder](#folder) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [memberwiseClone()](#memberwiseClone--) |  |
| [isConvertOwner()](#isConvertOwner--) | Sahibi dönüştürülmeyecek |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getFolder()](#getFolder--) | İşlenecek klasör, varsayılan olarak Gelen Kutusu'dur |
| [setFolder(String folder)](#setFolder-java.lang.String-) |  |
| [getDepth()](#getDepth--) | \{@inheritDoc\} Varsayılan: 3 |
| [setDepth(int depth)](#setDepth-int-) |  |
| [deepClone()](#deepClone--) | Mevcut örneği klonlar. |
### OlmLoadOptions() {#OlmLoadOptions--}
```
public OlmLoadOptions()
```


Yeni bir [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions) sınıf örneği başlatır.

### folder {#folder}
```
public String folder
```


### memberwiseClone() {#memberwiseClone--}
```
public Object memberwiseClone()
```




**Returns:**
java.lang.Object
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
### getFolder() {#getFolder--}
```
public String getFolder()
```


İşlenecek klasör, varsayılan olarak Gelen Kutusu'dur

**Returns:**
java.lang.String
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| klasör | java.lang.String |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Dönüştürmenin kaç derinlik seviyesinde yapılacağını kontrol eden seçenek Varsayılan: 3

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

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Mevcut örneği klonlar.

**Returns:**
java.lang.Object
