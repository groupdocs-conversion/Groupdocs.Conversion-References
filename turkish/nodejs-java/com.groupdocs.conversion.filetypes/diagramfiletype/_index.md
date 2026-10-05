---
title: "DiagramFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Diyagram belgelerini tanımlar."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Diagram belgelerini tanımlar. Aşağıdaki türleri içerir: [Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vdw), [Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vdx), [Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsd), [Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsdm), [Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsdx), [Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vss), [Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vssm), [Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vssx), [Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vst), [Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vstm), [Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vstx), [Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsx), [Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vtx).
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DiagramFileType()](#DiagramFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Vsd](#Vsd) | VSD dosyaları, çeşitli grafik nesnelerini ve bunlar arasındaki bağlantıyı temsil etmek için Microsoft Visio uygulamasıyla oluşturulan çizimlerdir. |
| [Vsdx](#Vsdx) | .VSDX uzantılı dosyalar, Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatını temsil eder. |
| [Vss](#Vss) | VSS, Microsoft Visio 2007 ve öncesi sürümlerle oluşturulan şablon (stencil) dosyalarıdır. |
| [Vst](#Vst) | VST uzantılı dosyalar, Microsoft Visio ile oluşturulan vektör görüntü dosyalarıdır ve sonraki dosyalar için şablon görevi görür. |
| [Vsx](#Vsx) | .VSX uzantılı dosyalar, Microsoft Visio'da diyagramlar oluşturmak için kullanılan çizimler ve şekillerden oluşan şablonları (stencil) ifade eder. |
| [Vtx](#Vtx) | VTX uzantılı bir dosya, XML dosya formatında diske kaydedilen bir Microsoft Visio çizim şablonudur. |
| [Vdw](#Vdw) | VDW, bir Web çiziminin renderlanması için gereken akışları ve depolamaları belirten Visio Graphics Service dosya formatıdır. |
| [Vdx](#Vdx) | Microsoft Visio'da oluşturulan ve XML formatında kaydedilen tüm çizimler veya grafikler .VDX uzantısına sahiptir. |
| [Vssx](#Vssx) | .VSSX uzantılı dosyalar, Microsoft Visio 2013 ve üzeri ile oluşturulan çizim şablonlarıdır. |
| [Vstx](#Vstx) | VSTX uzantılı dosyalar, Microsoft Visio 2013 ve üzeri ile oluşturulan çizim şablon dosyalarıdır. |
| [Vsdm](#Vsdm) | VSDM uzantılı dosyalar, makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyalarıdır. |
| [Vssm](#Vssm) | .VSSM uzantılı dosyalar, makroları destekleyen Microsoft Visio Şablon dosyalarıdır. |
| [Vstm](#Vstm) | VSTM uzantılı dosyalar, makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyalarıdır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Serileştirme yapıcısı

### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


VSD dosyaları, çeşitli grafik nesnelerini ve bunlar arasındaki bağlantıları temsil etmek için Microsoft Visio uygulamasıyla oluşturulan çizimlerdir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vsd

### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


.VSDX uzantılı dosyalar, Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatını temsil eder. Önceki Visio sürümlerinin desteklediği ikili .VSD formatının yerine geçecek şekilde geliştirilmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS, Microsoft Visio 2007 ve öncesi ile oluşturulan şablon dosyalarıdır. Şablon dosyaları, bir .VSD Visio çizimine eklenebilen çizim nesneleri sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vss

### Vst {#Vst}
```
public static final DiagramFileType Vst
```


VST uzantılı dosyalar, Microsoft Visio ile oluşturulan vektör görüntü dosyalarıdır ve sonraki dosyaların oluşturulması için şablon görevi görür. Bu şablon dosyaları ikili dosya formatındadır ve yeni Visio çizimleri oluşturulurken kullanılan varsayılan düzen ve ayarları içerir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vst

### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


.VSX uzantılı dosyalar, Microsoft Visio'da diyagram oluşturmak için kullanılan çizimler ve şekillerden oluşan şablonları ifade eder. VSX dosyaları XML dosya formatında kaydedilir ve Visio 2013'e kadar desteklenmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vsx

### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


VTX uzantılı bir dosya, XML dosya formatında diske kaydedilen bir Microsoft Visio çizim şablonudur. Şablon, aynı ayarlara sahip birden fazla Visio dosyası oluşturmak için kullanılabilecek temel ayarları içeren bir dosya sağlamayı amaçlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vtx

### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW, bir Web çiziminin renderlanması için gereken akışları ve depolamaları belirten Visio Graphics Service dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/vdw

### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Microsoft Visio'da oluşturulan ve XML formatında kaydedilen tüm çizimler veya grafikler .VDX uzantısına sahiptir. Visio yazılımı tarafından oluşturulan bir Visio çizim XML dosyasıdır; bu yazılım Microsoft tarafından geliştirilmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vdx

### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


.VSSX uzantılı dosyalar, Microsoft Visio 2013 ve üzeri ile oluşturulan çizim şablonlarıdır. VSSX dosya formatı Visio 2013 ve üzeri ile açılabilir. Visio dosyaları, şekil koleksiyonları, bağlayıcılar, akış şemaları, ağ düzeni, UML diyagramları gibi çeşitli çizim öğelerinin temsil edilmesiyle bilinir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vssx

### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


VSTX uzantılı dosyalar, Microsoft Visio 2013 ve üzeri ile oluşturulan çizim şablon dosyalarıdır. Bu VSTX dosyaları, .VSDX dosyaları olarak kaydedilen Visio çizimleri için varsayılan düzen ve ayarlarla bir başlangıç noktası sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vstx

### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


VSDM uzantılı dosyalar, makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyalarıdır. VSDM dosyaları, VSDX'e benzer OPC/XML çizimleridir, ancak dosya açıldığında makroları çalıştırma yeteneği de sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


.VSSM uzantılı dosyalar, makroları destekleyen Microsoft Visio Şablon dosyalarıdır. Bir VSSM dosyası açıldığında, diyagramdaki şekillerin istenen biçimlendirilmesi ve yerleştirilmesi için makroların çalıştırılmasına izin verir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vssm

### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


VSTM uzantılı dosyalar, makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyalarıdır. VSDX dosyalarından farklı olarak, VSTM şablonlarından oluşturulan dosyalar Visual Basic for Applications (VBA) kodunda geliştirilen makroları çalıştırabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vstm

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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
