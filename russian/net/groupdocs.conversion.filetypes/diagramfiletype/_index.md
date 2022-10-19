---
title: DiagramFileType
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Определяет документы диаграммы. Включает следующие типы Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx .
type: docs
weight: 830
url: /ru/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Определяет документы диаграммы. Включает следующие типы: [`Vdw`](./vdw) , [`Vdx`](./vdx) , [`Vsd`](./vsd) , [`Vsdm`](./vsdm) , [`Vsdx`](./vsdx) , [`Vss`](./vss) , [`Vssm`](./vssm) , [`Vssx`](./vssx) , [`Vst`](./vst) , [`Vstm`](./vstm) , [`Vstx`](./vstx) , [`Vsx`](./vsx) , [`Vtx`](./vtx) .

```csharp
public sealed class DiagramFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Конструктор сериализации |

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
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW — это формат файла службы графики Visio, который указывает потоки и хранилища, необходимые для визуализации веб-рисунка. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/web/vdw) . |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Любой рисунок или диаграмма, созданные в Microsoft Visio, но сохраненные в формате XML, имеют расширение .VDX. XML-файл чертежа Visio создается в программном обеспечении Visio, разработанном Microsoft. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/vdx) . |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | Файлы VSD — это рисунки, созданные с помощью приложения Microsoft Visio для представления различных графических объектов и взаимосвязей между ними. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/vsd) . |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Файлы с расширением VSDM — это файлы чертежей, созданные с помощью приложения Microsoft Visio, которое поддерживает макросы. Файлы VSDM представляют собой чертежи OPC/XML, похожие на VSDX, но также обеспечивающие возможность запуска макросов при открытии файла. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Файлы с расширением .VSDX представляют формат файлов Microsoft Visio, появившийся в Microsoft Office 2013 и более поздних версиях. Он был разработан для замены двоичного формата файла .VSD, который поддерживается более ранними версиями Microsoft Visio. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS — это файлы шаблонов, созданные с помощью Microsoft Visio 2007 и более ранних версий. Файлы трафаретов предоставляют объекты чертежа, которые можно включить в чертеж .VSD Visio. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/vss) . |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Файлы с расширением .VSSM — это файлы Microsoft Visio Stencil, которые поддерживают макросы. Файл VSSM при открытии позволяет запускать макросы для достижения желаемого форматирования и размещения фигур на диаграмме. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/vssm) . |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Файлы с расширением .VSSX представляют собой наборы элементов для рисования, созданные с помощью Microsoft Visio 2013 и более поздних версий. Формат файла VSSX можно открыть с помощью Visio 2013 и более поздних версий. Файлы Visio известны тем, что представляют различные элементы рисования, такие как набор фигур, соединители, блок-схемы, макет сети, диаграммы UML, Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/vssx) . |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Файлы с расширением VST представляют собой файлы векторных изображений, созданные с помощью Microsoft Visio, и служат шаблоном для создания дополнительных файлов. Эти файлы шаблонов имеют двоичный формат и содержат макет и параметры по умолчанию, которые используются для создания новых чертежей Visio. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/image/vst) . |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Файлы с расширением VSTM представляют собой файлы шаблонов, созданные с помощью Microsoft Visio и поддерживающие макросы. В отличие от файлов VSDX, файлы, созданные из шаблонов VSTM, могут запускать макросы, разработанные в коде Visual Basic для приложений (VBA). Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/vstm) . |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Файлы с расширениями VSTX — это файлы шаблонов чертежей, созданные с помощью Microsoft Visio 2013 и более поздних версий. Эти файлы VSTX служат отправной точкой для создания рисунков Visio, сохраненных в виде файлов .VSDX, с макетом и настройками по умолчанию. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/vstx) . |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Файлы с расширением .VSX относятся к наборам элементов, состоящим из рисунков и фигур, которые используются для создания диаграмм в Microsoft Visio. Файлы VSX сохраняются в формате XML и поддерживались до Visio 2013. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/image/vsx) . |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Файл с расширением VTX представляет собой шаблон чертежа Microsoft Visio, который сохраняется на диск в формате файла XML. Шаблон предназначен для предоставления файла с основными настройками, который можно использовать для создания нескольких файлов Visio с одинаковыми настройками. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/vtx) . |

### Смотрите также

* class [FileType](../filetype)
* пространство имен [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
