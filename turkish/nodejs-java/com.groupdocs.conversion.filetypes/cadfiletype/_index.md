---
title: "CadFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "3D grafik dosya formatları için kullanılan ve 2D veya 3D tasarımlar içerebilen CAD (Computer Aided Design) belgelerini tanımlar."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

3D grafik dosya formatları için kullanılan ve 2D veya 3D tasarımlar içerebilen CAD (Computer Aided Design) belgelerini tanımlar. Aşağıdaki türleri içerir: [Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dgn), [Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwf), [Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwg), [Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwt), [Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dxf), [Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype\#Ifc), [Igs](../../com.groupdocs.conversion.filetypes/cadfiletype\#Igs), [Plt](../../com.groupdocs.conversion.filetypes/cadfiletype\#Plt), [Stl](../../com.groupdocs.conversion.filetypes/cadfiletype\#Stl). [Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype\#Cf2). [Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwfx). CAD formatları hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CadFileType()](#CadFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Dxf](#Dxf) | DXF, Drawing Interchange Format veya Drawing Exchange Format, AutoCAD çizim dosyasının etiketli veri temsiliidir. |
| [Dwg](#Dwg) | DWG uzantılı dosyalar, 2D ve 3D tasarım verilerini içeren özel ikili dosyaları temsil eder. |
| [Dgn](#Dgn) | DGN, Design dosyaları, MicroStation ve Intergraph Interactive Graphics Design System gibi CAD uygulamaları tarafından oluşturulan ve desteklenen çizimlerdir. |
| [Dwf](#Dwf) | Design Web Format (DWF), tasarım dosyalarını görüntüleme, inceleme veya yazdırma amacıyla sıkıştırılmış formatta 2D/3D çizim olarak temsil eder. |
| [Stl](#Stl) | STL, stereolithografi kelimesinin kısaltmasıdır ve 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya formatıdır. |
| [Ifc](#Ifc) | IFC uzantılı dosyalar, bina nesnelerini ve özelliklerini içe ve dışa aktarmak için uluslararası standartlar belirleyen Industry Foundation Classes (IFC) dosya formatına atıfta bulunur. |
| [Plt](#Plt) | PLT dosya formatı, Autodesk, Inc. tarafından tanıtılan vektör tabanlı bir plotter dosyasıdır. |
| [Igs](#Igs) | Igs belge formatı |
| [Dwt](#Dwt) | DWT dosyası, DWG dosyası olarak kaydedilebilen çizimler oluşturmak için başlangıç olarak kullanılan bir AutoCAD çizim şablonu dosyasıdır. |
| [Dwfx](#Dwfx) | DWFX dosyası, Autodesk CAD yazılımı ile oluşturulan 2D veya 3D bir çizimdir. |
| [Cf2](#Cf2) | Common File Format dosyası. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Serileştirme yapıcısı

### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF, Drawing Interchange Format veya Drawing Exchange Format, AutoCAD çizim dosyasının etiketli veri temsiliidir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


DWG uzantılı dosyalar, 2D ve 3D tasarım verilerini içeren özel ikili dosyaları temsil eder. ASCII dosyaları olan DXF gibi, DWG CAD (Computer Aided Design) çizimleri için ikili dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][]


[here]: https://wiki.fileformat.com/cad/dwg

### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN, Design dosyaları, MicroStation ve Intergraph Interactive Graphics Design System gibi CAD uygulamaları tarafından oluşturulan ve desteklenen çizimlerdir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF), 2D/3D çizimleri sıkıştırılmış formatta görüntüleme, inceleme veya tasarım dosyalarını yazdırma için temsil eder. Tasarım verilerinin bir parçası olarak grafik ve metin içerir ve sıkıştırılmış formatı sayesinde dosya boyutunu azaltır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, stereolitografi'nin kısaltmasıdır, 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya formatıdır. Bu dosya formatı, hızlı prototipleme, 3D baskı ve bilgisayar destekli imalat gibi çeşitli alanlarda kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad/stl

### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


IFC uzantılı dosyalar, bina nesnelerini ve özelliklerini içe ve dışa aktarmak için uluslararası standartlar belirleyen Industry Foundation Classes (IFC) dosya formatını ifade eder. Bu dosya formatı, farklı yazılım uygulamaları arasında birlikte çalışabilirlik sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### Plt {#Plt}
```
public static final CadFileType Plt
```


PLT dosya formatı, Autodesk, Inc. tarafından tanıtılan vektör tabanlı bir plotter dosyasıdır ve belirli bir CAD dosyası için bilgi içerir. Çizim detayları üretimde doğruluk ve hassasiyet gerektirir ve PLT dosyasının kullanımı, tüm görüntülerin nokta yerine çizgiyle basılması sayesinde bunu garanti eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad/plt

### Igs {#Igs}
```
public static final CadFileType Igs
```


Igs belge formatı

### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


DWT dosyası, DWG dosyaları olarak kaydedilebilecek çizimler oluşturmak için başlangıç olarak kullanılan bir AutoCAD çizim şablonu dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


DWFX dosyası, Autodesk CAD yazılımı ile oluşturulan 2D veya 3D bir çizimdir. .DWF dosyasına benzer bir DWFx formatında kaydedilir, ancak Microsoft'un XML Paper Specification (XPS) kullanılarak biçimlendirilir.

### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Common File Format Dosyası. 3D paket tasarımları veya diğer model verilerini içeren CAD dosyası; bir kalıp kesme cihazı gibi bir CAD/CAM makinesi tarafından işlenip kesilebilir.

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
