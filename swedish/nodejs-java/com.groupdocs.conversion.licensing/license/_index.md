---
title: "Licens"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Tillhandahåller metoder för att licensiera komponenten."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Tillhandahåller metoder för att licensiera komponenten. Läs mer om licensiering  [här][].

**Learn more**More about licensing: [GroupDocs Licensing FAQ][here]More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing][]


[here]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [License()](#License--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isLicensed()](#isLicensed--) | Returnerar true om en giltig licens har tillämpats; false om komponenten körs i utvärderingsläge. |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
| [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | Licensierar komponenten. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licensierar komponenten. |
| [resetLicense()](#resetLicense--) |  |
### License() {#License--}
```
public License()
```


### isLicensed() {#isLicensed--}
```
public boolean isLicensed()
```


Returnerar true om en giltig licens har tillämpats; false om komponenten körs i utvärderingsläge.

**Returns:**
boolean
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


Licensierar komponenten.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseStream | com.aspose.ms.System.IO.Stream | Licensströmmen. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


Licensierar komponenten.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licensePath | java.lang.String | Licenssökvägen. |

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




