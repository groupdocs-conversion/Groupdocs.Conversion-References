---
title: "FontSubstitute"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "描述缺失字体的替代方案。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

描述缺失字体的替代方案。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | 实例化新的字体替代对。 |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | 原始字体名称。 |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | 替代字体名称。 |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


实例化新的字体替代对。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | originalFont | java.lang.String | 源文档中的字体。 |
|
|  | substituteWith | java.lang.String | 用于替换 originalFont 的字体。 |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


原始字体名称。


**Returns:**
java.lang.String - 原始字体名称。

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


替代字体名称。


**Returns:**
java.lang.String - 替代字体名称。

