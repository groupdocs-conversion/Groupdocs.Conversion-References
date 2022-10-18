---
title: ThreeDFileType
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Определяет 3Dдокументы Включает следующие типы Fbx./threedfiletype/fbx Узнайте больше о форматах 3Dздесьhttps//wiki.fileformat.com/3d .
type: docs
weight: 940
url: /ru/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Определяет 3D-документы Включает следующие типы: [`Fbx`](./fbx) Узнайте больше о форматах 3D[здесь](https://wiki.fileformat.com/3d) .

```csharp
public sealed class ThreeDFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Конструктор сериализации |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Файл AMF содержит рекомендации по описанию объектов, которые должны использоваться в процессах аддитивного производства. Он содержит открывающий тег XML и заканчивается элементом. Этому предшествует строка объявления XML, в которой указывается версия XML и кодировка файла. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Файл с расширением .ase представляет собой формат файла Autodesk ASCII Scene Export, представляющий собой ASCII-представление сцены, содержащее 2D- или 3D-информацию при экспорте данных сцены с помощью Autodesk. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Файл DAE представляет собой формат файла обмена цифровыми активами, который используется для обмена данными между интерактивными 3D-приложениями. Этот формат файла основан на XML-схеме COLLADA (COLLAborative Design Activity), которая представляет собой открытую стандартную XML-схему для обмена цифровыми активами между графическими приложениями. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Файл с расширением .drc представляет собой сжатый формат 3D-файла, созданный с помощью библиотеки Google Draco. Google предлагает Draco в качестве библиотеки с открытым исходным кодом для сжатия и распаковки трехмерных геометрических сеток и облаков точек, а также для улучшения хранения и передачи трехмерной графики. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox — популярный формат 3D-файлов, изначально разработанный Kaydara для MotionBuilder. Он был приобретен Autodesk Inc в 2006 году и в настоящее время является одним из основных форматов обмена 3D-данными, который используется во многих 3D-инструментах. FBX доступен как в двоичном формате, так и в формате ASCII. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (формат передачи GL) — это формат файла 3D, в котором информация о 3D-модели хранится в формате JSON. Использование JSON минимизирует как размер 3D-ресурсов, так и время выполнения, необходимое для распаковки и использования этих ресурсов. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) — это эффективный, отраслевой и гибкий формат 3D-данных, соответствующий стандарту ISO, разработанный Siemens PLM Software. Механические области САПР аэрокосмической, автомобильной промышленности и тяжелого оборудования используют JT как наиболее популярный формат 3D-визуализации. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | Файлы OBJ используются приложением Wavefront Advanced Visualizer для определения и хранения геометрических объектов. Обратная и прямая передача геометрических данных возможна через файлы OBJ. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, формат файла многоугольника, представляет формат файла 3D, в котором хранятся графические объекты, описываемые как набор многоугольников. Цель этого формата файла состояла в том, чтобы установить простой и удобный тип файла, который является достаточно общим, чтобы его можно было использовать для широкого спектра моделей. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | Файлы данных RVM относятся к AVEVA PDMS. Файл RVM представляет собой файл проекта AVEVA Plant Design Management System Model. Система управления проектированием предприятий AVEVA (PDMS) — самая популярная система 3D-проектирования, использующая технологию, ориентированную на данные, для управления проектами. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Файл с расширением .3ds представляет формат файла сетки 3D Sudio (DOS), используемый Autodesk 3D Studio. Autodesk 3D Studio существует на рынке форматов 3D-файлов с 1990-х годов и теперь превратилась в 3D Studio MAX для работы с 3D-моделированием, анимацией и визуализацией. Узнайте больше об этом формате файлов.[здесь](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, формат 3D-производства, используется приложениями для рендеринга 3D-моделей объектов для множества других приложений, платформ, сервисов и принтеров. Он был создан, чтобы избежать ограничений и проблем, связанных с другими форматами 3D-файлов, такими как STL, для работы с последними версиями 3D-принтеров. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) — это сжатый формат файла и структура данных для трехмерной компьютерной графики. Он содержит информацию о 3D-модели, такую как треугольные сетки, освещение, затенение, данные о движении, линии и точки с цветом и структурой. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Файл с расширением .usd является универсальным форматом файла описания сцены, который кодирует данные для обмена данными и дополнения между приложениями для создания цифрового контента. Разработанный Pixar, файл USD позволяет обмениваться элементарными активами (например, моделями) или анимацией. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Файл с расширением .usdz представляет собой несжатый и незашифрованный ZIP-архив для формата файлов USD (Universal Scene Description), который содержит и прокси для файлов других форматов (например, текстур и анимаций), встроенных в архив, и запускает их непосредственно с помощью Время выполнения в долларах США без необходимости распаковки. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Язык моделирования виртуальной реальности (VRML) — это файловый формат для представления интерактивных трехмерных объектов мира через World Wide Web (www). Он находит свое применение в создании трехмерных представлений сложных сцен, таких как иллюстрации, определение и презентации виртуальной реальности. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Файл с расширением .x относится к устаревшему формату файла 3D-графики DirectX, который был представлен в Microsoft DirectX 2.0. Он использовался для рендеринга 3D-графики в играх и определяет структуры для сеток, текстур, анимации и пользовательских объектов. Он устарел с 2014 года, поскольку формат файла Autodesk FBX лучше подходит как более современный формат. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/3d/x) . |

### Смотрите также

* class [FileType](../filetype)
* пространство имен [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
