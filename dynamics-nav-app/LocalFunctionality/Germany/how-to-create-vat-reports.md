---
title: 'Gewusst wie: MwSt.-Berichte erstellen'
description: "Verschiedene Arten von MwSt.-Erklärungen können basierend auf Anforderungen konfiguriert werden. Wenn Sie dann eine MwSt buchen müssen, können Sie sie im **MwSt Bericht** Fenster erstellen und dann im elektronischen Format exportieren, das an die Anforderungen des ELMA5 Formats sich anpaßt."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 346aacbfec31cd6ee50731aa10fe2b3b82128b66
ms.contentlocale: de-de
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-create-vat-reports"></a>Gewusst wie: MwSt.-Berichte erstellen
Verschiedene Arten von MwSt.-Erklärungen können basierend auf Anforderungen konfiguriert werden. Wenn Sie dann eine MwSt buchen müssen, können Sie sie im **MwSt Bericht** Fenster erstellen und dann im elektronischen Format exportieren, das an die Anforderungen des ELMA5 Formats sich anpaßt.  

## <a name="to-create-a-vat-report"></a>Einen MwSt.-Bericht erstellen:  

1.  Alternativ wählen Sie in der rechten oberen Ecke das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben die **MwSt-Bericht** ein. Wählen Sie dann den zugehörigen Link aus.  
2.  Füllen Sie im Inforegister **Allgemein** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  

    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Nr.**|Geben Sie die Nummer der Erklärung an.<br /><br /> Je nach Art der Erklärung und der Konfiguration in Ihrem Unternehmen können Sie die automatisch generierte Nummer verwenden, eine andere Nummernserie auswählen oder eine andere Nummer manuell eingeben.|  
    |**MwSt.-Berichtstyp**|Wählen Sie die entsprechende MwSt Berichtstyp aus. Die Standardeinstellung ist **Standard**. Wenn der Bericht eine Aktualisierung auf ein existierendes Bericht ist, wählen Sie **Korrektur** aus.|  
    |**Handelstyp**|Geben Sie die Art des Handels an, den der Bericht beschreibt. Der Standardwert ist **Verkauf**. Andere Optionen sind **Einkäufe** oder **Beides**.|  
    |**Startdatum**|Geben Sie das Startdatum der Berichtsperiode an.|  
    |**Enddatum**|Geben Sie das Enddatum des Erklärungszeitraums an.|  
    |**EU-Waren/-Dienstleistungen**|Geben Sie an, ob der Bericht sich auf **Waren**, **Dienste** oder beides bezieht. Der Standardwert ist **Beides**.|  
    |**Berichtsperiodentyp**|Geben Sie den Zeitraum an, den der Bericht umfasst:<br /><br /> -   Monat<br />-   Quartal<br />-   Jahr<br />-   Zwei-Monatlich|  
    |**Berichtsperiodennummer**|Geben Sie die Nummer der Mehrwertsteuerperiode an.|  
    |**Berichtsjahr**|Gibt das Jahr an, das der MwSt.-Bericht abdeckt.|  
    |**Verarbeitungsdatum**|Gibt das Datum an, an dem der MwSt.-Bericht erstellt wurde.|  

3.  Füllen Sie im Inforegister **Genehmigen** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  

    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Bereich zum Abzeichnen**|Gibt den Ort an, an dem der MwSt.-Bericht unterzeichnet wurde.|  
    |**Datum des Abzeichnens**|Gibt das Datum an, an dem der MwSt.-Bericht unterzeichnet wurde.|  
    |**Unterzeichnet von Mitarbeiter Nr.**|Geben Sie die Nummer des Mitarbeiters an, der den MwSt-Bericht aus der Lookupliste unterschrieben hat.|  
    |**Erstellt von Mitarbeiter Nr.**|Geben Sie die Nummer des Mitarbeiters an, der den MwSt-Bericht aus der Lookupliste erstellt hat.|  

4.  Jetzt müssen Sie die Mehrwertsteuerposten importieren, die in dieser MwSt.-Erklärung enthalten sein müssen.  
5. Wählen Sie die Aktion **Mahnungszeile vorschlagen**.  

Dadurch werden dem Fenster MwSt-Einträge hinzugefügt. Sie können optional für jede Zeile im Feld **Betrag** ein Drilldown durchführen, um die Mehrwertsteuerposten anzuzeigen, aus denen die Zeile resultiert.  

Nachdem Sie die MwSt.-Erklärung erstellt haben, müssen Sie sie an die Steuerbehörden übermitteln.  

## <a name="to-submit-a-vat-report"></a>Einen MwSt.-Bericht übermitteln:  

1.  Wählen Sie im Fenster **MwSt-Bericht** die Aktion **Freigabe** aus.  
2.  Bestätigen Sie, dass Sie den Bericht freigeben möchten.  

    [!INCLUDE[navnow](../../includes/navnow_md.md)] prüft, ob die MwSt.-Erklärung korrekt eingerichtet ist. Wenn die Prüfung fehlschlägt, werden die Fehler im Fenster **MwSt-Bericht Fehlerprotokoll** angezeigt, sodass Sie entsprechende Änderungen vornehmen können. Beispielsweise wird ein Fehler angezeigt, wenn Sie versuchen, eine Standard-MwSt.-Erklärung freizugeben, aber Sie der Erklärung noch keine Zeilen hinzugefügt haben.  

    Wenn Sie eine MwSt.-Erklärung als freigegeben kennzeichnen, ist sie nicht mehr editierbar. Wenn Sie die Erklärung ändern müssen, nachdem Sie sie als freigegeben gekennzeichnet haben, müssen Sie sie zuerst erneut öffnen.  

3.  Wählen Sie auf der Registerkarte die Aktion **Exportieren**, um einen MwSt-Bericht aus EU- Ausfuhr-Listendaten im Format ELMA5 zu erstellen. Speichern Sie eine Kopie des Berichtes, der den gewünschten Namen hat, der durch ELMA5 angegeben ist.  

    Sie können die Erklärung jetzt an die Steuerbehörden senden.  

4.  Wählen Sie die Akltion **Als Übermittelt markieren** aus.  

## <a name="see-also"></a>Siehe auch  
 [Gewusst wie: Korrigieren von MwSt-Berichten](how-to-correct-vat-reports.md)   
 [Vorgehensweise: Einrichten von MwSt.-Berichten](how-to-set-up-vat-reports.md)

