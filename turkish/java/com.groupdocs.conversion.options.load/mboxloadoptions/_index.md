---
title: "MboxLoadOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Mbox belgelerini yükleme seçenekleri."
type: docs
weight: 23
url: /tr/java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Mbox belgelerini yükleme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [MboxLoadOptions()](#MboxLoadOptions--) | Sınıfın yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isConvertOwner()](#isConvertOwner--) | Sahibi dönüştürülmeyecek |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} Varsayılan: 3 |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | {@inheritDoc} |
|
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


Sınıfın yeni bir örneğini başlatır.


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


Belge konteynerindeki sahip olunan belgelerin dönüştürülüp dönüştürülmeyeceğini kontrol etme seçeneği


**Returns:**
boolean
### getDepth() {#getDepth--}
```
public int getDepth()
```


Dönüşümün kaç derinlik seviyesinde gerçekleştirileceğini kontrol eden seçenek Varsayılan: 3


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

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
