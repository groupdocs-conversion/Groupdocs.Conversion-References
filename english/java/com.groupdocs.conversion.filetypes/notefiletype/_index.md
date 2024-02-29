---
title: NoteFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Note-taking formats.
type: docs
weight: 19
url: /java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Defines Note-taking formats. Includes the following file types: [One](../../com.groupdocs.conversion.filetypes/notefiletype\#One). Learn more about Note-taking formats [here][].


[here]: https://wiki.fileformat.com/note-taking
## Constructors

| Constructor | Description |
| --- | --- |
| [NoteFileType()](#NoteFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [One](#One) | File represented by .ONE extension are created by Microsoft OneNote application. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Serialization constructor

### One {#One}
```
public static final NoteFileType One
```


File represented by .ONE extension are created by Microsoft OneNote application. OneNote lets you gather information using the application as if you are using your draftpad for taking notes. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Prepared default load options for the source file type

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
