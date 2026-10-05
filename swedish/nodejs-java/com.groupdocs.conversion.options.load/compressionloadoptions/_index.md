---
title: "CompressionLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för inläsning av komprimeringsdokument."
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/compressionloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class CompressionLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Alternativ för inläsning av komprimeringsdokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CompressionLoadOptions()](#CompressionLoadOptions--) | Initierar en ny instans av  klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | Ägaren kommer inte att konverteras |
| [isConvertOwned()](#isConvertOwned--) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
| [getPassword()](#getPassword--) |  |
| [setPassword(String password)](#setPassword-java.lang.String-) | Ange lösenord för att läsa in skyddat dokument. |
| [getEqualityComponents()](#getEqualityComponents--) |  |
### CompressionLoadOptions() {#CompressionLoadOptions--}
```
public CompressionLoadOptions()
```


Initierar en ny instans av  klassen.

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Ägaren kommer inte att konverteras

**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Alternativ för att styra om de ägda dokumenten i dokumentbehållaren måste konverteras

**Returns:**
boolean
### getDepth() {#getDepth--}
```
public int getDepth()
```


Alternativ för att styra hur många nivåer i djupet konverteringen ska utföras

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| djup | int |  |

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


Ange lösenord för att läsa in skyddat dokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | java.lang.String | lösenord |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
