---
title: "DiagramFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет документы диаграмм."
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Определяет документы Diagram. Включает следующие типы: [Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vdw), [Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vdx), [Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsd), [Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsdm), [Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsdx), [Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vss), [Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vssm), [Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vssx), [Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vst), [Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vstm), [Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vstx), [Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsx), [Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vtx).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DiagramFileType()](#DiagramFileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [Vsd](#Vsd) | Файлы VSD — это чертежи, созданные с помощью приложения Microsoft Visio для представления разнообразных графических объектов и их взаимосвязей. |
| [Vsdx](#Vsdx) | Файлы с расширением .VSDX представляют формат файлов Microsoft Visio, введённый, начиная с Microsoft Office 2013. |
| [Vss](#Vss) | VSS — это файлы шаблонов, созданные в Microsoft Visio 2007 и более ранних версиях. |
| [Vst](#Vst) | Файлы с расширением VST — это векторные изображения, созданные в Microsoft Visio и служащие шаблоном для создания последующих файлов. |
| [Vsx](#Vsx) | Файлы с расширением .VSX относятся к шаблонам, состоящим из чертежей и фигур, используемых для создания диаграмм в Microsoft Visio. |
| [Vtx](#Vtx) | Файл с расширением VTX — это шаблон чертежа Microsoft Visio, сохранённый на диск в формате XML. |
| [Vdw](#Vdw) | VDW — это формат файла Visio Graphics Service, который определяет потоки и хранилища, необходимые для рендеринга веб‑чертежа. |
| [Vdx](#Vdx) | Любой чертеж или диаграмма, созданные в Microsoft Visio, но сохранённые в формате XML, имеют расширение .VDX. |
| [Vssx](#Vssx) | Файлы с расширением .VSSX являются шаблонами чертежей, созданными в Microsoft Visio 2013 и более новых версиях. |
| [Vstx](#Vstx) | Файлы с расширением VSTX являются шаблонами чертежей, созданными в Microsoft Visio 2013 и более новых версиях. |
| [Vsdm](#Vsdm) | Файлы с расширением VSDM являются файлами чертежей, созданными в приложении Microsoft Visio, которое поддерживает макросы. |
| [Vssm](#Vssm) | Файлы с расширением .VSSM являются файлами шаблонов Microsoft Visio, которые поддерживают макросы. |
| [Vstm](#Vstm) | Файлы с расширением VSTM являются шаблонными файлами, созданными в Microsoft Visio и поддерживающими макросы. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Конструктор сериализации

### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


Файлы VSD — это чертежи, созданные в приложении Microsoft Visio для представления разнообразных графических объектов и их взаимосвязей. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vsd

### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


Файлы с расширением .VSDX представляют формат файлов Microsoft Visio, введённый, начиная с Microsoft Office 2013. Он был разработан для замены бинарного формата .VSD, поддерживаемого более ранними версиями Microsoft Visio. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vsdx

### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS — это файлы шаблонов, созданные в Microsoft Visio 2007 и более ранних версиях. Шаблоны предоставляют объекты чертежей, которые можно включать в чертеж .VSD Visio. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vss

### Vst {#Vst}
```
public static final DiagramFileType Vst
```


Файлы с расширением VST — это векторные изображения, созданные в Microsoft Visio и используемые как шаблоны для создания последующих файлов. Эти шаблонные файлы находятся в бинарном формате и содержат макет и настройки по умолчанию, используемые при создании новых чертежей Visio. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vst

### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


Файлы с расширением .VSX относятся к шаблонам, состоящим из чертежей и фигур, используемых для создания диаграмм в Microsoft Visio. Файлы VSX сохраняются в формате XML и поддерживались до Visio 2013. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vsx

### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


Файл с расширением VTX — это шаблон чертежа Microsoft Visio, сохраняемый на диск в формате XML. Шаблон предназначен для предоставления файла с базовыми настройками, которые можно использовать для создания нескольких файлов Visio с одинаковыми параметрами. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vtx

### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW — это формат файлов Visio Graphics Service, определяющий потоки и хранилища, необходимые для визуализации веб‑чертежа. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/web/vdw

### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Любой чертеж или диаграмма, созданные в Microsoft Visio, но сохранённые в формате XML, имеют расширение .VDX. XML‑файл чертежа Visio создаётся в программном обеспечении Visio, разработанном Microsoft. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vdx

### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


Файлы с расширением .VSSX являются шаблонами чертежей, созданными в Microsoft Visio 2013 и более новых версиях. Формат файлов VSSX можно открыть в Visio 2013 и более новых версиях. Файлы Visio известны представлением разнообразных элементов чертежа, таких как набор фигур, соединителей, блок‑схем, сетевых схем, UML‑диаграмм. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vssx

### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


Файлы с расширением VSTX являются шаблонами чертежей, созданными в Microsoft Visio 2013 и более новых версиях. Эти файлы VSTX предоставляют отправную точку для создания чертежей Visio, сохраняемых как файлы .VSDX, с макетом и настройками по умолчанию. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vstx

### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


Файлы с расширением VSDM являются файлами чертежей, созданными в приложении Microsoft Visio, поддерживающем макросы. Файлы VSDM — это чертежи OPC/XML, похожие на VSDX, но также предоставляющие возможность выполнять макросы при открытии файла. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vsdm

### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


Файлы с расширением .VSSM являются файлами шаблонов Microsoft Visio, поддерживающими макросы. При открытии файла VSSM можно выполнять макросы для достижения нужного форматирования и размещения фигур в диаграмме. Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vssm

### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


Файлы с расширением VSTM являются шаблонными файлами, созданными в Microsoft Visio и поддерживающими макросы. В отличие от файлов VSDX, файлы, созданные из шаблонов VSTM, могут выполнять макросы, разработанные на языке Visual Basic for Applications (VBA). Узнайте больше об этом формате файлов [здесь][].


[here]: https://wiki.fileformat.com/image/vstm

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
