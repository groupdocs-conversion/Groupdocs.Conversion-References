---
title: "Лицензия"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Предоставляет методы для лицензирования компонента."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Предоставляет методы лицензирования компонента. Узнать больше о лицензировании  [здесь][].

**Learn more**More about licensing: [GroupDocs Licensing FAQ][here]More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing][]


[here]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [License()](#License--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [isLicensed()](#isLicensed--) | Возвращает true, если применена действительная лицензия; false, если компонент работает в режиме оценки. |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
| [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | Лицензирует компонент. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Лицензирует компонент. |
| [resetLicense()](#resetLicense--) |  |
### License() {#License--}
```
public License()
```


### isLicensed() {#isLicensed--}
```
public boolean isLicensed()
```


Возвращает true, если применена действительная лицензия; false, если компонент работает в режиме оценки.

**Returns:**
boolean
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


Лицензирует компонент.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseStream | com.aspose.ms.System.IO.Stream | Поток лицензии. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


Лицензирует компонент.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| licensePath | java.lang.String | Путь к лицензии. |

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




