---
title: "Класс GisFileType"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Определения типов GIS‑документов."
type: docs
url: /ru/python-net/groupdocs.conversion.filetypes/gisfiletype/
is_root: false
weight: 110
---


## GisFileType class

Определения типов GIS‑документов.

Включает следующие типы файлов: [`GisFileType.shp`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/), [`GisFileType.geo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/), [`GisFileType.gdb`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/), [`GisFileType.gml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/), [`GisFileType.kml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/), [`GisFileType.gpx`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/), [`GisFileType.topo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/), [`GisFileType.osm`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/).

Тип GisFileType раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/__init__/) | Инициализирует GisFileType для сериализации. |

### Методы
| Метод | Описание |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Сравнивает текущий объект с другим. (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Реализует сравнение на равенство, определённое в [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Получает FileType для указанного расширения файла. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Возвращает FileType для указанного file_name. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Возвращает FileType для предоставленного потока документа. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Предоставляет функцию хеширования по умолчанию. (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Строковое представление типа файла. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | Описание типа файла. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | Расширение файла. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | Семейство файлов. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Формат файла. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [SHP](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/) | SHP — это расширение файла для одного из основных типов файлов, используемых для представления ESRI Shapefile. Он представляет геопространственную информацию в виде векторных данных, которые могут использоваться приложениями Географических Информационных Систем (GIS). Узнайте больше об этом формате файла здесь. |
| [GEO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/) | GeoJSON — это основанный на JSON формат, предназначенный для представления географических объектов с их несущностными атрибутами. Этот формат определяет различные объекты JSON (JavaScript Object Notation) и их способ объединения. Формат JSON представляет совокупную информацию о географических объектах, их пространственных границах и свойствах. Узнайте больше об этом формате файла здесь. |
| [GDB](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/) | Файловая геобаза данных ESRI (FileGDB) представляет собой набор файлов в папке на диске, содержащих связанные геопространственные данные, такие как наборы объектов, классы объектов и связанные таблицы. Для её работы требуется хранить определённые другие файлы рядом с файлом .gdb в том же каталоге. Узнайте больше об этом формате файла здесь. |
| [GML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/) | GML расшифровывается как Geography Markup Language и основан на спецификациях XML, разработанных Open Geospatial Consortium (OGC). Этот формат используется для хранения географических данных для обмена между различными файловыми форматами. Он служит как язык моделирования географических систем, а также как открытый формат обмена географическими транзакциями в интернете. Узнайте больше об этом формате файла здесь. |
| [KML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/) | KML (Keyhole Markup Language) содержит геопространственную информацию в нотации XML. Файлы, сохранённые как KML, могут открываться в приложениях Географических Информационных Систем (GIS), при условии их поддержки. Многие приложения начали поддерживать формат KML после того, как он был принят в качестве международного стандарта. KML использует теговую структуру с вложенными элементами и атрибутами. Узнайте больше об этом формате файла здесь. |
| [GPX](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/) | Файлы с расширением GPX представляют формат GPS Exchange для обмена GPS‑данными между приложениями и веб‑сервисами в интернете. Это лёгкий XML‑формат, содержащий GPS‑данные, то есть контрольные точки, маршруты и треки, которые могут импортироваться и читаться множеством программ. Узнайте больше об этом формате файла здесь. |
| [TOPO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/) | TopoJSON — это расширение GeoJSON, которое кодирует топологию. Вместо представления геометрий отдельно, геометрии в файлах TopoJSON собираются из общих линейных сегментов, называемых дугами. |
| [OSM](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/) | Формат файла OSM — это структурированный формат данных, используемый для хранения географических данных в проекте OpenStreetMap. Файлы OSM обычно находятся в формате XML и содержат информацию, такую как расположение дорог, зданий, достопримечательностей и других объектов на карте. Узнайте больше об этом формате файла здесь. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Неизвестный тип файла (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### См. также
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
