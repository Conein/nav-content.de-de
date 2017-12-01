---
title: "Gewusst wie: Buchen von Inventuraufträgen"
description: "Nach Fertigstellen eines Inventurauftrags und Ändern des Status in **Beendet** kann er gebucht werden."
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
ms.openlocfilehash: 4482c17d8a6a504d4f212e64be5ba5066680a1db
ms.contentlocale: de-de
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-post-physical-inventory-orders"></a><span data-ttu-id="e3d1b-103">Gewusst wie: Buchen von Inventuraufträgen</span><span class="sxs-lookup"><span data-stu-id="e3d1b-103">How to: Post Physical Inventory Orders</span></span>
<span data-ttu-id="e3d1b-104">Nach Fertigstellen eines Inventurauftrags und Ändern des Status in **Beendet** kann er gebucht werden.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-104">After completing a physical inventory order and changing its status to **Finished**, you can post it.</span></span>  

<span data-ttu-id="e3d1b-105">Der Status eines Inventurauftrags kann unter folgenden Voraussetzungen auf **Beendet** festgelegt werden:</span><span class="sxs-lookup"><span data-stu-id="e3d1b-105">You can set the status of a physical inventory order to **Finished** if the following is true:</span></span>  

- <span data-ttu-id="e3d1b-106">Alle zugehörigen Inventurerfassungen weisen den Status **Beendet** auf.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-106">All related physical inventory recordings have a status of **Finished**.</span></span>  
- <span data-ttu-id="e3d1b-107">Jede Inventurauftragszeile wurde in mindestens einer Inventurerfassungszeile erfasst.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-107">Each physical inventory order line has been counted by at least one inventory recording line.</span></span>  
- <span data-ttu-id="e3d1b-108">Die Kontrollkästchen **In Erfassungszeilen enthalten** und **Berechnete erw. Menge** wurden für alle Inventurauftragszeilen aktiviert.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-108">The **In Recording Lines** and the **Qty. Exp. Calculated** check boxes have been selected for all of the physical inventory order lines.</span></span>  

<span data-ttu-id="e3d1b-109">Nach dem Buchen des Auftrags können die gebuchten Inventuraufträge angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-109">After posting the order, you can view the posted physical inventory orders.</span></span> <span data-ttu-id="e3d1b-110">Gebuchte Lagerbelege bieten einen vollständigen Überblick über den Inventurprozess.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-110">Posted inventory documents provide a complete overview of the physical inventory process.</span></span>  

## <a name="to-post-a-physical-inventory-order"></a><span data-ttu-id="e3d1b-111">So buchen Sie einen Inventurauftrag</span><span class="sxs-lookup"><span data-stu-id="e3d1b-111">To post a physical inventory order</span></span>  

1.  <span data-ttu-id="e3d1b-112">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol „Nach Seite oder Bericht suchen”"), geben Sie **Bestandsauftrag** ein, und wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-112">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Phys. Inventory Order**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="e3d1b-113">Wählen Sie den Inventurauftrag aus, den Sie fertig stellen möchten, klicken Sie auf **Bearbeiten**.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-113">Select the physical inventory order that you want to complete, and then choose the **Edit** action.</span></span>  

    <span data-ttu-id="e3d1b-114">Im Fenster **Inventurauftrag** kann die Menge angezeigt werden, die nach Ausführung der Inventur im Feld **Erfasste Menge (Basis)** erfasst wurde.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-114">In the **Phys. Inventory Order** window, you can view the quantity recorded after taking physical inventory in the **Qty. Recorded (Base)** field.</span></span>  

3.  <span data-ttu-id="e3d1b-115">Wählen Sie die Schaltfläche **Fertigstellung** aus.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-115">Choose the **Finish** action.</span></span>  
4.  <span data-ttu-id="e3d1b-116">Wählen Sie die Schaltfläche **Ja** aus.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-116">Choose the **Yes** button.</span></span> <span data-ttu-id="e3d1b-117">Der Wert im Feld **Status** wird in **Beendet** geändert.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-117">The value in the **Status** field is changed to **Finished**.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="e3d1b-118">Eine Änderung des Inventurauftragskopfs oder der Inventurauftragszeilen ist nicht möglich.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-118">You cannot change the physical inventory order header or the physical inventory order lines.</span></span>  

5.  <span data-ttu-id="e3d1b-119">Wählen Sie die zu buchenden Zeilen aus, und wählen Sie dann die Aktion **Buchen** und dann **ok** aus.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-119">To post the order, choose **Post**, and then choose the **OK** button.</span></span>  

## <a name="to-view-posted-physical-inventory-orders"></a><span data-ttu-id="e3d1b-120">So zeigen Sie gebuchte Inventuraufträge an</span><span class="sxs-lookup"><span data-stu-id="e3d1b-120">To view posted physical inventory orders</span></span>  

1.  <span data-ttu-id="e3d1b-121">Wählen Sie in der rechten oberen Ecke das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben die **Physische Inventur durchführen** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-121">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Phys. Invt. Order**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="e3d1b-122">Wählen Sie im Fenster **Gebuchter Inventurauftrag** den gebuchten Inventurauftrag aus, den Sie anzeigen möchten, klicken Sie auf Aktionen und anschließend auf **Ansicht**.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-122">In the **Posted Phys. Invt. Order** window, select the posted inventory order that you want to view, and then choose the **View** action.</span></span>  
3.  <span data-ttu-id="e3d1b-123">Um einer Liste zugehörige Inventurerfassungen anzuzeigen, wählen Sie die Aktion **Erfassungen** aus.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-123">To view a list of related physical inventory recordings, choose the **Recordings** action.</span></span>  

    <span data-ttu-id="e3d1b-124">Sie können auch einen Bericht ausführen, in dem die Differenz zwischen der erwarteten Menge und der erfassten Menge zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-124">You can also run a report that returns the difference between the expected quantity and the physical (recorded) quantity.</span></span>  

4.  <span data-ttu-id="e3d1b-125">Schließen Sie das Fenster.</span><span class="sxs-lookup"><span data-stu-id="e3d1b-125">Close the window.</span></span>  

## <a name="see-also"></a><span data-ttu-id="e3d1b-126">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="e3d1b-126">See Also</span></span>  
 <span data-ttu-id="e3d1b-127">[Inventurbelege](physical-inventory-documents.md) </span><span class="sxs-lookup"><span data-stu-id="e3d1b-127">[Physical Inventory Documents](physical-inventory-documents.md) </span></span>  
 [<span data-ttu-id="e3d1b-128">Gewusst wie: Eingeben von Inventuraufträgen</span><span class="sxs-lookup"><span data-stu-id="e3d1b-128">How to: Enter Physical Inventory Orders</span></span>](how-to-enter-physical-inventory-orders.md)

