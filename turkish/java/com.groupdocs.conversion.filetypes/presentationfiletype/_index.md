---
title: "PresentationFileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Sunum dosya formatlarını tanımlar; bu formatlar, slaytlar, şekiller, metin, animasyonlar, video, ses ve gömülü nesneler gibi sunum verilerini barındırmak için kayıt koleksiyonlarını depolar."
type: docs
weight: 22
url: /tr/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Sunum verilerini (slaytlar, şekiller, metin, animasyonlar, video, ses ve gömülü nesneler) barındırmak için kayıt koleksiyonunu depolayan Sunum dosya formatlarını tanımlar.
Aşağıdaki dosya türlerini içerir:
[Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Odp),
[Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Otp),
[Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pot),
[Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potm),
[Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potx),
[Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pps),
[Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsm),
[Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsx),
[Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppt),
[Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptm),
[Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptx).
Sunum formatları hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | Serileştirme yapıcısı |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Ppt](#Ppt) | PPT uzantılı bir dosya, Slayt Gösterisi olarak görüntülenmek üzere slayt koleksiyonundan oluşan bir PowerPoint dosyasını temsil eder. |
|
|  | [Pps](#Pps) | PPS, PowerPoint Slayt Gösterisi, dosyaları Slayt Gösterisi amacıyla Microsoft PowerPoint kullanılarak oluşturulur. |
|
|  | [Pptx](#Pptx) | PPTX uzantılı dosyalar, popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. |
|
|  | [Ppsx](#Ppsx) | PPSX, PowerPoint Slayt Gösterisi, dosyalar Slayt Gösterisi amacıyla Microsoft PowerPoint 2007 ve üzeri kullanılarak oluşturulur. |
|
|  | [Odp](#Odp) | ODP uzantılı dosyalar, OpenOffice.org tarafından OASISOpen standardında kullanılan sunum dosya formatını temsil eder. |
|
|  | [Otp](#Otp) | .OTP uzantılı dosyalar, OASIS OpenDocument standart formatında uygulamalar tarafından oluşturulan sunum şablon dosyalarını temsil eder. |
|
|  | [Potx](#Potx) | .POTX uzantılı dosyalar, Microsoft PowerPoint 2007 ve üzeri ile oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. |
|
|  | [Pot](#Pot) | .POT uzantılı dosyalar, PowerPoint 97-2003 sürümleriyle oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder. |
|
|  | [Potm](#Potm) | POTM uzantılı dosyalar, makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. |
|
|  | [Pptm](#Pptm) | PPTM uzantılı dosyalar, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan makro etkinleştirilmiş sunum dosyalarıdır. |
|
|  | [Ppsm](#Ppsm) | PPSM uzantılı dosyalar, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan makro etkinleştirilmiş Slayt Gösterisi dosya formatını temsil eder. |
|
|  | [Fodp](#Fodp) | FODP uzantılı dosyalar, OpenDocument Düz XML Sunumunu temsil eder. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


Serileştirme yapıcısı


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


PPT uzantılı bir dosya, Slayt Gösterisi olarak görüntülenmek üzere slayt koleksiyonundan oluşan bir PowerPoint dosyasını temsil eder. Bu, Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Formatını belirtir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/ppt).


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint Slayt Gösterisi, dosyaları Slayt Gösterisi amacıyla Microsoft PowerPoint kullanılarak oluşturulur. PPS dosya okuma ve oluşturma Microsoft PowerPoint 97-2003 tarafından desteklenir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/pps).


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


PPTX uzantılı dosyalar, popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. Önceki PPT sunum dosya formatının ikili olmasının aksine, PPTX formatı Microsoft PowerPoint açık XML sunum dosya formatına dayanır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/pptx).


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX, PowerPoint Slayt Gösterisi, dosyalar Slayt Gösterisi amacıyla Microsoft PowerPoint 2007 ve üzeri kullanılarak oluşturulur.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/ppsx).


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


ODP uzantılı dosyalar, OpenOffice.org tarafından OASISOpen standardında kullanılan sunum dosya formatını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/odp).


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


.OTP uzantılı dosyalar, OASIS OpenDocument standart formatında uygulamalar tarafından oluşturulan sunum şablon dosyalarını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/otp).


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


.POTX uzantılı dosyalar, Microsoft PowerPoint 2007 ve üzeri ile oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/potx).


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


.POT uzantılı dosyalar, PowerPoint 97-2003 sürümleriyle oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/pot).


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


POTM uzantılı dosyalar, Makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. POTM dosyaları PowerPoint 2007 veya daha yeni sürümlerle oluşturulur ve daha fazla sunum dosyası oluşturmak için kullanılabilecek varsayılan ayarları içerir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/potm).


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


PPTM uzantılı dosyalar, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan makro etkinleştirilmiş sunum dosyalarıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/pptm).


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


PPSM uzantılı dosyalar, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan makro etkinleştirilmiş Slayt Gösterisi dosya formatını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/ppsm).


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


FODP uzantılı dosyalar OpenDocument Düz XML Sunumu temsil eder. Sunum dosyası OpenDocument formatında kaydedilir, ancak standart .ODP dosyalarında kullanılan .ZIP konteyneri yerine düz XML formatı kullanılarak kaydedilir.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Dosya türü için varsayılan dönüştürme seçenekleri hazırlandı


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
