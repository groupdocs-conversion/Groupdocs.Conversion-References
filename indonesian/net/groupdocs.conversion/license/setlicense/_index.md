---
title: "SetLicense"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Melisensikan komponen."
type: docs
weight: 30
url: /id/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Melisensikan komponen.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseStream | Stream | Aliran lisensi. |

### Contoh

Contoh berikut menunjukkan cara mengatur lisensi dengan melewatkan Stream dari file lisensi.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### Lihat Juga

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

Melisensikan komponen.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licensePath | String | Jalur lisensi. |

### Contoh

Contoh berikut menunjukkan cara mengatur lisensi dengan melewatkan jalur ke file lisensi.

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### Lihat Juga

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
