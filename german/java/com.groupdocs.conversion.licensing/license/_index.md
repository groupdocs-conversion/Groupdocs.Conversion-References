---
title: "Lizenz"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt Methoden zum Lizenzieren der Komponente bereit."
type: docs
weight: 10
url: /de/java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Stellt Methoden zum Lizenzieren der Komponente bereit. Erfahren Sie mehr über Lizenzierung
[here](../https://purchase.groupdocs.com/faqs/licensing)
.
**Learn more** More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License()](#License--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isLicensed()](#isLicensed--) | Gibt true zurück, wenn eine gültige Lizenz angewendet wurde; false, wenn die Komponente im Evaluierungsmodus läuft. |
|
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
|  | [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | Lizenziert die Komponente. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Lizenziert die Komponente. |
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


Gibt true zurück, wenn eine gültige Lizenz angewendet wurde; false, wenn die Komponente im Evaluierungsmodus läuft.


**Returns:**
boolean
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


Lizenziert die Komponente.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | licenseStream | com.aspose.ms.System.IO.Stream | Der Lizenz-Stream. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


Lizenziert die Komponente.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | licensePath | java.lang.String | Der Lizenzpfad. |
|

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




