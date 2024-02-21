---
title: MboxLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Options for loading Mbox documents.
type: docs
weight: 23
url: /nodejs-java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Options for loading Mbox documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [MboxLoadOptions()](#MboxLoadOptions--) | Initializes new instance of  class. |
## Methods

| Method | Description |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | The owner will not be converted |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getDepth()](#getDepth--) | \{@inheritDoc\} Default: 3 |
| [setDepth(int depth)](#setDepth-int-) | \{@inheritDoc\} |
| [getEqualityComponents()](#getEqualityComponents--) | \{@inheritDoc\} |
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
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

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
