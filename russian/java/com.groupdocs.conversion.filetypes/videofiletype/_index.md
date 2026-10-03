---
title: "VideoFileType"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Определяет видеодокументы. Включает следующие типы        Узнайте больше о видеоформатах здесь."
type: docs
weight: 26
url: /ru/java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

Определяет видеодокументы. Включает следующие типы: , , , , , , , Узнайте больше о видеоформатах [здесь](../https://docs.fileformat.com/video/).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [VideoFileType()](#VideoFileType--) | Конструктор сериализации |
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [Mp4](#Mp4) | MP4 (сокращение от MPEG-4 Part 14) — это формат файла, основанный на ISO/IEC 14496-12:2004, который базируется на QuickTime File Format, но официально определяет поддержку Initial Object Descriptors (IOD) и других функций MPEG. |
|
|  | [Avi](#Avi) | Формат файла AVI — это мультимедийный контейнер Audio Video, представленный компанией Microsoft. |
|
|  | [Flv](#Flv) | FLV (Flash Video) — это контейнерный формат файла с расширением .flv. |
|
|  | [Mkv](#Mkv) | MKV (Matroska Video) — это мультимедийный контейнер, похожий на форматы MOV и AVI, но поддерживающий более одной аудио‑ и субтитровой дорожки в одном файле. |
|
|  | [Mov](#Mov) | MOV или формат файла QuickTime — это мультимедийный контейнер, разработанный Apple: содержит одну или несколько дорожек, каждая из которых хранит определённый тип данных, например. |
|
|  | [Webm](#Webm) | Файл с расширением .webm — это видеофайл, основанный на открытом, бесплатном формате WebM. |
|
|  | [Wmv](#Wmv) | Windows Media Video — это сжатый видеоформат, разработанный Microsoft. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


Конструктор сериализации


### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4 (сокращение от MPEG-4 Part 14) — это формат файла, основанный на ISO/IEC 14496-12:2004, который базируется на QuickTime File Format, но официально определяет поддержку Initial Object Descriptors (IOD) и других функций MPEG. Узнайте больше о этом формате файла [здесь](../https://docs.fileformat.com/video/mp4/).


### Avi {#Avi}
```
public static final VideoFileType Avi
```


Формат файла AVI — это мультимедийный контейнер Audio Video, представленный Microsoft. Он содержит аудио‑ и видеоданные, созданные и сжатые с помощью различных кодеков (кодировщиков/декодеров), таких как XVid и DivX. Узнайте больше о этом формате файла [здесь](../https://docs.fileformat.com/video/avi/).


### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video) — это контейнерный формат файла с расширением .flv. FLV используется для доставки аудио/видео контента через интернет с помощью Adobe Flash Player или Adobe Air. Узнайте больше о этом формате файла [здесь](../https://docs.fileformat.com/video/flv/).


### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video) — это мультимедийный контейнер, похожий на форматы MOV и AVI, но поддерживает более одной аудио‑ и субтитровой дорожки в одном файле. Файл MKV — это формат мультимедийного контейнера Matroska, используемый для видео. Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/video/mkv/).


### Mov {#Mov}
```
public static final VideoFileType Mov
```


Формат файла MOV или QuickTime — это мультимедийный контейнер, разработанный компанией Apple: содержит одну или несколько дорожек, каждая из которых хранит определённый тип данных, например видео, аудио, текст и т.д. Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/video/mov/).


### Webm {#Webm}
```
public static final VideoFileType Webm
```


Файл с расширением .webm — это видеофайл, основанный на открытом, не требующем роялти формате WebM. Он разработан для обмена видео в интернете и определяет структуру контейнера файла, включая видеo‑ и аудиоформаты. Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/video/webm//).


### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video — это сжатый видеоформат, разработанный компанией Microsoft. После стандартизации Обществом инженеров кино и телевидения (SMPTE) WMV теперь считается открытым стандартным форматом. Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/video/wmv/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Подготовлены параметры загрузки по умолчанию для исходного типа файла


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Подготовлены параметры конвертации по умолчанию для типа файла


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
