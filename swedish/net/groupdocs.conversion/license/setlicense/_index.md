---
title: "SetLicense"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Licensierar komponenten."
type: docs
weight: 30
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

Följande exempel visar hur man sätter en licens genom att skicka Stream för licensfilen.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### Se även

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

Licensierar komponenten.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licensePath | String | Licenssökvägen. |

### Exempel

Följande exempel visar hur man sätter en licens genom att ange en sökväg till licensfilen.

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### Se även

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
