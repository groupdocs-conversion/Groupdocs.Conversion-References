---
title: PersonalStorageLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading personal storage documents.
type: docs
weight: 24
url: /java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Options for loading personal storage documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Initializes new instance of  class. |
## Methods

| Method | Description |
| --- | --- |
| [getFolder()](#getFolder--) | Folder which to be processed Default is Inbox |
| [setFolder(String folder)](#setFolder-java.lang.String-) | Set folder which to be processed |
| [isConvertOwner()](#isConvertOwner--) | \{@inheritDoc\} The owner will not be converted |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getDepth()](#getDepth--) | \{@inheritDoc\} |
| [setDepth(int depth)](#setDepth-int-) | \{@inheritDoc\} |
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Initializes new instance of  class.

### getFolder() {#getFolder--}
```
public String getFolder()
```


Folder which to be processed Default is Inbox

**Returns:**
java.lang.String - Folder which to be processed
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Set folder which to be processed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | folder |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Gets option to control whether the documents container itself must be converted The owner will not be converted

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

