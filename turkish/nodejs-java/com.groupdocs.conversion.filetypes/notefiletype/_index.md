---
title: "NoteFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Not alma biçimlerini tanımlar."
type: docs
weight: 19
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Not alma formatlarını tanımlar. Aşağıdaki dosya türlerini içerir: [One](../../com.groupdocs.conversion.filetypes/notefiletype\#One). Not alma formatları hakkında daha fazla bilgi için [burada][].


[here]: https://wiki.fileformat.com/note-taking
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [NoteFileType()](#NoteFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [One](#One) | .ONE uzantısıyla temsil edilen dosyalar Microsoft OneNote uygulaması tarafından oluşturulur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Serileştirme yapıcısı

### One {#One}
```
public static final NoteFileType One
```


.ONE uzantısıyla temsil edilen dosyalar Microsoft OneNote uygulaması tarafından oluşturulur. OneNote, uygulamayı not alırken taslak defterinizi kullandığınız gibi bilgi toplamanıza olanak tanır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
