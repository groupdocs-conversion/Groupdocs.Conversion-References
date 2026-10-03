---
title: "CadFileType"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Определяет CAD‑документы (Computer Aided Design), которые используются для форматов файлов 3D‑графики и могут содержать 2D или 3D‑проекты."
type: docs
weight: 11
url: /ru/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

Определяет CAD‑документы (Computer Aided Design), которые используются для форматов файлов 3D‑графики и могут содержать 2D или 3D‑дизайны.
Включает следующие типы:
[Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype#Dgn),
[Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwf),
[Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwg),
[Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwt),
[Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dxf),
[Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype#Ifc),
[Igs](../../com.groupdocs.conversion.filetypes/cadfiletype#Igs),
[Plt](../../com.groupdocs.conversion.filetypes/cadfiletype#Plt),
[Stl](../../com.groupdocs.conversion.filetypes/cadfiletype#Stl).
[Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype#Cf2).
[Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwfx).
Узнайте больше о форматах CAD [здесь](../https://wiki.fileformat.com/cad).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | Конструктор сериализации |
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [Dxf](#Dxf) | DXF (Drawing Interchange Format или Drawing Exchange Format) — это тегированное представление данных файла чертежа AutoCAD. |
|
|  | [Dwg](#Dwg) | Файлы с расширением DWG представляют собой проприетарные бинарные файлы, используемые для хранения 2D и 3D данных дизайна. |
|
|  | [Dgn](#Dgn) | DGN (Design) — файлы чертежей, создаваемые и поддерживаемые CAD‑приложениями, такими как MicroStation и Intergraph Interactive Graphics Design System. |
|
|  | [Dwf](#Dwf) | Design Web Format (DWF) представляет 2D/3D чертеж в сжатом формате для просмотра, рецензирования или печати файлов дизайна. |
|
|  | [Stl](#Stl) | STL, сокращение от stereolithography, — взаимозаменяемый формат файла, представляющий трехмерную геометрию поверхности. |
|
|  | [Ifc](#Ifc) | Файлы с расширением IFC относятся к формату Industry Foundation Classes (IFC), который устанавливает международные стандарты импорта и экспорта строительных объектов и их свойств. |
|
|  | [Plt](#Plt) | Формат файла PLT — это векторный файл плоттера, представленный компанией Autodesk, Inc. |
|
|  | [Igs](#Igs) | Формат документа Igs |
|
|  | [Dwt](#Dwt) | Файл DWT — это шаблон чертежа AutoCAD, используемый в качестве отправной точки для создания чертежей, которые могут быть сохранены как файлы DWG. |
|
|  | [Dwfx](#Dwfx) | Файл DWFX — это 2D или 3D чертеж, созданный с помощью программного обеспечения Autodesk CAD. |
|
|  | [Cf2](#Cf2) | Файл Common File Format. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Конструктор сериализации


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF (Drawing Interchange Format или Drawing Exchange Format) — это тегированное представление данных файла чертежа AutoCAD.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dxf).


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


Файлы с расширением DWG представляют собой проприетарные бинарные файлы, используемые для хранения 2D и 3D данных дизайна. Как и DXF, который является ASCII‑файлом, DWG представляет бинарный формат файлов CAD (Computer Aided Design) чертежей.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dwg)


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN (Design) — файлы чертежей, создаваемые и поддерживаемые CAD‑приложениями, такими как MicroStation и Intergraph Interactive Graphics Design System.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dgn).


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) представляет 2D/3D чертеж в сжатом формате для просмотра, рецензирования или печати файлов дизайна. Он содержит графику и текст как часть данных дизайна и уменьшает размер файла благодаря сжатию.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, аббревиатура от стереолитографии, является взаимозаменяемым форматом файла, представляющим трехмерную поверхностную геометрию. Этот формат файла используется в нескольких областях, таких как быстрое прототипирование, 3D‑печать и компьютерное производство.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


Файлы с расширением IFC относятся к формату файлов Industry Foundation Classes (IFC), который устанавливает международные стандарты для импорта и экспорта строительных объектов и их свойств. Этот формат файла обеспечивает совместимость между различными программными приложениями.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


Формат файла PLT — векторный файл плоттера, представленный компанией Autodesk, Inc., и содержит информацию для определенного CAD‑файла. Детали построения требуют точности и прецизионности в производстве, и использование файла PLT гарантирует это, поскольку все изображения печатаются линиями, а не точками.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Формат документа Igs


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


Файл DWT — это шаблон чертежа AutoCAD, используемый в качестве отправной точки для создания чертежей, которые могут быть сохранены как файлы DWG.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


Файл DWFX — это 2D или 3D чертеж, созданный с помощью программного обеспечения Autodesk CAD. Он сохраняется в формате DWFx, который похож на файл .DWF, но оформлен с использованием XML Paper Specification (XPS) от Microsoft.


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Файл Common File Format. CAD‑файл, содержащий 3D‑пакетные конструкции или другие данные модели; может обрабатываться и резаться машиной CAD/CAM, такой как устройство для вырубки штампов.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Подготовлены параметры загрузки по умолчанию для исходного типа файла


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Подготовлены параметры конвертации по умолчанию для типа файла


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
