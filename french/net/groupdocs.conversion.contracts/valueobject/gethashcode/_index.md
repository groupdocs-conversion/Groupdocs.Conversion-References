---
title: "GetHashCode"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Servir de fonction de hachage par défaut."
type: docs
weight: 20
url: /fr/net/groupdocs.conversion.contracts/valueobject/gethashcode/
---
## ValueObject.GetHashCode method

Servir de fonction de hachage par défaut.

```csharp
public override int GetHashCode()
```

### Valeur de retour

Un code de hachage pour l'objet actuel.

### Remarques

Les composants de tableau, de liste et de dictionnaire sont hachés selon leur contenu, correspondant à la façon dont l’égalité les compare, de sorte que deux objets qui sont égaux sont également hachés de la même manière et peuvent être utilisés comme clés de dictionnaire ou membres d’ensemble. Cela ne s’étend PAS à un composant qui est un autre IEnumerable : un tel composant est haché par référence, et celui exposé comme un itérateur paresseux renvoie une valeur différente à chaque accès, de sorte qu’un objet le contenant n’est pas du tout utilisable comme clé. Les collections imbriquées sont de même comparées et hachées par référence plutôt que récursivement. L’autre conséquence est que la mutation d’une collection exposée par un objet valeur – ajouter à une liste de pages, ou écrire dans un tableau de noms de mise en page – modifie le hachage de cet objet, ainsi une instance déjà stockée dans un conteneur de hachage devient inatteignable. Traitez un objet valeur comme figé une fois qu’il a été utilisé comme clé.

### Voir aussi

* class [ValueObject](../../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
