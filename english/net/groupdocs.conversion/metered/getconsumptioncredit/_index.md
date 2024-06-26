---
title: GetConsumptionCredit
second_title: GroupDocs.Conversion for .NET API Reference
description: Retrieves count of credits consumed.
type: docs
weight: 30
url: /net/groupdocs.conversion/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Retrieves count of credits consumed.

```csharp
public static decimal GetConsumptionCredit()
```

### Examples

Following example demonstrates how to retrieve count of credits consumed.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### See Also

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
