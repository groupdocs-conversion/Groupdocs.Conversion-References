---
title: "GetHashCode"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Funziona come funzione hash predefinita."
type: docs
weight: 20
url: /it/net/groupdocs.conversion.contracts/valueobject/gethashcode/
---
## ValueObject.GetHashCode method

Funziona come funzione hash predefinita.

```csharp
public override int GetHashCode()
```

### Valore restituito

Un codice hash per l'oggetto corrente.

### Osservazioni

Le componenti di array, lista e dizionario vengono hashate in base al loro contenuto, corrispondendo al modo in cui l'uguaglianza le confronta, così due oggetti che risultano uguali vengono hashati allo stesso modo e possono essere usati come chiavi di dizionario o membri di un set. Questo NON si estende a una componente che è un altro IEnumerable: tale componente viene hashata per riferimento, e una esposta come iteratore lazy restituisce un valore diverso ad ogni accesso, quindi un oggetto che la contiene non è affatto utilizzabile come chiave. Le collezioni nidificate sono analogamente confrontate e hashate per riferimento anziché ricorsivamente. L'altra conseguenza è che la mutazione di una collezione a cui un oggetto valore espone – aggiungere a una lista di pagine, o scrivere in un array di nomi di layout – modifica l'hash di quell'oggetto, così un'istanza già memorizzata in un contenitore hash diventa irraggiungibile. Tratta un oggetto valore come congelato una volta che è stato usato come chiave.

### IConversionConvertOptions

* class [ValueObject](../../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
