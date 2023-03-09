---
title: CadFileType
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Определяет документы САПР автоматизированное проектирование которые используются для форматов файлов 3Dграфики и могут содержать 2D или 3Dпроекты. Включает следующие типы Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . Подробнее о форматах САПРздесьhttps//wiki.fileformat.com/cad .
type: docs
weight: 860
url: /ru/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Определяет документы САПР (автоматизированное проектирование), которые используются для форматов файлов 3D-графики и могут содержать 2D- или 3D-проекты. Включает следующие типы: [`Cf2`](./cf2)[`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwfx`](./dwfx)[`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . Подробнее о форматах САПР[здесь](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CadFileType](cadfiletype)() | Конструктор сериализации |

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
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Определяет, равны ли два экземпляра объекта. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит хеш-функцией по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Файл общего формата файла. Файл САПР, содержащий чертежи 3D-пакетов или другие данные модели; могут быть обработаны и вырезаны на станке CAD/CAM, таком как устройство для высечки. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | Файлы DGN, Design — это чертежи, созданные и поддерживаемые приложениями САПР, такими как MicroStation и Intergraph Interactive Graphics Design System. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) представляет собой 2D/3D-чертеж в сжатом формате для просмотра, просмотра или печати файлов проекта. Он содержит графику и текст как часть проектных данных и уменьшает размер файла из-за его сжатого формата. Узнайте больше об этом формате файла.[здесь](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | Файл DWFX представляет собой 2D- или 3D-чертеж, созданный с помощью программного обеспечения Autodesk CAD. Он сохраняется в формате DWFx, похожем на файл . DWF, но отформатирован с использованием Microsoft XML Paper Specification (XPS). |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Файлы с расширением DWG представляют собой проприетарные двоичные файлы, используемые для хранения данных 2D- и 3D-проектирования. Как и DXF, которые являются файлами ASCII, DWG представляет собой двоичный формат файла для чертежей CAD (автоматизированного проектирования). Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Файл DWT — это файл шаблона чертежа AutoCAD, который используется в качестве основы для создания чертежей, которые можно сохранить в виде файлов DWG. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, формат обмена чертежами или формат обмена чертежами — это теговое представление данных файла чертежа AutoCAD. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Файлы с расширением IFC относятся к формату файлов Industry Foundation Classes (IFC), который устанавливает международные стандарты для импорта и экспорта строительных объектов и их свойств. Этот формат файла обеспечивает взаимодействие между различными программными приложениями. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Формат документа IGs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Формат файла PLT представляет собой векторный файл плоттера, представленный Autodesk, Inc., и содержит информацию для определенного файла САПР. Детали чертежа требуют точности и аккуратности при производстве, и использование файла PLT гарантирует это, поскольку все изображения печатаются с использованием линий, а не точек. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, сокращение от стереолитографии, представляет собой взаимозаменяемый формат файла, представляющий трехмерную геометрию поверхности. Формат файла находит свое применение в нескольких областях, таких как быстрое прототипирование, 3D-печать и автоматизированное производство. Узнайте больше об этом формате файла.[здесь](https://wiki.fileformat.com/cad/stl) . |

### Смотрите также

* class [FileType](../filetype)
* пространство имен [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
