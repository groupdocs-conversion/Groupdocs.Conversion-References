---
title: OlmLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Options for loading Olm documents.
type: docs
weight: 29
url: /nodejs-java/com.groupdocs.conversion.options.load/olmloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class OlmLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Options for loading Olm documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [OlmLoadOptions()](#OlmLoadOptions--) | Initializes new instance of [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions) class. |
## Fields

| Field | Description |
| --- | --- |
| [folder](#folder) |  |
## Methods

| Method | Description |
| --- | --- |
| [memberwiseClone()](#memberwiseClone--) |  |
| [isConvertOwner()](#isConvertOwner--) | The owner will not be converted |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getFolder()](#getFolder--) | Folder which to be processed Default is Inbox |
| [setFolder(String folder)](#setFolder-java.lang.String-) |  |
| [getDepth()](#getDepth--) | \{@inheritDoc\} Default: 3 |
| [setDepth(int depth)](#setDepth-int-) |  |
| [deepClone()](#deepClone--) | Clones current instance. |
### OlmLoadOptions() {#OlmLoadOptions--}
```
public OlmLoadOptions()
```


Initializes new instance of [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions) class.

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
### getFolder() {#getFolder--}
```
public String getFolder()
```


Folder which to be processed Default is Inbox

**Returns:**
java.lang.String
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Option to control how many levels in depth to perform conversion Default: 3

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

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones current instance.

**Returns:**
java.lang.Object
