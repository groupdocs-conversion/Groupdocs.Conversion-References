---
title: "ProjectManagementFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义由项目管理软件（如 Microsoft Project、Primavera P6 等）创建的项目文件格式。"
type: docs
weight: 23
url: /zh/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

定义由项目管理软件（如 Microsoft Project、Primavera P6 等）创建的项目文件格式。项目文件是任务、资源及其调度的集合，用于获得以产品或服务形式的可衡量输出。
项目管理文档。包括以下文件类型：
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
了解更多关于项目管理格式的信息，请点击[这里](../https://wiki.fileformat.com/project-management).

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Mpt](#Mpt) | Microsoft Project 模板文件包含基本信息和结构以及用于创建 .MPP 文件的文档设置。 |
|
|  | [Mpp](#Mpp) | MPP 是 Microsoft Project 数据文件，以集成方式存储与项目管理相关的信息。 |
|
|  | [Mpx](#Mpx) | Microsoft Exchange 文件格式是一种 ASCII 文件格式，用于在 Microsoft Project (MSP) 与其他支持 MPX 文件格式的应用程序（如 Primavera Project Planner、Sciforma 和 Timerline Precision Estimating）之间传输项目信息。 |
|
|  | [Xer](#Xer) | XER 文件格式是一种专有的项目文件格式，供 Primavera P6 项目规划和管理应用程序使用。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


序列化构造函数


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Microsoft Project 模板文件包含基本信息和结构以及用于创建 .MPP 文件的文档设置。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP 是 Microsoft Project 数据文件，以集成方式存储与项目管理相关的信息。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange 文件格式是一种 ASCII 文件格式，用于在 Microsoft Project (MSP) 与其他支持 MPX 文件格式的应用程序（如 Primavera Project Planner、Sciforma 和 Timerline Precision Estimating）之间传输项目信息。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


XER 文件格式是一种专有的项目文件格式，供 Primavera P6 项目规划和管理应用程序使用。
了解更多关于此文件格式的信息，请点击[这里](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


为文件类型准备了默认转换选项


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
