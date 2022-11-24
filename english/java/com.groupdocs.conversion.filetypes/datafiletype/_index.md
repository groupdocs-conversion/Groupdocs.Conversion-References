---
title: DataFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Data documents.
type: docs
weight: 12
url: /java/com.groupdocs.conversion.filetypes/datafiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class DataFileType extends FileType
```

Defines Data documents. Includes the following file types: [Xml](../../com.groupdocs.conversion.filetypes/datafiletype\#Xml), [Json](../../com.groupdocs.conversion.filetypes/datafiletype\#Json).
## Constructors

| Constructor | Description |
| --- | --- |
| [DataFileType()](#DataFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Xml](#Xml) | XML stands for Extensible Markup Language that is similar to HTML but different in using tags for defining objects. |
| [Json](#Json) | JSON (JavaScript Object Notation) is an open standard file format for sharing data that uses human-readable text to store and transmit data. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### DataFileType() {#DataFileType--}
```
public DataFileType()
```


Serialization constructor

### Xml {#Xml}
```
public static final DataFileType Xml
```


XML stands for Extensible Markup Language that is similar to HTML but different in using tags for defining objects. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/xml

### Json {#Json}
```
public static final DataFileType Json
```


JSON (JavaScript Object Notation) is an open standard file format for sharing data that uses human-readable text to store and transmit data. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/json

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Prepared default load options for the source file type

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Prepared default convert options for the file type

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
