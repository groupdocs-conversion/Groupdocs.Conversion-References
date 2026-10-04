---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет документы Diagram. Включает следующие типы Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /ru/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Определяет документы Diagram. Включает следующие типы: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Конструктор сериализации |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | Файл с расширением DRAWIO — это диаграмма, созданная в diagrams.net (ранее draw.io). Он хранится в формате XML с корневым элементом mxfile и содержит содержимое и форматирование элементов диаграммы, таких как текст, изображения, макет, фигуры и позиционирование. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/web/drawio). |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | Файл с расширением MMD — это диаграмма, написанная на языке разметки Mermaid. Он сохраняется как обычный текстовый документ, который начинается с объявления диаграммы, например flowchart или sequenceDiagram, за которым следует определение узлов и связей между ними. Узнайте больше о этом формате файла [здесь](https://mermaid.js.org/intro/). |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW — это формат файла Visio Graphics Service, который определяет потоки и хранилища, необходимые для рендеринга веб‑рисунка. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Любой рисунок или диаграмма, созданные в Microsoft Visio, но сохранённые в формате XML, имеют расширение .VDX. XML‑файл рисунка Visio создаётся в программном обеспечении Visio, разработанном Microsoft. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | Файлы VSD — это рисунки, созданные с помощью приложения Microsoft Visio для представления различных графических объектов и их взаимосвязей. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Файлы с расширением VSDM — это файлы чертежей, созданные приложением Microsoft Visio, которое поддерживает макросы. Файлы VSDM являются чертежами OPC/XML, похожими на VSDX, но также предоставляют возможность выполнять макросы при открытии файла. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Файлы с расширением .VSDX представляют формат файлов Microsoft Visio, введённый, начиная с Microsoft Office 2013. Он был разработан для замены бинарного формата файлов .VSD, поддерживаемого более ранними версиями Microsoft Visio. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS — это файлы шаблонов, созданные в Microsoft Visio 2007 и более ранних версиях. Файлы шаблонов предоставляют объекты чертежей, которые можно включать в чертёж Visio с расширением .VSD. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Файлы с расширением .VSSM — это файлы шаблонов Microsoft Visio, которые поддерживают макросы. При открытии файла VSSM позволяют выполнять макросы для достижения нужного форматирования и размещения фигур в диаграмме. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Файлы с расширением .VSSX — это шаблоны чертежей, созданные в Microsoft Visio 2013 и более новых версиях. Формат файлов VSSX можно открыть в Visio 2013 и выше. Файлы Visio известны представлением разнообразных элементов чертежа, таких как набор фигур, соединители, блок‑схемы, сетевые схемы, UML‑диаграммы. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Файлы с расширением VST — это векторные изображения, созданные в Microsoft Visio и используемые как шаблоны для создания последующих файлов. Эти шаблонные файлы находятся в бинарном формате и содержат макет и настройки по умолчанию, которые используются при создании новых чертежей Visio. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Файлы с расширением VSTM — это шаблоны, созданные в Microsoft Visio и поддерживающие макросы. В отличие от файлов VSDX, файлы, созданные из шаблонов VSTM, могут выполнять макросы, разработанные на языке Visual Basic for Applications (VBA). Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Файлы с расширением VSTX — это шаблоны чертежей, созданные в Microsoft Visio 2013 и более новых версиях. Эти файлы VSTX предоставляют отправную точку для создания чертежей Visio, сохраняемых как файлы .VSDX, с макетом и настройками по умолчанию. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Файлы с расширением .VSX относятся к шаблонам, содержащим чертежи и фигуры, используемые для создания диаграмм в Microsoft Visio. Файлы VSX сохраняются в формате XML и поддерживались до Visio 2013. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Файл с расширением VTX — это шаблон чертежа Microsoft Visio, сохраняемый на диск в формате XML. Шаблон предназначен для предоставления файла с базовыми настройками, которые можно использовать для создания нескольких файлов Visio с одинаковыми параметрами. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/vtx). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
