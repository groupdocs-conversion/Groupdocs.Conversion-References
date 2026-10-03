---
title: "GisFileType"
second_title: "GroupDocs.Conversion لـ .NET مرجع API"
description: "يحدد مستندات GIS. يتضمن أنواع الملفات التالية Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /ar/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

يحدد مستندات GIS. يتضمن أنواع الملفات التالية: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GisFileType](gisfiletype)() | منشئ التسلسل |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | وصف نوع الملف |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | امتداد الملف |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | عائلة الملف |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | صيغة الملف |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | يقارن الكائن الحالي بآخر. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | ينفذ [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | يحدد ما إذا كان مثيلان للكائن متساويين. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | يعمل كدالة التجزئة الافتراضية. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | تمثيل النص |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | قاعدة بيانات ملفات ESRI (FileGDB) هي مجموعة من الملفات في مجلد على القرص تحتفظ ببيانات جغرافية مترابطة مثل مجموعات البيانات المميزة، فئات المميزات والجداول المرتبطة. يتطلب وجود ملفات أخرى معينة بجانب ملف .gdb في نفس الدليل لتعمل. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON هو تنسيق مبني على JSON صُمم لتمثيل الميزات الجغرافية مع سماتها غير المكانية. يعرّف هذا التنسيق كائنات JSON المختلفة وطريقة ربطها. يمثل تنسيق JSON معلومات شاملة عن الميزات الجغرافية، امتداداتها المكانية، وخصائصها. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | سلسلة نصية GeoJSON هي تدفق من سجلات GeoJSON مستقلة بدلاً من مستند موحد، كل سجل مفصول بسطر جديد أو بواسطة حرف التحكم RS. تُستخدم للتغذيات التي تُضاف بمرور الوقت، حيث لا يُعرف نهاية المجموعة عند بدء الكتابة. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML تعني لغة توصيف الجغرافيا (Geography Markup Language) وتستند إلى مواصفات XML التي طورها اتحاد الجغرافيا المفتوح (OGC). يُستخدم هذا التنسيق لتخزين ميزات البيانات الجغرافية لتبادلها بين تنسيقات ملفات مختلفة. يعمل كلغة نمذجة للأنظمة الجغرافية وكذلك كتنسيق تبادل مفتوح للمعاملات الجغرافية على الإنترنت. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | الملفات ذات الامتداد GPX تمثل تنسيق تبادل GPS لتبادل بيانات GPS بين التطبيقات والخدمات على الإنترنت. هو تنسيق XML خفيف الوزن يحتوي على بيانات GPS مثل نقاط الطريق والمسارات والمسارات لتُستورد وتُقرأ بواسطة برامج متعددة. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) يحتوي على معلومات جغرافية مكانية بصيغة XML. يمكن فتح الملفات المحفوظة كـ KML في تطبيقات نظام المعلومات الجغرافية (GIS) شريطة أن تدعمها. بدأت العديد من التطبيقات في توفير الدعم لتنسيق ملف KML بعد اعتماده كمعيار دولي. يستخدم KML بنية قائمة على العلامات مع عناصر وسمات متداخلة. تعرف على المزيد حول هذا التنسيق [here](https://docs.fileformat.com/gis/kml/). |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ هو أرشيف ZIP يحمل مستند KML، يُسمى عادةً doc.kml في جذر الأرشيف، مع أي موارد يشير إليها المستند. الهدف هو ضغط العلامات: فإن خلاصة KML بأي حجم تتقلص بشكل كبير، وهذا هو السبب في أن الناشرين يوزعون KMZ بدلاً من KML. تعرف على المزيد حول هذا التنسيق [here](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | تنسيق ملف OSM هو تنسيق بيانات منظم يُستخدم لتخزين البيانات الجغرافية في مشروع OpenStreetMap. عادةً ما تكون ملفات OSM بصيغة XML وتحتوي على معلومات مثل مواقع الطرق، المباني، نقاط الاهتمام، وغيرها من المعالم على الخريطة. تعرف على المزيد حول هذا التنسيق [here](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP هو امتداد الملف لأحد الأنواع الأساسية المستخدمة لتمثيل ملف ESRI Shapefile. يمثل معلومات جغرافية مكانية على شكل بيانات متجهة تُستخدم بواسطة تطبيقات نظام المعلومات الجغرافية (GIS). تعرف على المزيد حول هذا التنسيق [here](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON هو امتداد لـ GeoJSON يُشفّر الطوبولوجيا. بدلاً من تمثيل الأشكال الهندسية بشكل منفصل، تُربط الأشكال الهندسية في ملفات TopoJSON معًا من مقاطع خطوط مشتركة تُسمى أقواس. |

### انظر أيضًا

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
