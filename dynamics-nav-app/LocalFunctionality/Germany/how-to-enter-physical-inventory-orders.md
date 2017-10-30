---
title: "Gewusst wie: Eingeben von Inventuraufträgen"
description: "Auf Anwendungsebene ist ein Inventurauftrag ein vollständiger Beleg, der aus einem Inventurauftragskopf und einigen Inventurauftragszeilen besteht. Die Informationen im Inventurauftragskopf geben an, wie die Inventur durchgeführt werden soll. Der Kopf kann manuell ausgefüllt werden. Sie können einen Inventurauftrag erstellen und ihn mindestens einer Inventurerfassung zuordnen."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: e8305163e1d6fb2d9cfad26322115d4c16291a6f
ms.contentlocale: de-de
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enter-physical-inventory-orders"></a>Gewusst wie: Eingeben von Inventuraufträgen
Auf Anwendungsebene ist ein Inventurauftrag ein vollständiger Beleg, der aus einem Inventurauftragskopf und einigen Inventurauftragszeilen besteht. Die Informationen im Inventurauftragskopf geben an, wie die Inventur durchgeführt werden soll. Der Kopf kann manuell ausgefüllt werden. Sie können einen Inventurauftrag erstellen und ihn mindestens einer Inventurerfassung zuordnen.  
  
 Die Inventurauftragszeilen enthalten Informationen über die Artikel und deren Lagerorte. Sie können Inventurauftragszeilen manuell erstellen oder diese durch die Anwendung automatisch erzeugen lassen. Zu diesem Zweck stehen Stapelverarbeitungsfunktionen zur Verfügung.  
  
 Bevor Sie mit der Erstellung von Inventuraufträgen beginnen können, müssen verschiedene Eigenschaften für die Inventur eingerichtet werden. Weitere Informationen finden Sie unter [Vorgehensweise: Inventurdokumente einrichten](how-to-set-up-physical-inventory-documents.md)  
  
### <a name="to-create-a-physical-inventory-order"></a>So erstellen Sie einen Inventurauftrag  
  
1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol „Nach Seite oder Bericht suchen”"), geben Sie **Bestandsauftrag** ein, und wählen Sie dann den zugehörigen Link aus.  
  
2.  Wählen Sie auf der Registerkarte **Start** die Option **Neu** aus.  
  
3.  Füllen Sie die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  
  
    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Beschreibung**|Legt eine Beschreibung für den Inventurauftrag fest.|  
    |**Lagerortcode**|Legt den Lagerortcode für den Artikel in der Bestellzeile fest.|  
    |**Verantwortlich**|Wählen Sie hier den Code für die Person aus, die für die Entnahme von Lagerbestand zuständig ist.<br /><br /> Optional können Sie diese Informationen später hinzufügen.|  
    |**Bestelldatum**|Legt das Erstellungsdatum für den Inventurauftrag fest.|  
    |**Buchungsdatum**|Legt das Buchungsdatum für den Inventurauftrag fest.|  
  
 Diese können manuell erstellt werde oder [!INCLUDE[navnow](../../includes/navnow_md.md)] kann neue physische Bestandaufträge automatisch erstellen. Für die automatische Erzeugung neuer Inventurauftragszeilen stehen zwei Möglichkeiten zur Verfügung:  
  
-   Sie können neue Inventurauftragszeilen auf Basis des Lagerbestands wie Artikel und Artikelposten erstellen.  
  
-   Sie können neue Inventurauftragszeilen mithilfe der Kopierfunktion auf Basis vorhandener Inventuraufträge erstellen.  
  
 Beide Stapelverarbeitungen prüfen, ob bereits eine Inventurauftragszeile mit den gleichen Werten in den 4 Feldern Artikelnr., Variantencode, Lagerortcode und Lagerplatzcode vorhanden ist. In diesem Fall fügt die Anwendung keine neue Zeile automatisch ein, um doppelte Zeilen zu vermeiden.  
  
### <a name="to-automatically-add-physical-inventory-order-lines-from-inventory"></a>So fügen Sie automatisch Inventurauftragszeilen aus dem Lagerbestand hinzu  
  
1.  Wählen Sie im Fenster **Physischer Lagerauftrag** auf der Registerkarte **Aktionen** in der Gruppe **Funktionen** die Option **Zeilen berechnen** aus.  
  
2.  Füllen Sie im Fenster **Inventurauftragszeilen berech.** im Inforegister **Optionen** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  
  
    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Erwartete Menge berechnen**|Wählen Sie diese Option aus, um die Daten zur erwarteten Menge für neu erstellte Inventurauftragszeilen zu berechnen und einzufügen.|  
    |**Artikel nicht auf Lager**|Wählen Sie diese Option aus, um Inventurauftragszeilen für Artikel einzufügen, die im Feld **Erwartete Menge** den Wert null enthalten.|  
  
3.  Optional im Inforegister **Artikel** wählen Sie die entsprechenden Filter aus, und wählen Sie dann die Schaltfläche **OK** aus.  
  
4.  Wählen Sie die Schaltfläche **OK**, wenn der Batchauftrag beendet ist.  
  
### <a name="to-automatically-add-physical-inventory-order-lines-by-copying-documents"></a>So fügen Sie automatisch Inventurauftragszeilen aus dem Lagerbestand hinzu, indem Sie Dokumente kopieren.  
  
1.  Wählen Sie im Fenster **Physischer Lagerauftrag** auf der Registerkarte **Aktionen** in der Gruppe **Funktionen** die Option **Dokument kopieren** aus.  
  
2.  Füllen Sie im Fenster **Inventurauftragszeilen kopieren** im Inforegister **Optionen** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  
  
    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Belegart**|Gibt die Art des Belegs an, der kopiert werden soll.|  
    |**Belegnr.**|Gibt die Art des Belegs an, der kopiert werden soll.|  
    |**Erwartete Menge berechnen**|Wählen Sie diese Option aus, um die Daten zur erwarteten Menge für neu erstellte Inventurauftragszeilen zu berechnen und einzufügen.|  
  
3.  Wählen Sie die Schaltfläche **OK**, wenn der Batchauftrag beendet ist.  
  
     Sie können die Stapelverarbeitung mehrmals ausführen. Wenn im Inventurauftrag bereits Zeilen vorhanden sind, hängt die Anwendung die neuen Zeilen an das Ende des Belegs an.  
  
 Sie können einen Inventurauftrag erstellen und ihn mindestens einer Inventurerfassung zuordnen. Dort können Sie die Zählmengen dokumentieren. Weitere Informationen finden Sie unter [Vorgehensweise: Führen Sie physische Inventuren aus](how-to-create-a-physical-inventory-recording.md).  
  
 Die erwarteten Mengen aus den Inventurauftragszeilen können mit den (gezählten) Mengen aus den Inventurerfassungszeilen verglichen und dokumentiert werden. Anschließend können die Inventurdifferenzen gebucht werden.  
  
## <a name="see-also"></a>Siehe auch  
 [Inventurbelege](physical-inventory-documents.md)   
 [So geben Sie Dimensionen für den Inventurauftrag ein](how-to-enter-dimensions-for-physical-inventory-orders.md)   
 [So zeigen Sie doppelte Inventurauftragszeilen an](how-to-view-physical-inventory-order-lines.md)   
 [So erstellen Sie eine physische Inventurerfassung](how-to-create-a-physical-inventory-recording.md)   
 [Gewusst wie: Berechnen der verfügbaren Menge für einen Inventurauftrag](how-to-calculate-quantity-on-hand-for-a-physical-inventory-order.md)   
 [Gewusst wie: Buchen von Inventuraufträgen](how-to-post-physical-inventory-orders.md)   
 Inventurauftragszeilen berech.   
 Inventurauftrag kopieren
