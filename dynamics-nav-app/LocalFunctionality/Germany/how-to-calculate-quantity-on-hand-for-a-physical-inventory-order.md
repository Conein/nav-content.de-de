---
title: "Vorgehensweise beim Berechnen der verfügbaren Menge für einen Inventurauftrag"
description: "Nachdem Sie den Inventurauftrag erstellt und die Inventurauftragszeilen eingegeben haben, müssen Sie vom Programm das Feld „Erwartete Menge (Basis)” für die einzelnen Inventurauftragszeilen berechnen lassen."
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
ms.openlocfilehash: de859c5ec4bfd7bb73c85222f2bfcbf4a7292800
ms.contentlocale: de-de
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-calculate-quantity-on-hand-for-a-physical-inventory-order"></a><span data-ttu-id="3334f-103">Gewusst wie: Berechnen der verfügbaren Menge für einen Inventurauftrag</span><span class="sxs-lookup"><span data-stu-id="3334f-103">How to: Calculate Quantity On Hand for a Physical Inventory Order</span></span>
<span data-ttu-id="3334f-104">Nachdem Sie den Inventurauftrag erstellt und die Inventurauftragszeilen eingegeben haben, müssen Sie vom Programm das Feld „Erwartete Menge (Basis)” für die einzelnen Inventurauftragszeilen berechnen lassen.</span><span class="sxs-lookup"><span data-stu-id="3334f-104">After you have created the physical inventory order and after you have entered the physical inventory order lines, you must have the program calculate the field Qty. Expected (Base) for every physical inventory order line.</span></span>  

<span data-ttu-id="3334f-105">Wenn die Erstellung dieser Inventurauftragszeilen von [!INCLUDE[navnow](../../includes/navnow_md.md)] automatisch durchgeführt wurde, konnten Sie auf der Anforderungsseite für die Stapelverarbeitung festlegen, ob die erwartete Menge berechnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="3334f-105">If [!INCLUDE[navnow](../../includes/navnow_md.md)] created this physical inventory order lines automatically, you could decide in the request page for the batch job whether to calculate the expected quantity or not.</span></span> <span data-ttu-id="3334f-106">Wenn Sie die Inventurauftragszeilen manuell erstellt oder zwischenzeitlich geändert haben, müssen Sie die erwarteten Mengen manuell berechnen.</span><span class="sxs-lookup"><span data-stu-id="3334f-106">If you have created the physical inventory order lines manually or if you changed them in the meantime, you have to calculate the expected quantities manually.</span></span> <span data-ttu-id="3334f-107">Sie können Mengen auf zwei Arten berechnen, wie im folgenden Abschnitt erläutert.</span><span class="sxs-lookup"><span data-stu-id="3334f-107">You can calculate quantities in two ways as described in the following section.</span></span>  

## <a name="to-calculate-the-expected-quantity-on-the-physical-inventory-order"></a><span data-ttu-id="3334f-108">So wird die erwartete Menge im Inventurauftrag berechnet</span><span class="sxs-lookup"><span data-stu-id="3334f-108">To calculate the expected quantity on the physical inventory order</span></span>  

1.  <span data-ttu-id="3334f-109">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol „Nach Seite oder Bericht suchen”"), geben Sie **Bestandsauftrag** ein, und wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="3334f-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Phys. Inventory Order**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="3334f-110">Öffnen Sie den Inventurauftrag, für den Sie die erwartete Menge berechnen möchten.</span><span class="sxs-lookup"><span data-stu-id="3334f-110">Open the physical inventory order that you want to calculate the expected quantity for.</span></span>  
3.  <span data-ttu-id="3334f-111">Um die erwartete Menge nur einer Inventurauftragszeile zu berechnen, wählen Sie auf der Registerkarte Aktionen in der Gruppe Funktionen die Option **Erwartete Menge berechnen**, und wählen Sie dann **Diese Zeile** aus.</span><span class="sxs-lookup"><span data-stu-id="3334f-111">To calculate the expected quantity of only one physical inventory order line, choose the **Calculate Qty. Expected** action, and then choose the **This Line** action.</span></span>  
4.  <span data-ttu-id="3334f-112">Um die erwartete Menge aller Inventurauftragszeilen zu berechnen, wählen Sie auf der Registerkarte Aktionen in der Gruppe Funktionen die Option **Erwartete Menge berechnen**, und wählen Sie dann **Alle Zeile** aus.</span><span class="sxs-lookup"><span data-stu-id="3334f-112">To calculate the expected quantity in all physical inventory order lines, choose the **Calculate Qty. Expected** action, and then choose the **All Lines** action.</span></span>  

    <span data-ttu-id="3334f-113">Im Dialog, der angezeigt wird, wählen Sie aus, dass die Mengen für alle Zeilen oder für die Zeilen berechnet werden, die noch nicht berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="3334f-113">In the dialog that appears, choose to calculate the quantities for all lines or for those lines that have not yet been calculated.</span></span>  

<span data-ttu-id="3334f-114">Wenn [!INCLUDE[navnow](../../includes/navnow_md.md)] die erwartete Menge bereits berechnet hat, ist das Kontrollkästchen für **Berechnete erw. Menge** der Inventurauftragszeile aktiviert.</span><span class="sxs-lookup"><span data-stu-id="3334f-114">If [!INCLUDE[navnow](../../includes/navnow_md.md)] has already calculated the expected quantity, it shows this by placing a check mark in the **Qty. Exp. Calculated** field in the inventory order line.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="3334f-115">Das Verfahren zur Durchführung der Inventur und zu deren Erfassung in der Inventurerfassung ist von der Berechnung der erwarteten Mengen unabhängig.</span><span class="sxs-lookup"><span data-stu-id="3334f-115">The process of taking the inventory and recording it in the physical inventory recording is independent from the calculation of the expected quantities.</span></span>  

<span data-ttu-id="3334f-116">Sie müssen die erwarteten Mengen für alle Inventurauftragszeilen eines Inventurauftrags berechnen, bevor Sie das Feld „Status” auf **Beendet** setzen.</span><span class="sxs-lookup"><span data-stu-id="3334f-116">You must calculate the expected quantities for all physical inventory order lines of a physical inventory order before you can set the Status field to **Finished**.</span></span> <span data-ttu-id="3334f-117">Der Grund hierfür ist, dass [!INCLUDE[navnow](../../includes/navnow_md.md)] die erwarteten und die erfassten Mengen vergleicht und die Differenzen zu Buchungszwecken berechnet.</span><span class="sxs-lookup"><span data-stu-id="3334f-117">This is because [!INCLUDE[navnow](../../includes/navnow_md.md)] compares the expected and the recorded quantities and calculates the differences for posting.</span></span>  

## <a name="see-also"></a><span data-ttu-id="3334f-118">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="3334f-118">See Also</span></span>  
 <span data-ttu-id="3334f-119">[Gewusst wie: Eingeben von Inventuraufträgen](how-to-enter-physical-inventory-orders.md) </span><span class="sxs-lookup"><span data-stu-id="3334f-119">[How to: Enter Physical Inventory Orders](how-to-enter-physical-inventory-orders.md) </span></span>  
 <span data-ttu-id="3334f-120">[Inventurerfassung – Inventurzählung](physical-inventory-recording-counting-physical-inventory.md) </span><span class="sxs-lookup"><span data-stu-id="3334f-120">[Physical Inventory Recording - Counting Physical Inventory](physical-inventory-recording-counting-physical-inventory.md) </span></span>  
 <span data-ttu-id="3334f-121">[Gewusst wie: Einen Inventurauftrag abschließen](how-to-finish-a-physical-inventory-order.md) </span><span class="sxs-lookup"><span data-stu-id="3334f-121">[How to: Finish a Physical Inventory Order](how-to-finish-a-physical-inventory-order.md) </span></span>  
 <span data-ttu-id="3334f-122">[Gewusst wie: So schließen Sie eine Inventurerfassung ab](how-to-finish-a-physical-inventory-recording.md) </span><span class="sxs-lookup"><span data-stu-id="3334f-122">[How to: Finish a Physical Inventory Recording](how-to-finish-a-physical-inventory-recording.md) </span></span>  
 [<span data-ttu-id="3334f-123">Inventurauftragszeilen mit Artikelverfolgungszeilen</span><span class="sxs-lookup"><span data-stu-id="3334f-123">Physical Inventory Order Lines With Item Tracking Lines</span></span>](physical-inventory-order-lines-with-item-tracking-lines.md)  
 [<span data-ttu-id="3334f-124">Vorgehensweise. Erfassen, Regulieren und Umbuchen von Lagerbestand</span><span class="sxs-lookup"><span data-stu-id="3334f-124">How to: Count, Adjust, and Reclassify Inventory</span></span>](../../inventory-how-count-adjust-reclassify.md)

