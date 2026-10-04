---
title: "GisFileType"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "GIS belgelerini tanımlar. Aşağıdaki dosya türlerini içerir: Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /tr/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

GIS belgelerini tanımlar. Aşağıdaki dosya türlerini içerir: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [GisFileType](gisfiletype)() | Serileştirme yapıcısı |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dosya türü açıklaması |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Dosya uzantısı |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Dosya ailesi |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Dosya formatı |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Mevcut nesneyi diğerine karşılaştırır. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) uygular. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Varsayılan hash işlevi olarak hizmet eder. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Dize temsili |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | ESRI dosya Geodatabase (FileGDB), özellik veri setleri, özellik sınıfları ve ilişkili tablolar gibi ilgili coğrafi verileri tutan bir klasördeki dosyaların koleksiyonudur. Çalışması için .gdb dosyasının yanında aynı dizinde belirli diğer dosyaların bulunması gerekir. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON, coğrafi özellikleri ve bunların mekansal olmayan niteliklerini temsil etmek için tasarlanmış JSON tabanlı bir formattır. Bu format, farklı JSON (JavaScript Object Notation) nesnelerini ve bunların birleştirilme şeklini tanımlar. JSON formatı, coğrafi özellikler, bunların mekânsal kapsamları ve özellikleri hakkında toplu bilgi sunar. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON Metin Dizisi, tek bir kapsayıcı belge yerine bağımsız GeoJSON kayıtlarından oluşan bir akıştır; her kayıt bir yeni satır ya da RS kontrol karakteriyle ayrılır. Zaman içinde eklenen beslemeler için, koleksiyonun sonu yazma başladığında bilinmediğinde kullanılır. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML, Açık Coğrafi Veri Konsorsiyumu (OGC) tarafından geliştirilen XML spesifikasyonlarına dayanan Geography Markup Language (Coğrafya İşaretleme Dili) anlamına gelir. Bu format, farklı dosya formatları arasında değiş tokuş için coğrafi veri özelliklerini depolamak amacıyla kullanılır. Aynı zamanda coğrafi sistemler için bir modelleme dili ve internet üzerindeki coğrafi işlemler için açık bir değiş tokuş formatı olarak hizmet verir. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | GPX uzantılı dosyalar, internet üzerindeki uygulamalar ve web hizmetleri arasında GPS verilerinin değiş tokuşu için GPS Exchange formatını temsil eder. Bu, GPS verilerini (örneğin yol noktaları, rotalar ve izler) içeren hafif bir XML dosya formatıdır ve birden çok program tarafından içe aktarılabilir ve okunabilir. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language), XML notasyonunda coğrafi bilgi içerir. KML olarak kaydedilen dosyalar, destekli oldukları sürece Coğrafi Bilgi Sistemi (GIS) uygulamalarında açılabilir. Birçok uygulama, KML dosya formatı uluslararası standart haline geldikten sonra destek sağlamaya başladı. KML, iç içe öğeler ve özniteliklerle etiket tabanlı bir yapı kullanır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/gis/kml/) bakabilirsiniz. |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ, bir KML belgesi taşıyan bir ZIP arşividir; geleneksel olarak arşivin kökünde doc.kml adıyla bulunur ve belgeye referans veren tüm kaynakları içerir. İşaretlemenin sıkıştırılması amaçtır: herhangi bir boyuttaki KML akışı büyük ölçüde küçülür, bu yüzden yayıncılar KML yerine KMZ dağıtır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/gis/kmz/) bakabilirsiniz. |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | OSM dosya formatı, OpenStreetMap projesinde coğrafi verileri depolamak için kullanılan yapılandırılmış bir veri formatıdır. OSM dosyaları genellikle XML formatındadır ve yollardaki, binalardaki, ilgi noktalarındaki ve haritadaki diğer özelliklerin konumu gibi bilgileri içerir. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/gis/osm/) bakabilirsiniz. |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP, ESRI Shapefile temsilinde kullanılan temel dosya türlerinden birinin dosya uzantısıdır. Coğrafi Bilgi Sistemleri (GIS) uygulamaları tarafından kullanılmak üzere vektör veri biçiminde coğrafi bilgi temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/gis/shp/) bakabilirsiniz. |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON, topolojiyi kodlayan bir GeoJSON uzantısıdır. Geometrileri ayrı ayrı temsil etmek yerine, TopoJSON dosyalarındaki geometriler, 'arc' adı verilen ortak çizgi segmentlerinden birleştirilir. |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
