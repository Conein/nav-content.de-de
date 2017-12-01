---
title: 'Gewusst wie: Einrichten von Lieferbenachrichtigungsbedingungen, -stufen und -text'
description: "Um Lieferbenachrichtigungen zu erstellen, müssen Sie bestimmte Einrichtungen festlegen."
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
ms.openlocfilehash: 4fb405fa349976473b6c83e276a2ce255d47c7da
ms.contentlocale: de-de
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-set-up-delivery-reminder-terms-levels-and-text"></a>Gewusst wie: Einrichten von Lieferbenachrichtigungsbedingungen, -stufen und -text
Um Lieferbenachrichtigung zu erstellen, müssen Sie Folgendes einrichten:  

- Lieferbenachrichtigungsbestimmungen  
- Lieferbenachrichtigungsstufen  
- Lieferbenachrichtigungstextnachrichten  

Jede Lieferbenachrichtigungsmethode verfügt über eigene Lieferbenachrichtigungsstufen, und Sie können für jede der Lieferbenachrichtigungsstufe spezielle Lieferbenachrichtigungstexte definieren.  

Weitere Informationen finden Sie unter [Lieferbenachrichtigungen](delivery-reminders.md).  

## <a name="to-set-up-delivery-reminder-terms"></a>Einrichten von Lieferbenachrichtigungsmethoden  

1.  Wählen Sie in der rechten oberen Ecke ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol nach Seite oder Bericht suchen") und geben **Lieferbenachrichtigungsmethoden** ein. Wählen Sie dann den zugehörigen Link aus.  
2.  Wählen Sie die Aktion **Neu** aus.  
3.  Füllen Sie die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  

    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Code**|Der Code für das Fälligkeitsdatum der Lieferbenachrichtigung. Sie können maximal 10 alphanumerische Zeichen eingeben.|  
    |**Beschreibung**|Die Beschreibung für die Lieferbenachrichtigungsmethode. Sie können maximal 30 alphanumerische Zeichen eingeben.|  
    |**Max. Anzahl Lieferbenachrichtigungen**|Gibt die maximale Anzahl von Lieferbenachrichtigungen an, die für eine Bestellung erstellt werden kann.<br /><br /> **HINWEIS:** Dies ist die maximale Anzahl über alle Mahnstufen hinweg für diese Anmahnungsmethode. Wenn Sie beispielsweise drei Stufen eingerichtet haben, und Sie **Max. Anzahl Lieferbenachrichtigungen** auf 5 festlegen, wird die erste Mahnung mit Stufe 1, die zweite mit Stufe 2 und die letzten drei mit Stufe 3 erstellt.|  

4.  Wählen Sie die Schaltfläche **OK** aus.  

## <a name="to-add-delivery-reminder-levels-to-a-delivery-reminder-term"></a>So richten Sie Lieferanmahnungsstufen für Lieferanmahnungsmethoden ein  

1.  Klicken Sie im Fenster **Lieferbenachrichtigungsbestimmungen** in die Zeile mit der Methode, für die Sie Stufen anlegen möchten, und wählen Sie dann die Aktion **Stufen**.  
2.  Wählen Sie die Aktion **Neu** aus.  
3.  Füllen Sie die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  

    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Nr.**|Lieferbenachrichtigungsstufenzahl. Dieses Feld wird automatisch ausgefüllt.|  
    |**Berechnung Fälligkeitsdatum**|Die Formel für die Berechnung des Fälligkeitsdatums für die Lieferbenachrichtigung Sie können eine Kombination von Nummern zwischen 0 und 9999 sowie Datumscodes eingeben (D für Tag, TW für Wochentag, W für Woche, M für Monat, Q für Quartal oder J für Jahr). Die Formel für die Berechnung des Datencodes für das Fälligkeitsdatum für die Lieferbenachrichtigung. Die Datumsberechnungsformel für das Fälligkeitsdatum kann maximal 20 Zeichen enthalten.|  

4.  Wählen Sie die Schaltfläche **OK** aus.  

Für jede Lieferbenachrichtigungsstufe kann eine Textnachricht definiert werden, der in die Lieferbenachrichtigung aufgenommen wird. Sie können Vortext definieren, der vor der Beschreibung der überfälligen Bestellung hinzugefügt wird, und Nachtext, der nach der Beschreibung der überfälligen Bestellung hinzugefügt wird.  

Nachfolgend wird beschrieben, wie Vortextnachrichten eingerichtet werde. Aber dieselben Schritte gelten auch für das Einrichten von Nachtextnachrichten.  

## <a name="to-set-up-delivery-reminder-text-messages"></a>Lieferbenachrichtigungstextnachrichten einrichten  

1.  Im Fenster **Lieferbenachrichtigungsstufen** wählen Sie eine Ebene, und wählen die Aktion **Vortext** aus.  
2.  Wählen Sie die Aktion **Neu** aus.  
3.  Geben Sie im Feld **Beschreibung** die Vortextnachricht für die Lieferbenachrichtigung ein.  
4.  Wählen Sie die Schaltfläche **OK** aus.  

## <a name="see-also"></a>Siehe auch  
 [Lieferbenachrichtigungen](delivery-reminders.md)   
 [Gewusst wie: Einrichten von Lieferbenachrichtigungen](how-to-set-up-delivery-reminders.md)   
 [Gewusst wie: Zuweisen von Lieferbenachrichtigungscodes zu Kreditoren](how-to-assign-delivery-reminder-codes-to-vendors.md)   
 [Gewusst wie: Lieferbenachrichtigungen manuell erstellen](how-to-create-delivery-reminders-manually.md)   
 [Gewusst wie: Lieferbenachrichtigungen ausstellen](how-to-issue-delivery-reminders.md)

