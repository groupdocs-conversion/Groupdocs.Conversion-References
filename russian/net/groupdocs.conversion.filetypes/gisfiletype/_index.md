---
title: "GisFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет GIS‑документы. Включает следующие типы файлов Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /ru/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

Определяет GIS‑документы. Включает следующие типы файлов: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GisFileType](gisfiletype)() | Конструктор сериализации |

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
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | ESRI‑файл Geodatabase (FileGDB) — это набор файлов в папке на диске, содержащих связанные геопространственные данные, такие как наборы наборов объектов, классы объектов и связанные таблицы. Для его работы необходимо хранить рядом с файлом .gdb определённые другие файлы в том же каталоге. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON — это основанный на JSON формат, предназначенный для представления географических объектов с их не пространственными атрибутами. Этот формат определяет различные объекты JSON (JavaScript Object Notation) и способ их объединения. Формат JSON представляет совокупную информацию о географических объектах, их пространственных охватах и свойствах. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON Text Sequence — это поток независимых записей GeoJSON, а не один охватывающий документ; каждая запись разделяется переводом строки или управляющим символом RS. Он используется для потоков, к которым со временем добавляются данные, когда конец коллекции неизвестен в момент начала записи. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML расшифровывается как Geography Markup Language и основан на спецификациях XML, разработанных Open Geospatial Consortium (OGC). Формат используется для хранения геоданных и их обмена между различными форматами файлов. Он служит как язык моделирования географических систем, так и открытый формат обмена географическими транзакциями в интернете. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | Файлы с расширением GPX представляют формат GPS Exchange для обмена GPS‑данными между приложениями и веб‑сервисами в интернете. Это лёгкий XML‑формат, содержащий GPS‑данные, такие как контрольные точки, маршруты и треки, которые могут импортироваться и читаться несколькими программами. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) содержит геопространственную информацию в XML‑нотации. Файлы, сохранённые как KML, можно открыть в приложениях Geographic Information System (GIS), при условии их поддержки. Многие приложения начали поддерживать формат KML после его признания международным стандартом. KML использует теговую структуру с вложенными элементами и атрибутами. Узнайте больше о этом формате файлов [здесь](https://docs.fileformat.com/gis/kml/). |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ — это ZIP‑архив, содержащий документ KML, по соглашению названный doc.kml в корне архива, вместе с любыми ресурсами, на которые ссылается документ. Сжатие разметки — цель: любой KML‑канал значительно уменьшается в размере, поэтому издатели распространяют KMZ вместо KML. Узнайте больше о этом формате файлов [здесь](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | Формат файлов OSM — это структурированный формат данных, используемый для хранения географических данных в проекте OpenStreetMap. Файлы OSM обычно находятся в формате XML и содержат информацию, такую как расположение дорог, зданий, достопримечательностей и других объектов на карте. Узнайте больше о этом формате файлов [здесь](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP — это расширение файла для одного из основных типов файлов, используемых для представления ESRI Shapefile. Он представляет геопространственную информацию в виде векторных данных, которые могут использоваться приложениями Geographic Information Systems (GIS). Узнайте больше о этом формате файлов [здесь](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON — это расширение GeoJSON, которое кодирует топологию. Вместо отдельного представления геометрий, геометрии в файлах TopoJSON собираются из общих линейных сегментов, называемых дугами. |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
