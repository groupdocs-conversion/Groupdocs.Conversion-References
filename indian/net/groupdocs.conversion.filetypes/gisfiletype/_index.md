---
title: "GisFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "GIS दस्तावेज़ों को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /hi/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

GIS दस्तावेज़ों को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [GisFileType](gisfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

## गुण

| नाम | विवरण |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | फ़ाइल प्रकार विवरण |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | फ़ाइल एक्सटेंशन |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | फ़ाइल परिवार |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | फ़ाइल फ़ॉर्मेट |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | वर्तमान ऑब्जेक्ट की तुलना अन्य से करता है। |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) को लागू करता है। |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | स्ट्रिंग प्रतिनिधित्व |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | ESRI फ़ाइल Geodatabase (FileGDB) डिस्क पर एक फ़ोल्डर में फ़ाइलों का संग्रह है जो फीचर डेटासेट, फीचर क्लास और संबंधित तालिकाओं जैसे संबंधित जियोस्पेशियल डेटा को रखता है। इसे काम करने के लिए .gdb फ़ाइल के साथ उसी डायरेक्टरी में कुछ अन्य फ़ाइलों को भी रखना आवश्यक है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/database/gdb/) देखें। |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON एक JSON-आधारित फ़ॉर्मेट है जिसे भौगोलिक विशेषताओं को उनके गैर-स्थानिक गुणों के साथ दर्शाने के लिए डिज़ाइन किया गया है। यह फ़ॉर्मेट विभिन्न JSON (JavaScript Object Notation) ऑब्जेक्ट्स और उनके संयोजन को परिभाषित करता है। JSON फ़ॉर्मेट भौगोलिक विशेषताओं, उनके स्थानिक विस्तार और गुणों के बारे में सामूहिक जानकारी प्रस्तुत करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/gis/geojson/) देखें। |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON टेक्स्ट सीक्वेंस स्वतंत्र GeoJSON रिकॉर्ड्स की एक स्ट्रीम है, न कि एक समाहित दस्तावेज़, प्रत्येक रिकॉर्ड नई पंक्ति या RS नियंत्रण अक्षर द्वारा सीमांकित होता है। इसे उन फ़ीड्स के लिए उपयोग किया जाता है जो समय के साथ जोड़े जाते हैं, जहाँ संग्रह का अंत लिखना शुरू होने पर ज्ञात नहीं होता। |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML का अर्थ Geography Markup Language है, जो Open Geospatial Consortium (OGC) द्वारा विकसित XML विनिर्देशों पर आधारित है। यह फ़ॉर्मेट विभिन्न फ़ाइल फ़ॉर्मेटों के बीच विनिमय के लिए भौगोलिक डेटा विशेषताओं को संग्रहीत करने में उपयोग होता है। यह भौगोलिक प्रणालियों के लिए एक मॉडलिंग भाषा और इंटरनेट पर भौगोलिक लेनदेन के लिए एक खुला विनिमय फ़ॉर्मेट दोनों के रूप में कार्य करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/gis/gml/) देखें। |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | .GPX एक्सटेंशन वाली फ़ाइलें GPS एक्सचेंज फ़ॉर्मेट को दर्शाती हैं जो इंटरनेट पर एप्लिकेशन और वेब सेवाओं के बीच GPS डेटा के विनिमय के लिए उपयोग होती हैं। यह एक हल्का XML फ़ाइल फ़ॉर्मेट है जिसमें GPS डेटा जैसे वेपॉइंट, रूट और ट्रैक शामिल होते हैं, जिन्हें कई प्रोग्राम आयात और पढ़ सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/gis/gpx/) देखें। |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) में XML नोटेशन में भू-स्थानिक जानकारी होती है। KML के रूप में सहेजी गई फ़ाइलें Geographic Information System (GIS) अनुप्रयोगों में खोली जा सकती हैं, बशर्ते वे इसे समर्थन करें। कई अनुप्रयोगों ने KML फ़ाइल फ़ॉर्मेट के लिए समर्थन प्रदान करना शुरू कर दिया है, जब इसे अंतरराष्ट्रीय मानक के रूप में अपनाया गया। KML टैग-आधारित संरचना का उपयोग करता है जिसमें नेस्टेड तत्व और गुण होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/gis/kml/) देखें। |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ एक ZIP आर्काइव है जिसमें KML दस्तावेज़ होता है, सामान्यतः आर्काइव की रूट पर इसे doc.kml नाम दिया जाता है, साथ ही उन सभी संसाधनों के साथ जिनका उल्लेख दस्तावेज़ करता है। मार्कअप को संकुचित करना मुख्य उद्देश्य है: किसी भी आकार का KML फ़ीड काफी घट जाता है, इसलिए प्रकाशक KMZ को KML की बजाय वितरित करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/gis/kmz/) देखें। |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | OSM फ़ाइल फ़ॉर्मेट एक संरचित डेटा फ़ॉर्मेट है जो OpenStreetMap परियोजना में भौगोलिक डेटा संग्रहीत करने के लिए उपयोग किया जाता है। OSM फ़ाइलें सामान्यतः XML फ़ॉर्मेट में होती हैं और इसमें सड़कें, इमारतें, रुचि के बिंदु और मानचित्र पर अन्य विशेषताओं के स्थान जैसी जानकारी शामिल होती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/gis/osm/) देखें। |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP ESRI Shapefile के प्रतिनिधित्व के लिए उपयोग किए जाने वाले प्रमुख फ़ाइल प्रकारों में से एक की फ़ाइल एक्सटेंशन है। यह वेक्टर डेटा के रूप में भू-स्थानिक जानकारी को दर्शाता है जिसे Geographic Information Systems (GIS) अनुप्रयोगों द्वारा उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/gis/shp/) देखें। |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON, GeoJSON का एक विस्तार है जो टोपोलॉजी को एन्कोड करता है। अलग-अलग ज्यामितियों को दर्शाने के बजाय, TopoJSON फ़ाइलों में ज्यामितियाँ साझा रेखा खंडों जिन्हें आर्क कहा जाता है, से मिलकर बनती हैं। |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
