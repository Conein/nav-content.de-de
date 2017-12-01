---
title: "Gewusst wie: Einen Inventurauftrag abschließen"
description: "Nach Abschluss des Inventurauftrags können Sie die Inventurdifferenzen analysieren."
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
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 21d4b4312e0440fa951c7c6dc1192d52d6019f40
ms.contentlocale: de-de
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-finish-a-physical-inventory-order"></a><span data-ttu-id="c1ee4-103">Gewusst wie: Einen Inventurauftrag abschließen</span><span class="sxs-lookup"><span data-stu-id="c1ee4-103">How to: Finish a Physical Inventory Order</span></span>
<span data-ttu-id="c1ee4-104">Nach Abschluss des Inventurauftrags können Sie die Inventurdifferenzen analysieren.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-104">After you have entered all data for the physical inventory order, you can finish the physical inventory order.</span></span>  

<span data-ttu-id="c1ee4-105">Ein Inventurauftrag kann nur abgeschlossen werden, wenn Folgendes zutrifft:</span><span class="sxs-lookup"><span data-stu-id="c1ee4-105">It is only possible to finish the physical inventory order if the following is true:</span></span>  

- <span data-ttu-id="c1ee4-106">Alle zugehörigen Inventurerfassungen müssen den **Status** "Beendet" aufweisen.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-106">For all related physical inventory recordings, the Status field is set to **Finished**.</span></span>  
- <span data-ttu-id="c1ee4-107">In allen Inventurauftragszeilen wurde die erwartete Menge berechnet.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-107">In all physical inventory order lines, the quantity expected has been calculated.</span></span>  

    [!INCLUDE[navnow](../../includes/navnow_md.md)]<span data-ttu-id="c1ee4-108"> zeigt dies durch Aktivierung des Kontrollkästchens **Erwartete Menge berechnen** der  jeweilige Inventurauftragszeile an.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-108"> shows this by setting a check mark in the field **Qty. Exp. Calculated** of the physical inventory order line.</span></span>  

- <span data-ttu-id="c1ee4-109">Jede Inventurauftragszeile wurde mit mindestens einer Inventurerfassungszeile gezählt.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-109">Every physical inventory order line has been counted by at least one inventory recording line.</span></span>  

    <span data-ttu-id="c1ee4-110">Dies wird angegeben, indem Sie im Feld Aufzeichnungs-Zeilen das Gebiet der Inventurauftragszeile auswählen.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-110">This is indicated by selecting the In Recording Lines field of the physical inventory order line.</span></span> <span data-ttu-id="c1ee4-111">Für eine Inventurauftragszeile können Sie eine Liste der Inventurerfassungszeilen anzeigen.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-111">For a physical inventory order line, you can view a list of the physical inventory recording lines.</span></span>  

## <a name="to-finish-a-physical-inventory-order"></a><span data-ttu-id="c1ee4-112">So schließen Sie einen Inventurauftrag ab</span><span class="sxs-lookup"><span data-stu-id="c1ee4-112">To finish a physical inventory order</span></span>  

1.  <span data-ttu-id="c1ee4-113">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol „Nach Seite oder Bericht suchen”"), geben Sie **Bestandsauftrag** ein, und wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-113">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Phys. Inventory Order**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="c1ee4-114">Öffnen Sie den Inventurauftrag, den Sie abschließen möchten, und wählen Sie die **Fertig stellen** Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-114">Open the physical inventory order that you want to finish, and then choose the **Finish** action.</span></span>  

    <span data-ttu-id="c1ee4-115">Die Anwendung setzt den Status im Inventurauftragskopf auf **Beendet**.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-115">The status of the physical inventory header is set to **Finished**.</span></span> <span data-ttu-id="c1ee4-116">Sie können den Inventurauftragskopf oder die Inventurauftragszeilen nun nicht mehr ändern.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-116">You can no longer change the physical inventory order header or the physical inventory order lines.</span></span>  

<span data-ttu-id="c1ee4-117">Beim Abschluss des Inventurauftrags vergleicht die Anwendung die erwartete Menge und die erfassten Mengen des Inventurauftragskopfes und berechnet die Abweichungen.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-117">When finishing the physical inventory order, the expected quantity and the recorded quantities of the physical inventory header are compared and the differences calculated.</span></span>  

<span data-ttu-id="c1ee4-118">Sie müssen den Status im Inventurauftragskopf erst auf "Beendet" setzen, bevor Sie Differenzen auswerten und den Inventurauftrag buchen können.</span><span class="sxs-lookup"><span data-stu-id="c1ee4-118">You have to finish the physical inventory order header first before you can evaluate differences and before you can post the physical inventory order.</span></span>  

## <a name="see-also"></a><span data-ttu-id="c1ee4-119">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="c1ee4-119">See Also</span></span>  
 <span data-ttu-id="c1ee4-120">[Gewusst wie: Eingeben von Inventuraufträgen](how-to-enter-physical-inventory-orders.md) </span><span class="sxs-lookup"><span data-stu-id="c1ee4-120">[How to: Enter Physical Inventory Orders](how-to-enter-physical-inventory-orders.md) </span></span>  
 <span data-ttu-id="c1ee4-121">[Gewusst wie: Buchen von Inventuraufträgen](how-to-post-physical-inventory-orders.md) </span><span class="sxs-lookup"><span data-stu-id="c1ee4-121">[How to: Post Physical Inventory Orders](how-to-post-physical-inventory-orders.md) </span></span>  
 <span data-ttu-id="c1ee4-122">[Gewusst wie: Berechnen der verfügbaren Menge für einen Inventurauftrag](how-to-calculate-quantity-on-hand-for-a-physical-inventory-order.md) </span><span class="sxs-lookup"><span data-stu-id="c1ee4-122">[How to: Calculate Quantity On Hand for a Physical Inventory Order](how-to-calculate-quantity-on-hand-for-a-physical-inventory-order.md) </span></span>  
 <span data-ttu-id="c1ee4-123">[Gewusst wie: So schließen Sie eine Inventurerfassung ab](how-to-finish-a-physical-inventory-recording.md) </span><span class="sxs-lookup"><span data-stu-id="c1ee4-123">[How to: Finish a Physical Inventory Recording](how-to-finish-a-physical-inventory-recording.md) </span></span>  
 <span data-ttu-id="c1ee4-124">[Gewusst wie: Analysieren von Inventurdifferenzen](how-to-analyze-physical-inventory-differences.md) </span><span class="sxs-lookup"><span data-stu-id="c1ee4-124">[How to: Analyze Physical Inventory Differences](how-to-analyze-physical-inventory-differences.md) </span></span>  
 [<span data-ttu-id="c1ee4-125">Inventurauftragszeilen mit Artikelverfolgungszeilen</span><span class="sxs-lookup"><span data-stu-id="c1ee4-125">Physical Inventory Order Lines With Item Tracking Lines</span></span>](physical-inventory-order-lines-with-item-tracking-lines.md)

