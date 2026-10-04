---
title: "SetLicense"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Лицензирует компонент."
type: docs
weight: 30
url: /ru/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Лицензирует компонент.

```csharp
public void SetLicense(Stream licenseStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseStream | Stream | Поток лицензии. |

### Примеры

В следующем примере демонстрируется, как установить лицензию, передавая Stream файла лицензии.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### См. также

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

Лицензирует компонент.

```csharp
public void SetLicense(string licensePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| licensePath | String | Путь к лицензии. |

### Примеры

В следующем примере демонстрируется, как установить лицензию, передавая путь к файлу лицензии.

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### См. также

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
