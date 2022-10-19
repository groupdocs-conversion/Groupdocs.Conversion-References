---
title: PresentationFileType
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Определяет форматы файлов презентаций в которых хранится коллекция записей для размещения данных презентации таких как слайды фигуры текст анимация видео аудио и встроенные объекты. Включает следующие типы файлов Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . Подробнее о форматах презентацийздесьhttps//wiki.fileformat.com/presentation .
type: docs
weight: 910
url: /ru/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Определяет форматы файлов презентаций, в которых хранится коллекция записей для размещения данных презентации, таких как слайды, фигуры, текст, анимация, видео, аудио и встроенные объекты. Включает следующие типы файлов: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . Подробнее о форматах презентаций[здесь](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Конструктор сериализации |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Файл family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Определяет, равны ли два экземпляра объекта. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит хеш-функцией по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Файлы с расширением FODP представляют собой представление OpenDocument Flat XML. Файл презентации, сохраненный в формате OpenDocument, но сохраненный с использованием плоского формата XML вместо контейнера .ZIP, используемого стандартными файлами .ODP |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Файлы с расширением ODP представляют формат файла презентации, используемый OpenOffice.org в стандарте OASISOpen. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Файлы с расширением .OTP представляют собой файлы шаблонов презентаций, созданные приложениями в стандартном формате OASIS OpenDocument. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Файлы с расширением .POT представляют собой файлы шаблонов Microsoft PowerPoint, созданные версиями PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Файлы с расширением POTM представляют собой файлы шаблонов Microsoft PowerPoint с поддержкой макросов. Файлы POTM создаются с помощью PowerPoint 2007 или более поздней версии и содержат параметры по умолчанию, которые можно использовать для создания дополнительных файлов презентаций. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Файлы с расширением .POTX представляют шаблоны презентаций Microsoft PowerPoint, созданные с помощью Microsoft PowerPoint 2007 и более поздних версий. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, слайд-шоу PowerPoint, файлы создаются с помощью Microsoft PowerPoint для целей слайд-шоу. Чтение и создание файла PPS поддерживается Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Файлы с расширением PPSM представляют формат файлов слайд-шоу с поддержкой макросов, созданный с помощью Microsoft PowerPoint 2007 или более поздней версии. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, слайд-шоу Power Point, файл создается с использованием Microsoft PowerPoint 2007 и более поздних версий для целей слайд-шоу. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Файл с расширением PPT представляет собой файл PowerPoint, состоящий из набора слайдов для отображения в виде слайд-шоу. Он указывает формат двоичного файла, используемый Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Файлы с расширением PPTM представляют собой файлы презентаций с поддержкой макросов, созданные с помощью Microsoft PowerPoint 2007 или более поздних версий. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Файлы с расширением PPTX представляют собой файлы презентаций, созданные с помощью популярного приложения Microsoft PowerPoint. В отличие от предыдущей версии формата файла презентации PPT, которая была двоичной, формат PPTX основан на формате файла презентации Microsoft PowerPoint open XML. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/pptx) . |

### Смотрите также

* class [FileType](../filetype)
* пространство имен [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
