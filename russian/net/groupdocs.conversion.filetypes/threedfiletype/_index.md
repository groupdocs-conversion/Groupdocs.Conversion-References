---
title: "ТипФайла3D"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет 3D документы Включает следующие типы Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb Узнайте больше о 3D форматах здесьhttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /ru/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Определяет 3D документы Включает следующие типы: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) Узнайте больше о 3D форматах [здесь](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Конструктор сериализации |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Файл AMF состоит из рекомендаций по описанию объектов для использования в процессах аддитивного производства. Он содержит открывающий тег XML и заканчивается элементом. Перед этим находится строка декларации XML, указывающая версию XML и кодировку файла. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Файл с расширением .ase — это формат экспорта сцен Autodesk ASCII, представляющий сцену в виде ASCII, содержащий 2D или 3D информацию при экспорте данных сцены с помощью Autodesk. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Файл DAE — это формат Digital Asset Exchange, используемый для обмена данными между интерактивными 3D приложениями. Этот формат основан на XML‑схеме COLLADA (COLLAborative Design Activity), которая является открытым стандартом XML‑схемы для обмена цифровыми активами между графическими программными приложениями. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Файл с расширением .drc — это сжатый 3D формат, созданный с помощью библиотеки Google Draco. Google предоставляет Draco как библиотеку с открытым исходным кодом для сжатия и распаковки 3D геометрических сеток и облаков точек, улучшая хранение и передачу 3D графики. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, — популярный 3D формат, изначально разработанный компанией Kaydara для MotionBuilder. В 2006 году его приобрела Autodesk Inc, и сейчас это один из основных форматов обмена 3D, используемый многими 3D инструментами. FBX доступен как в бинарном, так и в ASCII формате. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB — бинарное представление файлов 3D моделей, сохранённых в формате GL Transmission Format (glTF). Этот бинарный формат хранит ресурс glTF (JSON, .bin и изображения) в бинарном блобе. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) — 3D формат, который хранит информацию о 3D модели в формате JSON. Использование JSON уменьшает как размер 3D активов, так и время выполнения, необходимое для их распаковки и использования. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) — эффективный, ориентированный на промышленность и гибкий 3D формат данных, стандартизированный ISO, разработанный Siemens PLM Software. В областях механического CAD в аэрокосмической, автомобильной промышленности и тяжелом оборудовании JT используется как ведущий формат 3D визуализации. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | Файл с расширением .ma — 3D проектный файл, созданный в приложении Autodesk Maya. Он содержит большой список текстовых команд, задающих информацию о файле. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | Файл с расширением .mb — это бинарный проектный файл, созданный в приложении Autodesk Maya. В отличие от формата MA, который хранится в ASCII, файлы MB сохраняются в бинарном формате. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | Файлы OBJ используются приложением Advanced Visualizer от Wavefront для определения и хранения геометрических объектов. Обратная и прямая передача геометрических данных возможна с помощью файлов OBJ. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, представляет 3D‑формат файла, который хранит графические объекты, описанные как набор полигонов. Цель этого формата файла — создать простой и удобный тип файла, достаточно общий, чтобы быть полезным для широкого спектра моделей. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | Файлы данных RVM связаны с AVEVA PDMS. Файл RVM — это проектный файл модели системы управления проектированием заводов AVEVA (Plant Design Management System). Система управления проектированием заводов AVEVA (PDMS) является самым популярным 3D‑системой проектирования, использующей технологию, ориентированную на данные, для управления проектами. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Файл с расширением .3ds представляет собой формат файлов сетки 3D Studio (DOS), используемый Autodesk 3D Studio. Autodesk 3D Studio присутствует на рынке 3D‑форматов файлов с 1990‑х годов и теперь эволюционировал в 3D Studio MAX для работы с 3D‑моделированием, анимацией и рендерингом. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, используется приложениями для передачи 3D‑моделей объектов в различные другие приложения, платформы, сервисы и принтеры. Он был создан, чтобы избежать ограничений и проблем других 3D‑форматов файлов, таких как STL, при работе с новейшими версиями 3D‑принтеров. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) — это сжатый формат файла и структура данных для 3D‑компьютерной графики. Он содержит информацию о 3D‑модели, такую как треугольные сетки, освещение, затенение, данные движения, линии и точки с цветом и структурой. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Файл с расширением .usd — это формат Universal Scene Description, который кодирует данные для обмена и дополнения между приложениями создания цифрового контента. Разработанный Pixar, USD предоставляет возможность обмениваться элементарными ресурсами (например, моделями) или анимацией. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Файл с расширением .usdz — это несжатый и незашифрованный ZIP‑архив для формата USD (Universal Scene Description), который содержит и проксирует файлы других форматов (например, текстуры и анимации), встроенные в архив, и запускает их напрямую в среде выполнения USD без необходимости распаковки. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Virtual Reality Modeling Language (VRML) — это формат файла для представления интерактивных 3D‑объектов мира в сети World Wide Web (www). Он используется для создания трехмерных представлений сложных сцен, таких как иллюстрации, описания и презентации виртуальной реальности. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Файл с расширением .x относится к устаревшему формату файлов DirectX 3D Graphics, который был введён в Microsoft DirectX 2.0. Он использовался для рендеринга 3D‑графики в играх и определял структуры для сеток, текстур, анимаций и пользовательских объектов. С 2014 года он объявлен устаревшим, поскольку формат файлов Autodesk FBX лучше подходит как более современный формат. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/3d/x). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
