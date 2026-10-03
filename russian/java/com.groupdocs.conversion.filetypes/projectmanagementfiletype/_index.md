---
title: "ProjectManagementFileType"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Определяет форматы файлов проекта, которые создаются программным обеспечением управления проектами, таким как Microsoft Project Primavera P6 и т.д."
type: docs
weight: 23
url: /ru/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Определяет форматы файлов проекта, которые создаются программным обеспечением управления проектами, таким как Microsoft Project, Primavera P6 и т.д. Файл проекта — это набор задач, ресурсов и их расписания, позволяющий получить измеримый результат в виде продукта или услуги.
Документы управления проектами. Включает следующие типы файлов:
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
Узнайте больше о форматах управления проектами [здесь](../https://wiki.fileformat.com/project-management).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | Конструктор сериализации |
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [Mpt](#Mpt) | Файлы шаблонов Microsoft Project содержат базовую информацию и структуру вместе с настройками документов для создания файлов .MPP. |
|
|  | [Mpp](#Mpp) | MPP — это файл данных Microsoft Project, который хранит информацию, связанную с управлением проектом, в интегрированном виде. |
|
|  | [Mpx](#Mpx) | Microsoft Exchange File Format — это ASCII‑формат файла для передачи проектной информации между Microsoft Project (MSP) и другими приложениями, поддерживающими формат MPX, такими как Primavera Project Planner, Sciforma и Timerline Precision Estimating. |
|
|  | [Xer](#Xer) | Формат файла XER — это проприетарный формат проектного файла, используемый приложением Primavera P6 для планирования и управления проектами. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Конструктор сериализации


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Файлы шаблонов Microsoft Project содержат базовую информацию и структуру вместе с настройками документов для создания файлов .MPP.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP — это файл данных Microsoft Project, который хранит информацию, связанную с управлением проектом, в интегрированном виде.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format — это ASCII‑формат файла для передачи проектной информации между Microsoft Project (MSP) и другими приложениями, поддерживающими формат MPX, такими как Primavera Project Planner, Sciforma и Timerline Precision Estimating.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


Формат файла XER — это проприетарный формат проектного файла, используемый приложением Primavera P6 для планирования и управления проектами.
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Подготовлены параметры конвертации по умолчанию для типа файла


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
