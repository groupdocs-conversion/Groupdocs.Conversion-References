---
title: CompressionLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Options for loading compression documents.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.conversion.options.load/compressionloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class CompressionLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Options for loading compression documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [CompressionLoadOptions()](#CompressionLoadOptions--) | Initializes new instance of  class. |
## Methods

| Method | Description |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | The owner will not be converted |
| [isConvertOwned()](#isConvertOwned--) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
| [getPassword()](#getPassword--) |  |
| [setPassword(String password)](#setPassword-java.lang.String-) | Set password to load protected document. |
| [getEqualityComponents()](#getEqualityComponents--) |  |
### CompressionLoadOptions() {#CompressionLoadOptions--}
```
public CompressionLoadOptions()
```


Initializes new instance of  class.

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


The owner will not be converted

**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Option to control whether the owned documents in the documents container must be converted

**Returns:**
boolean
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


Set password to load protected document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | password |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
