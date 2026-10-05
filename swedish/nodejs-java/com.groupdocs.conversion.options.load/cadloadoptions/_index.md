---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för inläsning av CAD-dokument."
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

Alternativ för inläsning av CAD-dokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CadLoadOptions()](#CadLoadOptions--) | Initierar en ny instans av [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getWidth()](#getWidth--) | Ställer in önskad sidbredd för konvertering av CAD-dokument |
| [setWidth(int value)](#setWidth-int-) | Ställer in önskad sidbredd för konvertering av CAD-dokument |
| [getHeight()](#getHeight--) | Ställer in önskad sidhöjd för konvertering av CAD-dokument |
| [setHeight(int value)](#setHeight-int-) | Ställer in önskad sidhöjd för konvertering av CAD-dokument |
| [getLayoutNames()](#getLayoutNames--) | Anger vilka CAD‑layouter som ska konverteras |
| [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Anger vilka CAD‑layouter som ska konverteras |
| [getDrawType()](#getDrawType--) | Hämtar typ av ritning. |
| [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Ställer in typ av ritning. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar en bakgrundsfärg. |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Ställer in en bakgrundsfärg. |
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


Initierar en ny instans av [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) klassen.

### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


Inmatningsdokumentets filtyp

**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ställer in önskad sidbredd för konvertering av CAD-dokument

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in önskad sidbredd för konvertering av CAD-dokument

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ställer in önskad sidhöjd för konvertering av CAD-dokument

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in önskad sidhöjd för konvertering av CAD-dokument

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


Anger vilka CAD‑layouter som ska konverteras

**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


Anger vilka CAD‑layouter som ska konverteras

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


Hämtar typ av ritning.

**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


Ställer in typ av ritning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Hämtar en bakgrundsfärg.

**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Ställer in en bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

