---
title: ImageConvertOptions
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Επιλογές για μετατροπή σε τύπο αρχείου εικόνας.
type: docs
weight: 1630
url: /el/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Επιλογές για μετατροπή σε τύπο αρχείου εικόνας.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Αρχικοποιεί νέα παρουσία του[`ImageConvertOptions`](../imageconvertoptions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Ορίζει το χρώμα φόντου όπου υποστηρίζεται από τη μορφή πηγής |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Προσαρμόζει τη φωτεινότητα της εικόνας. |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Προσαρμόζει την αντίθεση εικόνας. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Λειτουργία αναστροφής εικόνας. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στο οποίο θα πρέπει να μετατραπεί το έγγραφο εισόδου. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στο οποίο θα πρέπει να μετατραπεί το έγγραφο εισόδου. |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Προσαρμόζει το γάμμα εικόνας. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Υποδεικνύει εάν θα μετατραπεί σε εικόνα σε κλίμακα του γκρι. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Επιθυμητό ύψος εικόνας μετά τη μετατροπή. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Επιθυμητή οριζόντια ανάλυση εικόνας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι η ανάλυση του αρχείου εισόδου ή 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Επιλογές μετατροπής ειδικά για Jpeg. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Ο αριθμός σελίδας από τον οποίο θα ξεκινήσει η μετατροπή. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Η λίστα των ευρετηρίων σελίδων προς μετατροπή. Θα πρέπει να καθοριστεί για τη μετατροπή συγκεκριμένων σελίδων. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Αριθμός σελίδων για μετατροπή ξεκινώντας από`Αριθμός σελίδας` . |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Επιλογές μετατροπής ειδικά για Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Γωνία περιστροφής εικόνας. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Επιλογές μετατροπής για συγκεκριμένες Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Αν`αληθής` , η είσοδος μετατρέπεται πρώτα σε PDF και μετά στην επιθυμητή μορφή. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Επιθυμητή κατακόρυφη ανάλυση εικόνας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι η ανάλυση του αρχείου εισόδου ή 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Ειδικές επιλογές υδατογραφήματος |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Επιλογές μετατροπής ειδικών Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Επιθυμητό πλάτος εικόνας μετά τη μετατροπή. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία επιλογών. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Εξυπηρετεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* χώρος ονομάτων [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
