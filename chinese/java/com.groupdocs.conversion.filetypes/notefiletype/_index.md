---
title: "NoteFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义笔记格式。"
type: docs
weight: 19
url: /zh/java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

定义笔记格式。包括以下文件类型：
[One](../../com.groupdocs.conversion.filetypes/notefiletype#One).
了解更多关于笔记格式的信息 [此处](../https://wiki.fileformat.com/note-taking)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [NoteFileType()](#NoteFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [One](#One) | 扩展名为 .ONE 的文件由 Microsoft OneNote 应用程序创建。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


序列化构造函数


### One {#One}
```
public static final NoteFileType One
```


扩展名为 .ONE 的文件由 Microsoft OneNote 应用程序创建。OneNote 让您使用该应用程序收集信息，就像使用草稿本记笔记一样。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/note-taking/one)。


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


为源文件类型准备了默认加载选项


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
