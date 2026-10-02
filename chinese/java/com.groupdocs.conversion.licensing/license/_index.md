---
title: "许可证"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "提供用于授权组件的方法。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

提供对组件进行授权的方法。了解更多关于授权的信息
[here](../https://purchase.groupdocs.com/faqs/licensing)
.
**Learn more** More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License()](#License--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLicensed()](#isLicensed--) | 如果已应用有效许可证则返回 true；如果组件处于评估模式则返回 false。 |
|
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
|  | [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | 授权组件。 |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | 授权组件。 |
|
| [resetLicense()](#resetLicense--) |  |
### License() {#License--}
```
public License()
```


### isLicensed() {#isLicensed--}
```
public boolean isLicensed()
```


如果已应用有效许可证则返回 true；如果组件处于评估模式则返回 false。


**Returns:**
布尔
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


授权组件。

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set a license
>  passing Stream of the license file.
>   using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
>  {
>      GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
>      lic.SetLicense(licenseStream);
>  }
>  
>  
> ```

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licenseStream | com.aspose.ms.System.IO.Stream | 许可证流。 |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


授权组件。

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set a license
>  passing a path to the license file.
>   string licensePath = "GroupDocs.Conversion.lic";
>  GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
>  lic.SetLicense(licensePath);
>  
>  
> ```

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licensePath | java.lang.String | 许可证路径。 |
|

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




