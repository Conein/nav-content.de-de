---
title: "Inventurerfassung – Inventurzählung"
description: "Nach dem Erstellen eines Inventurauftrags und nach der Eingabe der Inventurauftragszeilen kann die eigentliche Inventur durchgeführt werden. In diesem Zusammenhang können die Inventurerfassungsbelege verwendet werden."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 742bebfa7a2fabab87e643b57251db592945eda6
ms.contentlocale: de-de
ms.lasthandoff: 10/26/2017

---
# <a name="physical-inventory-recording---counting-physical-inventory"></a>Inventurerfassung – Inventurzählung
Nach dem Erstellen eines Inventurauftrags und nach der Eingabe der Inventurauftragszeilen kann die eigentliche Inventur durchgeführt werden. In diesem Zusammenhang können die Inventurerfassungsbelege verwendet werden.  

Eine Inventurerfassung bezieht sich immer nur auf einen Inventurauftrag. Ein Inventurauftrag kann hingegen mit mehr als einer Inventurerfassung verknüpft sein.  

Jede Inventurerfassung setzt sich aus einem Inventurerfassungskopf und einer Reihe von Inventurerfassungszeilen zusammen. Der Inventurerfassungskopf enthält die Informationen, die für alle Inventurerfassungszeilen gültig sind.  

Die Zeilen enthalten die Artikel, die Lagerorte, die Lagerplätze und die erfassten Mengen.  

Diese können manuell oder von der Anwendung automatisch erstellt werden. Es können Inventurerfassungslisten gedruckt werden.  

Durch Festlegen des Status auf "Beendet" teilen Sie der Anwendung mit, dass die aktuelle Inventurerfassung abgeschlossen ist.  

> [!NOTE]  
>  Beim Abschluss der aktuellen Inventurerfassung weist die Anwendung jeder Inventurerfassungszeile eine Zeile des zugehörigen Inventurauftrags zu. Die Anwendung weist jeweils Inventurauftragszeilen mit den gleichen Werten in den 4 Feldern  Artikelnr.,  Variantencode,  Lagerortcode und  Lagerplatzcode wie in der Inventurerfassungszeile zu.  
>   
>  Wenn keine entsprechende Inventurauftragszeile vorhanden ist, fügt die Anwendung beim Abschluss der Inventurerfassung automatisch eine neue Zeile hinzu. Die Anwendung kennzeichnet diese Zeile durch Aktivierung des Kontrollkästchens Ohne Auftrag erfasst in der jeweiligen Inventurauftragszeile.  
>   
>  Ist mehr als eine entsprechende Inventurauftragszeile vorhanden, wird eine Fehlermeldung angezeigt. In diesem Fall können Sie die Anwendung anweisen, die doppelten Zeilen anzuzeigen.  

## <a name="see-also"></a>Siehe auch  
 [So erstellen Sie eine physische Inventurerfassung](how-to-create-a-physical-inventory-recording.md)   
 [Gewusst wie: So schließen Sie eine Inventurerfassung ab](how-to-finish-a-physical-inventory-recording.md)   
 [So zeigen Sie doppelte Inventurauftragszeilen an](how-to-view-duplicate-physical-inventory-order-lines.md)   
 [Inventurauftragszeilen mit Artikelverfolgungszeilen](physical-inventory-order-lines-with-item-tracking-lines.md)

