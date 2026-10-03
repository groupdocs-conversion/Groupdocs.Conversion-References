---
title: "ProjectManagementFileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Microsoft Project, Primavera P6 vb. gibi Proje Yönetimi yazılımları tarafından oluşturulan Proje dosya formatlarını tanımlar."
type: docs
weight: 23
url: /tr/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Microsoft Project, Primavera P6 vb. gibi Proje Yönetimi yazılımları tarafından oluşturulan Proje dosya formatlarını tanımlar. Bir proje dosyası, ölçülebilir bir çıktı elde etmek için görevlerin, kaynakların ve bunların zamanlamasının bir koleksiyonudur; bu çıktı bir ürün veya hizmet şeklinde olabilir.
Proje yönetimi belgeleri. Aşağıdaki dosya türlerini içerir:
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
Proje Yönetimi formatları hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/project-management).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | Serileştirme yapıcısı |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Mpt](#Mpt) | Microsoft Project şablon dosyaları, .MPP dosyaları oluşturmak için temel bilgi ve yapı ile birlikte belge ayarlarını içerir. |
|
|  | [Mpp](#Mpp) | MPP, proje yönetimiyle ilgili bilgileri bütünleşik bir şekilde depolayan Microsoft Project veri dosyasıdır. |
|
|  | [Mpx](#Mpx) | Microsoft Exchange File Format, Microsoft Project (MSP) ile Primavera Project Planner, Sciforma ve Timerline Precision Estimating gibi MPX dosya formatını destekleyen diğer uygulamalar arasında proje bilgilerini aktarmak için kullanılan bir ASCII dosya formatıdır. |
|
|  | [Xer](#Xer) | XER dosya formatı, Primavera P6 proje planlama ve yönetim uygulaması tarafından kullanılan özel bir proje dosya formatıdır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Serileştirme yapıcısı


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Microsoft Project şablon dosyaları, .MPP dosyaları oluşturmak için temel bilgi ve yapı ile birlikte belge ayarlarını içerir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP, proje yönetimiyle ilgili bilgileri bütünleşik bir şekilde depolayan Microsoft Project veri dosyasıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format, Microsoft Project (MSP) ile Primavera Project Planner, Sciforma ve Timerline Precision Estimating gibi MPX dosya formatını destekleyen diğer uygulamalar arasında proje bilgilerini aktarmak için kullanılan bir ASCII dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


XER dosya formatı, Primavera P6 proje planlama ve yönetim uygulaması tarafından kullanılan özel bir proje dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Dosya türü için varsayılan dönüştürme seçenekleri hazırlandı


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
