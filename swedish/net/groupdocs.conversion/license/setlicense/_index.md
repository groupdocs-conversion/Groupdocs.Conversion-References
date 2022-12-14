---
title: SetLicense
second_title: GroupDocs.Conversion for .NET API Referens
description: Licensierar komponenten.
type: docs
weight: 20
url: /sv/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licensierar komponenten.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseStream | Stream | Licensströmmen. |

### Exempel

Följande exempel visar hur man ställer in en license som passerar Stream av licensfilen.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### Se även

* class [License](../../license)
* namnutrymme [GroupDocs.Conversion](../../license)
* hopsättning [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

Licensierar komponenten.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licensePath | String | Licensvägen. |

### Exempel

Följande exempel visar hur man ställer in en licens genom att skicka en sökväg till licensfilen.

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### Se även

* class [License](../../license)
* namnutrymme [GroupDocs.Conversion](../../license)
* hopsättning [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
