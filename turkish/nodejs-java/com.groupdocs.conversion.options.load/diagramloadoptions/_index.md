---
title: "DiagramLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Diagram belgelerini yükleme seçenekleri."
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Diagram belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DiagramLoadOptions()](#DiagramLoadOptions--) | Yeni bir [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Diagram belgesi için varsayılan yazı tipi. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Diagram belgesi için varsayılan yazı tipi. |
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


Yeni bir [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) sınıfının örneğini başlatır.

### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


Girdi belge dosya türü

**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Diagram belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Diagram belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

