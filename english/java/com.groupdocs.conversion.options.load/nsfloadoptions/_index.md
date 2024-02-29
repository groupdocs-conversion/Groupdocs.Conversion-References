---
title: NsfLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading Nsf documents.
type: docs
weight: 25
url: /java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Options for loading Nsf documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) |  |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### NsfLoadOptions() {#NsfLoadOptions--}
```
public NsfLoadOptions()
```


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Gets option to control whether the documents container itself must be converted

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

