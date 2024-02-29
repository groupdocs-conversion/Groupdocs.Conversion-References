---
title: DiagramLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading Diagram documents.
type: docs
weight: 15
url: /java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Options for loading Diagram documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [DiagramLoadOptions()](#DiagramLoadOptions--) | Initializes new instance of [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Default font for Diagram document. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Default font for Diagram document. |
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


Initializes new instance of [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) class.

### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


Input document file type

**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Default font for Diagram document. The following font will be used if a font is missing.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Default font for Diagram document. The following font will be used if a font is missing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

