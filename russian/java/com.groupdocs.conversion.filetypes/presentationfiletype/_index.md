---
title: "PresentationFileType"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Определяет форматы файлов презентаций, которые хранят набор записей для размещения данных презентации, таких как слайды, фигуры, текст, анимации, видео, аудио и встроенные объекты."
type: docs
weight: 22
url: /ru/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Определяет форматы файлов презентаций, которые хранят коллекцию записей для представления данных презентации, таких как слайды, фигуры, текст, анимации, видео, аудио и встроенные объекты.
Включает следующие типы файлов:
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
Узнайте больше о форматах презентаций [здесь](../https://wiki.fileformat.com/presentation).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | Конструктор сериализации |
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [Ppt](#Ppt) | Файл с расширением PPT представляет файл PowerPoint, который состоит из набора слайдов для отображения в виде слайд-шоу. |
|
|  | [Pps](#Pps) | PPS, PowerPoint Slide Show, файлы создаются с помощью Microsoft PowerPoint для целей слайд-шоу. |
|
|  | [Pptx](#Pptx) | Файлы с расширением PPTX являются презентационными файлами, созданными популярным приложением Microsoft PowerPoint. |
|
|  | [Ppsx](#Ppsx) | PPSX, Power Point Slide Show, файлы создаются с помощью Microsoft PowerPoint 2007 и новее для целей слайд-шоу. |
|
|  | [Odp](#Odp) | Файлы с расширением ODP представляют формат презентационных файлов, используемый OpenOffice.org в стандарте OASISOpen. |
|
|  | [Otp](#Otp) | Файлы с расширением .OTP представляют шаблоны презентаций, созданные приложениями в формате стандарта OASIS OpenDocument. |
|
|  | [Potx](#Potx) | Файлы с расширением .POTX представляют шаблоны презентаций Microsoft PowerPoint, созданные с помощью Microsoft PowerPoint 2007 и новее. |
|
|  | [Pot](#Pot) | Файлы с расширением .POT представляют шаблоны файлов Microsoft PowerPoint, созданные версиями PowerPoint 97-2003. |
|
|  | [Potm](#Potm) | Файлы с расширением POTM являются шаблонами Microsoft PowerPoint с поддержкой макросов. |
|
|  | [Pptm](#Pptm) | Файлы с расширением PPTM являются презентационными файлами с поддержкой макросов, созданными с помощью Microsoft PowerPoint 2007 или более новых версий. |
|
|  | [Ppsm](#Ppsm) | Файлы с расширением PPSM представляют формат файлов слайд-шоу с поддержкой макросов, созданный с помощью Microsoft PowerPoint 2007 или новее. |
|
|  | [Fodp](#Fodp) | Файлы с расширением FODP представляют презентацию OpenDocument Flat XML. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


Конструктор сериализации


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


Файл с расширением PPT представляет файл PowerPoint, который состоит из набора слайдов для отображения в виде слайд-шоу. Он определяет двоичный формат файла, используемый Microsoft PowerPoint 97-2003.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/ppt).


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint Slide Show, файлы создаются с помощью Microsoft PowerPoint для целей слайд-шоу. Чтение и создание файлов PPS поддерживается Microsoft PowerPoint 97-2003.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/pps).


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


Файлы с расширением PPTX являются презентационными файлами, созданными популярным приложением Microsoft PowerPoint. В отличие от предыдущей версии формата презентационных файлов PPT, который был двоичным, формат PPTX основан на открытом XML-формате презентаций Microsoft PowerPoint.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/pptx).


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX, Power Point Slide Show, файлы создаются с помощью Microsoft PowerPoint 2007 и новее для целей слайд-шоу.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/ppsx).


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


Файлы с расширением ODP представляют формат презентационных файлов, используемый OpenOffice.org в стандарте OASISOpen.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/odp).


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


Файлы с расширением .OTP представляют шаблоны презентаций, созданные приложениями в формате стандарта OASIS OpenDocument.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/otp).


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


Файлы с расширением .POTX представляют шаблоны презентаций Microsoft PowerPoint, созданные с помощью Microsoft PowerPoint 2007 и новее.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/potx).


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


Файлы с расширением .POT представляют шаблоны файлов Microsoft PowerPoint, созданные версиями PowerPoint 97-2003.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/pot).


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


Файлы с расширением POTM являются шаблонами Microsoft PowerPoint с поддержкой макросов. Файлы POTM создаются в PowerPoint 2007 или более новых версиях и содержат настройки по умолчанию, которые можно использовать для создания дальнейших презентаций.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/potm).


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


Файлы с расширением PPTM являются презентационными файлами с поддержкой макросов, созданными с помощью Microsoft PowerPoint 2007 или более новых версий.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/pptm).


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


Файлы с расширением PPSM представляют формат файлов слайд-шоу с поддержкой макросов, созданный с помощью Microsoft PowerPoint 2007 или новее.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/ppsm).


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


Файлы с расширением FODP представляют собой презентацию OpenDocument Flat XML. Файл презентации сохраняется в формате OpenDocument, но использует плоский XML‑формат вместо контейнера .ZIP, применяемого в стандартных файлах .ODP.


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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
