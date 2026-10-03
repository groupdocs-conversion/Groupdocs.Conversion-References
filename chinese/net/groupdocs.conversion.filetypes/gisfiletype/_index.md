---
title: "GisFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义 GIS 文档。包括以下文件类型 Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /zh/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

定义 GIS 文档。包括以下文件类型：[`Shp`](./shp)。[`GeoJson`](./geojson)。[`GeoJsonSeq`](./geojsonseq)。[`Gdb`](./gdb)。[`Gml`](./gml)。[`Kml`](./kml)。[`Kmz`](./kmz)。[`Gpx`](./gpx)。[`TopoJson`](./topojson)。[`Osm`](./osm)。

```csharp
public sealed class GisFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GisFileType](gisfiletype)() | 序列化构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 文件类型描述 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 文件扩展名 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 文件族 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 文件格式 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 实现 [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 充当默认的哈希函数。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 字符串表示 |

## Fields

| 名称 | 描述 |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | ESRI 文件地理数据库（FileGDB）是一组存放在磁盘文件夹中的文件，保存相关的地理空间数据，如要素数据集、要素类和关联表。它需要将其他特定文件与 .gdb 文件一起保存在同一目录中才能正常工作。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/database/gdb/)。 |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON 是一种基于 JSON 的格式，旨在表示具有非空间属性的地理要素。该格式定义了不同的 JSON（JavaScript Object Notation）对象及其关联方式。JSON 格式呈现关于地理要素、其空间范围和属性的综合信息。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/gis/geojson/)。 |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON 文本序列是一系列独立的 GeoJSON 记录流，而不是单个封闭文档，每条记录由换行符或 RS 控制字符分隔。它用于随时间追加的馈送，在写入开始时集合的结束未知。 |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML 代表地理标记语言（Geography Markup Language），基于由开放地理空间联盟（OGC）制定的 XML 规范。该格式用于存储地理数据要素，以便在不同文件格式之间进行交换。它既是地理系统的建模语言，也是互联网地理交易的开放交换格式。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/gis/gml/)。 |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | 扩展名为 GPX 的文件代表 GPS 交换格式，用于在应用程序和互联网 Web 服务之间交换 GPS 数据。它是一种轻量级的 XML 文件格式，包含 GPS 数据，如航点、路线和轨迹，可被多个程序导入和读取。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/gis/gpx/)。 |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML（Keyhole Markup Language）以 XML 形式包含地理空间信息。保存为 KML 的文件可以在支持的地理信息系统（GIS）应用程序中打开。自从 KML 被采纳为国际标准后，许多应用程序开始支持 KML 文件格式。KML 使用基于标签的结构，包含嵌套元素和属性。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/gis/kml/)。 |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ 是一种 ZIP 存档，携带 KML 文档，约定在存档根目录下命名为 doc.kml，并包含文档引用的任何资源。压缩标记是其要点：任何大小的 KML 源会显著缩小，这也是发布者分发 KMZ 而非 KML 的原因。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | OSM 文件格式是一种结构化数据格式，用于在 OpenStreetMap 项目中存储地理数据。OSM 文件通常为 XML 格式，包含道路、建筑物、兴趣点以及地图上其他要素的位置等信息。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP 是用于表示 ESRI Shapefile 的主要文件类型之一的文件扩展名。它以矢量数据的形式表示地理空间信息，可供地理信息系统（GIS）应用使用。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON 是 GeoJSON 的扩展，用于编码拓扑结构。与离散表示几何形状不同，TopoJSON 文件中的几何形状是由称为弧的共享线段拼接而成。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
