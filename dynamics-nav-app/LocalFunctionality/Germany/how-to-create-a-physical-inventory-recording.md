---
title: So erstellen Sie eine physische Inventurerfassung
description: "Nachdem Sie einen Inventurauftrag und die zugehörigen Zeilen erstellt haben, können Sie eine neue Inventurauftragserfassung für diese Inventur erstellen."
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
ms.openlocfilehash: c4e53ff7d6ad350720e3e577c9aa18f52c14ca33
ms.contentlocale: de-de
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-a-physical-inventory-recording"></a>So erstellen Sie eine physische Inventurerfassung
Nachdem Sie einen Inventurauftrag und die zugehörigen Zeilen erstellt haben, können Sie eine neue Inventurauftragserfassung für diese Inventur erstellen.  
  
 Sie können manuell eine physische Inventurerfassung erstellen. Dies erweist sich ggf. als nützlich, wenn die Verwendung von Inventurlisten nicht erforderlich ist und/oder wenn die Lagerbestandsdaten mithilfe eines Scanners ermittelt werden. Sie können eine Inventurerfassung auch dann manuell erstellen, wenn der zugehörige Inventurauftrag keine Zeilen aufweist. Nach Abschluss der Inventurerfassung erzeugt die Anwendung die erforderlichen Inventurauftragszeilen automatisch. Dies kann beispielsweise bei permanenten Inventuren nützlich sein.  
  
 In den meisten Fällen verwenden Sie jedoch einen Batchauftrag, um Lagerbestand zu erfassen. Basierend auf der Inventurerfassung können Sie eine Liste drucken, um die Inventur durchzuführen und die Ergebnisse zu notieren. Anschließend können die Ergebnisse vom Papier in die Inventurerfassungszeilen übertragen werden.  
  
### <a name="to-create-a-physical-inventory-recording"></a>So erstellen Sie eine Inventurerfassung  
  
1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol „Nach Seite oder Bericht suchen”"), geben Sie **Bestandsauftrag** ein, und wählen Sie dann den zugehörigen Link aus.  
  
2.  Wählen Sie den Inventurauftrag aus, für den Sie eine Inventurerfassung erstellen möchten, klicken Sie auf **Startseite** und anschließend auf **Bearbeiten**.  
  
3.  Um eine Inventurerfassung, auf der Registerkarte **Startseite**, in der Gruppe **Verarbeiten** zu erstellen, wählen Sie **Neue Erfassung erstellen**.  
  
4.  Füllen Sie im Fenster **Neue Inventurerfassung erst.** im Inforegister **Optionen** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  
  
    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Nur nicht erfasste Zeilen**|Wählen Sie diese Option aus, um nur dann eine neue Inventurerfassungszeile zu generieren, falls die Daten in keiner anderen Inventurerfassungszeile vorhanden sind.|  
    |**Erfassung ohne Auftrag erlaubt**|Wählen Sie diese Option aus, um eine neue Inventurerfassungszeile zu generieren.|  
  
5.  Klicken Sie auf die Schaltfläche **OK**, um den Batchauftrag zu starten.  
  
6.  Wählen Sie auf der Registerkarte **Navigieren** die Option **Aufzeichnen** aus. Das Fenster "Inventurerfassung" wird angezeigt. Wählen Sie die neu erstellte Inventurerfassung aus.  
  
     Sie können nun die Inventurliste basierend auf den Daten der aktuellen Inventurerfassung drucken.  
  
7.  Wählen Sie auf der Registerkarte **Bericht** wählen Sie **Inventurerfassung** aus.  
  
8.  Im Fenster **Phys. Invt. Erfassung** legen Sie die entsprechenden Filter fest, und wählen Sie die Schaltfläche **Drucken** aus oder wählen Sie die Schaltfläche **Vorschau** aus.  
  
     Optional können Sie die Funktion Physische Stabelverarbeitungs-Inventur verwenden, um die Serien- oder Chargennummern zu erfassen.  
  
9. Im Fenster **Physische Inventurerfassung** wählen Sie die Inventurerfassungszeile aus, wählen Sie **Funktionen** und dann **Zeile kopieren**.  
  
10. Im Fenster **Physische Inventurerfassung kopieren** geben Sie die Anzahl der Kopien an, die von der ausgewählten Zeile erstellt werden sollen, und wählen Sie dann die Schaltfläche **OK** aus.  
  
 Sie können die gedruckte physische Inventurerfassung verwenden, um die tatsächliche Menge des am angegebenen Lagerort verfügbaren Artikels zu aktualisieren. Zum Abschließen des Erfassungsprozesses muss das Kontrollkästchen **Erfasst** für alle Inventurerfassungszeilen aktiviert werden.  
  
 Damit ersichtlich ist, dass die Inventurerfassung abgeschlossen wurde, muss der **Status** im Inventurerfassungskopf mithilfe der entsprechenden Funktion auf **Beendet** gesetzt werden. Weitere Informationen finden Sie unter [Vorgehensweise: Führen Sie physische Inventuren aus](how-to-finish-a-physical-inventory-recording.md).  
  
### <a name="to-complete-a-physical-inventory-recording"></a>So schließen Sie eine Inventurerfassung ab  
  
1.  Wählen Sie in der rechten oberen Ecke das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben die **Physische Inventur durchführen** ein. Wählen Sie dann den zugehörigen Link aus.  
  
2.  Wählen Sie den Inventurauftrag aus, für den Sie eine Inventurerfassung erstellen möchten, klicken Sie auf **Startseite** und anschließend auf **Bearbeiten**.  
  
3.  Geben Sie im Fenster **Inventurerfassung** im Inforegister **Zeilen** im Feld **Menge** für jede Zeile die tatsächliche Artikelmenge ein.  
  
4.  Aktivieren Sie für jede Zeile das Kontrollkästchen **Erfasst**.  
  
5.  Füllen Sie im Inforegister **Allgemein** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  
  
    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Erfasst von**|Die Person, von der der Lagerbestand erfasst wurde.|  
    |**Erfassungsdatum**|Das Datum, an dem die Inventur erfasst wurde.|  
    |**Erfassungszeit**|Die Zeit, zu der die Inventur erfasst wurde.|  
  
 Sie können die Inventur jetzt beenden. Weitere Informationen finden Sie unter [Vorgehensweise: Führen Sie physische Inventuren aus](how-to-finish-a-physical-inventory-recording.md).  
  
## <a name="see-also"></a>Siehe auch  
 [Inventurerfassung – Inventurzählung](physical-inventory-recording-counting-physical-inventory.md)   
 [Gewusst wie: Eingeben von Inventuraufträgen](how-to-enter-physical-inventory-orders.md)   
 [Gewusst wie: Berechnen der verfügbaren Menge für einen Inventurauftrag](how-to-calculate-quantity-on-hand-for-a-physical-inventory-order.md)   
 [Gewusst wie: So schließen Sie eine Inventurerfassung ab](how-to-finish-a-physical-inventory-recording.md)   
 Neue Inventurerfassung erst.   
 Inventurerfassung
