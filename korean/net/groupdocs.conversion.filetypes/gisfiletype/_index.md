---
title: "GisFileType"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "GIS 문서를 정의합니다. 다음 파일 유형을 포함합니다 Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /ko/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

GIS 문서를 정의합니다. 다음 파일 유형을 포함합니다: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GisFileType](gisfiletype)() | 직렬화 생성자 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 파일 유형 설명 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 파일 확장자 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 파일 패밀리 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 파일 형식 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 현재 객체를 다른 객체와 비교합니다. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | `[`Equals`](../../groupdocs.conversion.contracts/enumeration/equals)`를 구현합니다. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 기본 해시 함수로 사용됩니다. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 문자열 표현 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | ESRI 파일 Geodatabase(FileGDB)는 폴더에 있는 파일들의 모음으로, 피처 데이터셋, 피처 클래스 및 관련 테이블과 같은 관련 지리공간 데이터를 보관합니다. 이 파일이 작동하려면 .gdb 파일과 함께 동일한 디렉터리에 특정 다른 파일들을 함께 보관해야 합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/database/gdb/)를 클릭하세요. |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON은 지리적 특징과 비공간 속성을 표현하도록 설계된 JSON 기반 형식입니다. 이 형식은 다양한 JSON(JavaScript Object Notation) 객체와 그 결합 방식을 정의합니다. JSON 형식은 지리적 특징, 공간 범위 및 속성에 대한 종합 정보를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/gis/geojson/)를 클릭하세요. |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON 텍스트 시퀀스는 하나의 포괄적인 문서가 아니라 독립적인 GeoJSON 레코드들의 스트림이며, 각 레코드는 새 줄이나 RS 제어 문자로 구분됩니다. 이는 시간이 지남에 따라 추가되는 피드에 사용되며, 기록이 시작될 때 컬렉션의 끝이 알려지지 않은 경우에 활용됩니다. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML은 Open Geospatial Consortium(OGC)에서 개발한 XML 사양을 기반으로 하는 Geography Markup Language의 약자입니다. 이 형식은 다양한 파일 형식 간에 지리 데이터 특징을 교환하기 위해 사용됩니다. 또한 지리 시스템을 모델링하는 언어이자 인터넷상의 지리 거래를 위한 개방형 교환 형식으로 활용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/gis/gml/)를 클릭하세요. |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | GPX 확장자를 가진 파일은 애플리케이션 및 웹 서비스 간에 GPS 데이터를 교환하기 위한 GPS Exchange 형식을 나타냅니다. 이는 경유지, 경로 및 트랙과 같은 GPS 데이터를 포함하는 경량 XML 파일 형식으로, 여러 프로그램에서 가져오고 읽을 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/gis/gpx/)를 클릭하세요. |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML(Keyhole Markup Language)은 XML 표기법으로 지리 정보를 포함합니다. KML로 저장된 파일은 해당 기능을 지원하는 GIS(Geographic Information System) 애플리케이션에서 열 수 있습니다. 국제 표준으로 채택된 이후 많은 애플리케이션이 KML 파일 형식을 지원하기 시작했습니다. KML은 중첩 요소와 속성을 갖는 태그 기반 구조를 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/gis/kml/)를 클릭하세요. |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ는 KML 문서를 포함하는 ZIP 압축 파일이며, 관례적으로 아카이브 루트에 doc.kml이라는 이름으로 저장되고 문서가 참조하는 모든 리소스를 함께 포함합니다. 마크업을 압축하는 것이 핵심이며, 크기에 관계없이 KML 피드가 크게 축소되기 때문에 게시자는 KML보다 KMZ를 배포합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/gis/kmz/)를 클릭하십시오. |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | OSM 파일 형식은 OpenStreetMap 프로젝트에서 지리 데이터를 저장하는 데 사용되는 구조화된 데이터 형식입니다. OSM 파일은 일반적으로 XML 형식이며 도로, 건물, 관심 지점 및 지도상의 기타 특징 위치와 같은 정보를 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/gis/osm/)를 클릭하십시오. |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP는 ESRI Shapefile을 나타내는 주요 파일 유형 중 하나의 파일 확장자입니다. 이는 지리 정보 시스템(GIS) 애플리케이션에서 사용되는 벡터 데이터 형태의 지리공간 정보를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/gis/shp/)를 클릭하십시오. |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON은 토폴로지를 인코딩하는 GeoJSON의 확장입니다. 기하학을 개별적으로 표현하는 대신, TopoJSON 파일의 기하학은 arcs라고 불리는 공유 선분을 결합하여 구성됩니다. |

### 또 보기

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
