---
title: "NoteFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет форматы для заметок."
type: docs
weight: 19
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Определяет форматы для заметок. Включает следующие типы файлов: [One](../../com.groupdocs.conversion.filetypes/notefiletype\#One). Узнайте больше о форматах для заметок [здесь][].


[here]: https://wiki.fileformat.com/note-taking
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [NoteFileType()](#NoteFileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [One](#One) | Файлы с расширением .ONE создаются приложением Microsoft OneNote. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Конструктор сериализации

### One {#One}
```
public static final NoteFileType One
```


Файлы с расширением .ONE создаются приложением Microsoft OneNote. OneNote позволяет собирать информацию, используя приложение, как будто вы используете черновик для записи заметок. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Подготовлены параметры загрузки по умолчанию для исходного типа файла

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
