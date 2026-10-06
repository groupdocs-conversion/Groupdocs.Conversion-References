---
title: "GisFileType 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "GIS 문서 유형 정의입니다."
type: docs
url: /ko/python-net/groupdocs.conversion.filetypes/gisfiletype/
is_root: false
weight: 110
---


## GisFileType class

GIS 문서 유형 정의입니다.

다음 파일 형식을 포함합니다: [`GisFileType.shp`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/), [`GisFileType.geo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/), [`GisFileType.gdb`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/), [`GisFileType.gml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/), [`GisFileType.kml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/), [`GisFileType.gpx`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/), [`GisFileType.topo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/), [`GisFileType.osm`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/).

GisFileType 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/__init__/) | 직렬화를 위해 GisFileType을 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | 현재 객체를 다른 객체와 비교합니다. ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/)에 정의된 동등성 비교를 구현합니다. (`[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (`[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | 제공된 파일 확장자에 대한 FileType을 가져옵니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | 지정된 file_name에 대한 FileType을 반환합니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | 제공된 문서 스트림에 대한 FileType을 반환합니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (`[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | 기본 해시 함수를 제공합니다. ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | 파일 유형의 문자열 표현입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | 파일 유형 설명입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | 파일 확장자입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | 파일 패밀리입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | 파일 형식입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### 필드
| 필드 | 설명 |
| :- | :- |
| [SHP](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/) | SHP는 ESRI Shapefile을 표현하는 주요 파일 형식 중 하나의 파일 확장자이며, 지리 정보 시스템(GIS) 애플리케이션에서 사용되는 벡터 데이터 형태의 지리공간 정보를 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [GEO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/) | GeoJSON은 비공간 속성을 가진 지리적 특징을 표현하도록 설계된 JSON 기반 형식입니다. 이 형식은 다양한 JSON(JavaScript Object Notation) 객체와 그 결합 방식을 정의합니다. JSON 형식은 지리적 특징, 그 공간 범위 및 속성에 대한 종합 정보를 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [GDB](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/) | ESRI 파일 지오데이터베이스(FileGDB)는 디스크의 폴더에 있는 파일 컬렉션으로, 피처 데이터셋, 피처 클래스 및 관련 테이블과 같은 관련 지리공간 데이터를 보관합니다. 작동하려면 .gdb 파일과 함께 동일한 디렉터리에 특정 다른 파일들을 보관해야 합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [GML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/) | GML은 Open Geospatial Consortium(OGC)에서 개발한 XML 사양을 기반으로 하는 Geography Markup Language를 의미합니다. 이 형식은 다양한 파일 형식 간의 교환을 위해 지리 데이터 피처를 저장하는 데 사용됩니다. 지리 시스템을 모델링하는 언어이자 인터넷상의 지리 거래를 위한 개방형 교환 형식으로도 활용됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [KML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/) | KML(Keyhole Markup Language)은 XML 표기법으로 지리 공간 정보를 포함합니다. KML로 저장된 파일은 GIS(Geographic Information System) 애플리케이션에서 지원되는 경우 열 수 있습니다. 많은 애플리케이션이 KML 파일 형식을 국제 표준으로 채택한 이후 지원을 시작했습니다. KML은 중첩된 요소와 속성을 가진 태그 기반 구조를 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [GPX](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/) | GPX 확장자를 가진 파일은 인터넷상의 애플리케이션 및 웹 서비스 간에 GPS 데이터를 교환하기 위한 GPS Exchange 형식을 나타냅니다. 이는 경량 XML 파일 형식으로, 웨이포인트, 경로 및 트랙과 같은 GPS 데이터를 포함하며 여러 프로그램에서 가져오고 읽을 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [TOPO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/) | TopoJSON은 토폴로지를 인코딩하는 GeoJSON의 확장입니다. 개별적으로 기하를 표현하는 대신, TopoJSON 파일의 기하는 아크라 불리는 공유 선분으로부터 연결되어 구성됩니다. |
| [OSM](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/) | OSM 파일 형식은 OpenStreetMap 프로젝트에서 지리 데이터를 저장하기 위해 사용되는 구조화된 데이터 형식입니다. OSM 파일은 일반적으로 XML 형식이며 도로, 건물, 관심 지점 및 지도상의 기타 특징과 같은 정보를 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 알 수 없는 파일 유형 ([`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |

### 또 보기
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
