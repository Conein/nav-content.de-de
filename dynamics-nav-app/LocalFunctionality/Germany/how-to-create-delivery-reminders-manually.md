---
title: 'Gewusst wie: Lieferbenachrichtigungen manuell erstellen'
description: "Mahnt Ihre Debitoren wegen überfälliger Lieferung."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: b31b4ffa843d39058ed97a560f6d8041b4eb510b
ms.contentlocale: de-de
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-create-delivery-reminders-manually"></a>Gewusst wie: Lieferbenachrichtigungen manuell erstellen
In [!INCLUDE[navnow](../../includes/navnow_md.md)], können Sie Lieferbenachrichtigungen erstellen, wenn eine Bestellung nicht wie erwartet geliefert wurde. Sie können eine einzelne Lieferbenachrichtigung manuell erstellen oder Sie können Lieferbenachrichtigungen für alle überfälligen Lieferungen erstellen. Weitere Informationen finden Sie unter [Vorgehensweise: Erstellen von Lieferbenachrichtigungen](how-to-generate-delivery-reminders.md).

> [!NOTE]
> Um Lieferanmahnungen zu erstellen, müssen Sie die Lieferanmahnungseigenschaften einrichten. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Lieferbenachrichtigungen](how-to-set-up-delivery-reminders.md).

## <a name="to-create-a-delivery-reminder-manually"></a>So erstellen Sie Lieferantenbenachrichtigungen manuell  

1.  Wählen Sie in der rechten oberen Ecke ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol nach Seite oder Bericht suchen") und geben **Lieferbenachrichtigungen** ein. Wählen Sie dann den zugehörigen Link aus.  
2.  Wählen Sie die Aktion **Neu** aus.  
3.  Füllen Sie im Fenster **Lieferbenachrichtigung** im Inforegister **Allgemein** die erforderlichen Felder gemäß der Beschreibung in der folgenden Tabelle aus.  

    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Nr.**|Die eindeutige Kennnummer für die Lieferbenachrichtigung.|  
    |**Kreditorennr**|Gibt die Nummer des Kreditors an, für den Sie eine Lieferbenachrichtigung buchen möchten.<br /><br /> Wenn Sie die Kreditorennummer auswählen, werden **Name**, **Adresse**, **PLZ Code/Ort** und **Kontakt** Felder automatisch ausgefüllt.|  
    |**Buchungsdatum**|Gibt das Buchungsdatum der Lieferbenachrichtigung an. Dieses Datum wird in alle Lieferbenachrichtigung kopiert.|  
    |**Belegdatum**|Gibt das Dokumentdatum der Lieferbenachrichtigung an. Dieses Datum wird auch verwendet, um das Fälligkeitsdatum der Lieferbenachrichtigung zu bestimmen. Sie können das Buchungsdatum bei Bedarf ändern.|  
    |**Mahnstufe**|Lieferbenachrichtigungsstufe. Dieser Wert basiert auf der Anzahl von Lieferbenachrichtigung, die bereits gesendet wurden. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Lieferbenachrichtigungen](how-to-set-up-delivery-reminder-terms-levels-and-text.md).|  
    |**Mahnmethodencode**|Gibt den Lieferbenachrichtigungscode für den Kreditor an.|  
    |**Fälligkeitsdatum**|Gibt das Fälligkeitsdatum der Lieferbenachrichtigung an.|  

4.  Wählen Sie die Aktion **Mahnungszeile vorschlagen**.  

    Wenn es überfällige Lieferungen vom angegebenen Kreditor gibt, werden diese der Lieferbenachrichtigung hinzugefügt.  

5.  Wählen Sie die Schaltfläche **OK** aus.  

    Lieferbenachrichtigung wurde erstellt. So können die Lieferbenachrichtigungen ausgeben und erstellen.  

## <a name="see-also"></a>Siehe auch  
 [Lieferbenachrichtigungen](delivery-reminders.md)   
 [Gewusst wie: Einrichten von Lieferbenachrichtigungen](how-to-generate-delivery-reminders.md)   
 [Gewusst wie: Einrichten von Lieferbenachrichtigungen](how-to-set-up-delivery-reminders.md)   
 [Gewusst wie: Einrichten von Lieferbenachrichtigungsbedingungen, -stufen und -text](how-to-set-up-delivery-reminder-terms-levels-and-text.md)   
 [Gewusst wie: Zuweisen von Lieferbenachrichtigungscodes zu Kreditoren](how-to-assign-delivery-reminder-codes-to-vendors.md)   
 [Gewusst wie: Lieferbenachrichtigungen ausstellen](how-to-issue-delivery-reminders.md)   
 [So drucken Sie Testberichte vor dem Registrieren von Lieferanmahnungen](how-to-print-test-reports-for-delivery-reminders.md)

