---
title: "SetLicense"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Δίνει άδεια στο στοιχείο."
type: docs
weight: 30
url: /el/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Δίνει άδεια στο στοιχείο.

```csharp
public void SetLicense(Stream licenseStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseStream | Stream | Η ροή άδειας. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε μια άδεια περνώντας το Stream του αρχείου άδειας.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### Δείτε επίσης

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

Δίνει άδεια στο στοιχείο.

```csharp
public void SetLicense(string licensePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licensePath | String | Η διαδρομή της άδειας. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε μια άδεια περνώντας μια διαδρομή στο αρχείο άδειας.

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### Δείτε επίσης

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
