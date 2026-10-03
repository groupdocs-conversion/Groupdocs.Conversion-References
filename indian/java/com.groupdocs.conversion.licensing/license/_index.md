---
title: "License"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "घटक को लाइसेंस करने के लिए विधियाँ प्रदान करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

घटक को लाइसेंस करने के लिए विधियां प्रदान करता है। लाइसेंसिंग के बारे में अधिक जानें
[here](../https://purchase.groupdocs.com/faqs/licensing)
.
**Learn more** More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [License()](#License--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [isLicensed()](#isLicensed--) | यदि वैध लाइसेंस लागू किया गया है तो true लौटाता है; यदि घटक मूल्यांकन मोड में चल रहा है तो false लौटाता है। |
|
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
|  | [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | घटक को लाइसेंस करता है। |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | घटक को लाइसेंस करता है। |
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


यदि वैध लाइसेंस लागू किया गया है तो true लौटाता है; यदि घटक मूल्यांकन मोड में चल रहा है तो false लौटाता है।


**Returns:**
बूलियन
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


घटक को लाइसेंस करता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | licenseStream | com.aspose.ms.System.IO.Stream | लाइसेंस स्ट्रीम। |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


घटक को लाइसेंस करता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | licensePath | java.lang.String | लाइसेंस पथ। |
|

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




