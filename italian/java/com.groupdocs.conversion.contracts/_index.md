---
title: "com.groupdocs.conversion.contracts"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Lo spazio dei nomi GroupDocs.Conversion.Contracts fornisce membri per istanziare e rilasciare documenti di output, gestire le sostituzioni dei caratteri, ecc."
type: docs
weight: 12
url: /it/java/com.groupdocs.conversion.contracts/
---

Il namespace GroupDocs.Conversion.Contracts fornisce membri per istanziare e rilasciare il documento di output, gestire le sostituzioni dei font, ecc.



## Classi

| Classe | Descrizione |
| --- | --- |
| [ConversionPair](../com.groupdocs.conversion.contracts/conversionpair) | Rappresenta una coppia di conversione |
| [Enumeration](../com.groupdocs.conversion.contracts/enumeration) | Classe di enumerazione generica. |
| [FontSubstitute](../com.groupdocs.conversion.contracts/fontsubstitute) | Descrive la sostituzione per i caratteri mancanti. |
| [PossibleConversions](../com.groupdocs.conversion.contracts/possibleconversions) | Rappresenta una mappatura delle coppie di conversione supportate per un formato di file sorgente specifico |
| [TargetConversion](../com.groupdocs.conversion.contracts/targetconversion) | Rappresenta la conversione di destinazione possibile e un flag che indica se è primaria o secondaria |
| [ValueObject](../com.groupdocs.conversion.contracts/valueobject) | Classe astratta di oggetto valore. |

## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [ConvertOptionsProvider](../com.groupdocs.conversion.contracts/convertoptionsprovider) | Descrive il delegato per fornire le opzioni di conversione per un documento sorgente specifico. |
| [ConvertedDocumentStream](../com.groupdocs.conversion.contracts/converteddocumentstream) | Descrive il delegato per ricevere lo stream del documento convertito. |
| [ConvertedPageStream](../com.groupdocs.conversion.contracts/convertedpagestream) | Descrive il delegato per ricevere lo stream della pagina convertita. |
| [ConverterSettingsProvider](../com.groupdocs.conversion.contracts/convertersettingsprovider) | Fornitore per ConverterSettings |
| [DocumentStreamProvider](../com.groupdocs.conversion.contracts/documentstreamprovider) | Fornitore per InputStream |
| [DocumentStreamsProvider](../com.groupdocs.conversion.contracts/documentstreamsprovider) | Fornitore per array di InputStream |
| [IDocument](../com.groupdocs.conversion.contracts/idocument) | Interfaccia per i documenti |
| [SaveDocumentStream](../com.groupdocs.conversion.contracts/savedocumentstream) | Descrive il delegato per salvare il documento convertito in uno stream di output. |
| [SaveDocumentStreamForFileType](../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Descrive il delegato per salvare il documento convertito in uno stream. |
| [SavePageStream](../com.groupdocs.conversion.contracts/savepagestream) | Descrive il delegato per salvare la pagina del documento convertito in uno stream. |
| [SavePageStreamForFileType](../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Descrive il delegato per salvare la pagina del documento convertito in uno stream. |
