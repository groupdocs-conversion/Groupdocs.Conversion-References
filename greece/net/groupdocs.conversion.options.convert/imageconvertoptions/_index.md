---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Εικόνα."
type: docs
weight: 1950
url: /el/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Επιλογές για μετατροπή σε τύπο αρχείου Εικόνα.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`ImageConvertOptions`](../imageconvertoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Ορίζει το χρώμα φόντου όπου υποστηρίζεται από τη μορφή πηγής. |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Ρυθμίζει τη φωτεινότητα της εικόνας. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | Όταν είναι ορισμένο, περιορίζει την ανάλυση απόδοσης PDF ανά σελίδα στην εγγενή ανάλυση raster της σελίδας, ώστε μια σελίδα να μην αποδίδεται ποτέ σε υψηλότερο DPI από ό,τι περιέχει πραγματικά η ενσωματωμένη εικόνα, και εκδίδει αυτή τη σελίδα στις εγγενείς (μικρότερες) διαστάσεις εικονοστοιχείων και εγγενές DPI στην τελική έξοδο αντί να την αυξάνει στο ζητούμενο DPI. Επηρεάζονται μόνο οι σελίδες που κυριαρχούνται από εικόνα (σάρωση); οι σελίδες με κείμενο ή διανυσματικό περιεχόμενο δεν μαλακώνουν ποτέ και εκδίδονται στο ζητούμενο DPI. Παραλείπεται όταν ορίζεται ρητή έξοδος [`Width`](./width) ή [`Height`](./height). Η προεπιλογή είναι `false` (χωρίς περιορισμό· κάθε σελίδα αποδίδεται και εκδίδεται στο ζητούμενο DPI). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Ρυθμίζει την αντίθεση της εικόνας. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Περικοπή περιοχής raster εικόνας μετά τη μετατροπή |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Λειτουργία αντιστροφής εικόνας. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στον οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Υλοποιεί [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Ρυθμίζει τη γάμμα της εικόνας. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Δείχνει εάν θα μετατραπεί σε εικόνα σε κλίμακα του γκρι. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Επιθυμητό ύψος εικόνας μετά τη μετατροπή. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Επιθυμητή οριζόντια ανάλυση εικόνας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι η ανάλυση του αρχείου εισόδου ή 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Ειδικές επιλογές μετατροπής για Jpeg. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | Κατώτερο όριο ανά άξονα που εφαρμόζεται στο περιορισμένο DPI απόδοσης όταν είναι ενεργοποιημένο το [`CapResolutionToPageContent`](./capresolutiontopagecontent). Το περιορισμένο DPI δεν μειώνεται ποτέ κάτω από αυτήν την τιμή. Η προεπιλογή είναι `0` (χωρίς όριο). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Υλοποιεί [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Υλοποιεί [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Υλοποιεί [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Ειδικές επιλογές μετατροπής για Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Γωνία περιστροφής εικόνας. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Ειδικές επιλογές μετατροπής για Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Εάν `true`, η είσοδος πρώτα μετατρέπεται σε PDF και μετά στο επιθυμητό μορφότυπο. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Επιθυμητή κάθετη ανάλυση εικόνας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι η ανάλυση του αρχείου εισόδου ή 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Υλοποιεί [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Ειδικές επιλογές μετατροπής για Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Επιθυμητό πλάτος εικόνας μετά τη μετατροπή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία επιλογών. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
