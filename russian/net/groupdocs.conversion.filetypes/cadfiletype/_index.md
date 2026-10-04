---
title: "CadFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет CAD‑документы (Computer Aided Design), которые используются для форматов файлов 3D‑графики и могут содержать 2D или 3D‑проекты. Включает следующие типы Cf2./cadfiletype/cf2 Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfx Dwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. Узнайте больше о форматах CAD здесьhttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /ru/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Определяет CAD‑документы (Computer Aided Design), которые используются для форматов файлов 3D‑графики и могут содержать 2D или 3D‑проекты. Включает следующие типы: [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). Узнайте больше о форматах CAD [здесь](https://wiki.fileformat.com/cad).

```csharp
public sealed class CadFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CadFileType](cadfiletype)() | Конструктор сериализации |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Общий файл формата. CAD‑файл, содержащий 3D‑пакетные проекты или другие данные модели; может обрабатываться и резаться машиной CAD/CAM, такой как устройство для вырубки штампов. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | Файлы DGN, Design, представляют собой чертежи, созданные и поддерживаемые CAD‑приложениями, такими как MicroStation и Intergraph Interactive Graphics Design System. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/cad/dgn). |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) представляет собой 2D/3D‑чертеж в сжатом формате для просмотра, рецензирования или печати файлов дизайна. Он содержит графику и текст как часть данных проекта и уменьшает размер файла благодаря сжатому формату. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/cad/dwf). |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | Файл DWFX — это 2D или 3D чертеж, созданный с помощью программного обеспечения Autodesk CAD. Он сохраняется в формате DWFx, который похож на файл .DWF, но оформлен с использованием спецификации XML Paper Specification (XPS) от Microsoft. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Файлы с расширением DWG представляют собой проприетарные бинарные файлы, используемые для хранения 2D и 3D данных дизайна. Как и DXF, которые являются ASCII‑файлами, DWG представляют бинарный формат файлов для чертежей CAD (Computer Aided Design). Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Файл DWT — это шаблон чертежа AutoCAD, который используется в качестве отправной точки для создания чертежей, которые могут сохраняться как файлы DWG. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, или Drawing Exchange Format, представляет собой тегированное представление данных файла чертежа AutoCAD. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Файлы с расширением IFC относятся к формату файлов Industry Foundation Classes (IFC), который устанавливает международные стандарты для импорта и экспорта строительных объектов и их свойств. Этот формат файлов обеспечивает совместимость между различными программными приложениями. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Формат документа Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Формат файла PLT — это векторный файл плоттера, представленный компанией Autodesk, Inc., и содержащий информацию для определённого файла CAD. Детали построения требуют точности и прецизионности в производстве, а использование файла PLT гарантирует это, поскольку все изображения печатаются линиями, а не точками. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, сокращение от stereolithrography, представляет собой взаимозаменяемый формат файла, который описывает трёхмерную поверхность. Этот формат файла используется в нескольких областях, таких как быстрое прототипирование, 3D‑печать и компьютерное производство. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/cad/stl). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
