---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет форматы файлов презентаций, которые хранят коллекцию записей для размещения данных презентации, таких как слайды, фигуры, текст, анимации, видео, аудио и встроенные объекты. Включает следующие типы файлов Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. Узнайте больше о форматах презентаций здесьhttps//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /ru/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Определяет форматы файлов презентаций, которые хранят коллекцию записей для размещения данных презентации, таких как слайды, фигуры, текст, анимации, видео, аудио и встроенные объекты. Включает следующие типы файлов: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). Узнайте больше о форматах презентаций [здесь](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Конструктор сериализации |

## Свойства

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Семейство файлов |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Реализует [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Файлы с расширением FODP представляют собой презентацию OpenDocument Flat XML. Файл презентации сохраняется в формате OpenDocument, но использует плоский XML-формат вместо контейнера .ZIP, используемого в стандартных файлах .ODP. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Файлы с расширением ODP представляют формат файлов презентаций, используемый OpenOffice.org в стандарте OASIS Open. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Файлы с расширением .OTP представляют шаблоны презентаций, созданные приложениями в формате стандарта OASIS OpenDocument. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Файлы с расширением .POT представляют шаблоны файлов Microsoft PowerPoint, созданные версиями PowerPoint 97‑2003. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Файлы с расширением POTM — это шаблоны Microsoft PowerPoint с поддержкой макросов. Файлы POTM создаются в PowerPoint 2007 и более новых версиях и содержат настройки по умолчанию, которые можно использовать для создания последующих файлов презентаций. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Файлы с расширением .POTX представляют шаблоны презентаций Microsoft PowerPoint, созданные в Microsoft PowerPoint 2007 и более новых версиях. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint Slide Show, файлы создаются с помощью Microsoft PowerPoint для целей слайд-шоу. Чтение и создание файлов PPS поддерживается Microsoft PowerPoint 97‑2003. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Файлы с расширением PPSM представляют формат файлов слайд-шоу с поддержкой макросов, созданный в Microsoft PowerPoint 2007 или более новых версиях. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, Power Point Slide Show, файлы создаются с помощью Microsoft PowerPoint 2007 и более новых версий для целей слайд-шоу. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Файл с расширением PPT представляет файл PowerPoint, содержащий коллекцию слайдов для отображения в виде слайд-шоу. Он определяет двоичный формат файла, используемый Microsoft PowerPoint 97‑2003. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Файлы с расширением PPTM — это презентации с поддержкой макросов, созданные в Microsoft PowerPoint 2007 и более новых версиях. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Файлы с расширением PPTX являются презентационными файлами, созданными с помощью популярного приложения Microsoft PowerPoint. В отличие от предыдущей версии формата презентационных файлов PPT, который был бинарным, формат PPTX основан на открытом XML-формате презентаций Microsoft PowerPoint. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/presentation/pptx). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
