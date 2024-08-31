---
title: License
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Provides methods to license the component.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Provides methods to license the component. Learn more about licensing  [here][] .

**Learn more**More about licensing: [GroupDocs Licensing FAQ][here]More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing][]


[here]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isLicensed()](#isLicensed--) | Returns true if a valid license has been applied; false if the component is running in evaluation mode. |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
| [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | Licenses the component. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licenses the component. |
| [resetLicense()](#resetLicense--) |  |
### License() {#License--}
```
public License()
```


### isLicensed() {#isLicensed--}
```
public boolean isLicensed()
```


Returns true if a valid license has been applied; false if the component is running in evaluation mode.

**Returns:**
boolean
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


Licenses the component.

--------------------

> ```
> The following example demonstrates how to set a license
>  passing Stream of the license file.
>  
>  using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
>  {
>      GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
>      lic.SetLicense(licenseStream);
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseStream | com.aspose.ms.System.IO.Stream | The license stream. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


Licenses the component.

--------------------

> ```
> The following example demonstrates how to set a license
>  passing a path to the license file.
>  
>  string licensePath = "GroupDocs.Conversion.lic";
>  GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
>  lic.SetLicense(licensePath);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | java.lang.String | The license path. |

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




