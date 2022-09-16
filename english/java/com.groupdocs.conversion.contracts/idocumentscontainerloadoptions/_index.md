---
title: IDocumentsContainerLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Loading options for documents container
type: docs
weight: 30
url: /java/com.groupdocs.conversion.contracts/idocumentscontainerloadoptions/
---```
public interface IDocumentsContainerLoadOptions
```

Loading options for documents container
## Methods

| Method | Description |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | Gets option to control whether the documents container itself must be converted |
| [isConvertOwned()](#isConvertOwned--) | Option to control whether the owned documents in the documents container must be converted |
| [getDepth()](#getDepth--) | Option to control how many levels in depth to perform conversion |
### isConvertOwner() {#isConvertOwner--}
```
public abstract boolean isConvertOwner()
```


Gets option to control whether the documents container itself must be converted

**Returns:**
boolean - If this property is true the documents container will be the first converted document
### isConvertOwned() {#isConvertOwned--}
```
public abstract boolean isConvertOwned()
```


Option to control whether the owned documents in the documents container must be converted

**Returns:**
boolean - true if the owned documents in the documents container must be converted
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Option to control how many levels in depth to perform conversion

**Returns:**
int - depth levels count
