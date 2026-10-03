---
title: "WebConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Web."
type: docs
weight: 46
url: /el/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

Επιλογές για μετατροπή σε τύπο αρχείου Web.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | Καθορίζει αν θα ενσωματωθούν οι πόροι γραμματοσειράς μέσα στο κύριο HTML. |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | Καθορίζει αν θα ενσωματωθούν οι πόροι γραμματοσειράς μέσα στο κύριο HTML. |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης.


### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```




**Returns:**
boolean
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| usePdf | boolean |  |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```




**Returns:**
boolean
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| fixedLayout | boolean |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```




**Returns:**
boolean
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| fixedLayoutShowBorders | boolean |  |

### getZoom() {#getZoom--}
```
public int getZoom()
```




**Returns:**
int
### setZoom(int zoom) {#setZoom-int-}
```
public void setZoom(int zoom)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


Καθορίζει εάν θα ενσωματωθούν οι πόροι γραμματοσειράς στο κύριο HTML. Η προεπιλογή είναι false. Σημείωση: Εάν το FixedLayout οριστεί σε true, οι πόροι γραμματοσειράς θα ενσωματώνονται πάντα.


**Returns:**
boolean
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


Καθορίζει εάν θα ενσωματωθούν οι πόροι γραμματοσειράς στο κύριο HTML. Η προεπιλογή είναι false. Σημείωση: Εάν το FixedLayout οριστεί σε true, οι πόροι γραμματοσειράς θα ενσωματώνονται πάντα.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| embedFontResources | boolean |  |

