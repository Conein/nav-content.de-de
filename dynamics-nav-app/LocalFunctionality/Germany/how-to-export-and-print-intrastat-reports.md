---
title: 'Gewusst wie: Exportieren und Drucken von Intrastat-Berichten'
description: "Intrastat-Berichterstattung ist in der gesamten Europäischen Union (EU) erforderlich und muss landesbezogenen Anforderungen entsprechen (beispielsweise bestimmten Formaten und Dateien). Alle Unternehmen innerhalb der EU sind verpflichtet, Auskunft über ihre Handelsaktivitäten mit anderen EU-Ländern zu geben."
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
ms.openlocfilehash: ad47b26eb49fe07c08ba838ba4c6a0e111c2ff3b
ms.contentlocale: de-de
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-export-and-print-intrastat-reports"></a><span data-ttu-id="4ddd2-104">Gewusst wie: Exportieren und Drucken von Intrastat-Berichten</span><span class="sxs-lookup"><span data-stu-id="4ddd2-104">How to: Export and Print Intrastat Reports</span></span>
<span data-ttu-id="4ddd2-105">Intrastat-Berichterstattung ist in der gesamten Europäischen Union (EU) erforderlich und muss landesbezogenen Anforderungen entsprechen (beispielsweise bestimmten Formaten und Dateien).</span><span class="sxs-lookup"><span data-stu-id="4ddd2-105">Intrastat reporting is required throughout the European Union (EU) and must follow local requirements, such as specific formats and files.</span></span> <span data-ttu-id="4ddd2-106">Alle Unternehmen innerhalb der EU sind verpflichtet, Auskunft über ihre Handelsaktivitäten mit anderen EU-Ländern zu geben.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-106">All companies in the EU must report their trade with other EU countries.</span></span> <span data-ttu-id="4ddd2-107">Warenbewegungen müssen jeden Monat dem Statistischen Amt Ihres Landes/Ihrer Region mitgeteilt und die Berichte müssen an die Steuerbehörden übermittelt werden.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-107">The movement of goods must be reported to the statistics authorities (Statistisches Bundesamt) every month, and a report must be delivered to the tax authorities.</span></span>  

 <span data-ttu-id="4ddd2-108">Für Intrastat-Berichte müssen Sie Papierberichte und Dateien zur Verfügung stellen, die für Deutschland im ASCII-Format sein müssen.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-108">For Intrastat reporting, you must provide paper reports and files, which must be in ASCII format for Germany.</span></span> [!INCLUDE[navnow](../../includes/navnow_md.md)]<span data-ttu-id="4ddd2-109"> schließt Berichte und Batchaufträgen ein, die alle Informationen generieren, die an die deutschen Steuerbehörden gesendet werden müssen.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-109"> includes reports and batch jobs that generate all of the information that must be sent to the German tax authorities.</span></span> <span data-ttu-id="4ddd2-110">Diese Informationen umfasst automatisch alle gelieferten als auch alle erhaltenen Waren.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-110">This information automatically includes both receipt and delivery of goods.</span></span> <span data-ttu-id="4ddd2-111">Die Intrastat-Datei enthält die Daten, die in den Zeilen des **Intrastat**-Buchungsblatts eingetragen wurden.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-111">The Intrastat file contains information from the lines in the **Intrastat** journal.</span></span>  

## <a name="to-print-the-german-intrastat-checklist"></a><span data-ttu-id="4ddd2-112">So drucken Sie die Intrastat-Checkliste für Deutschland</span><span class="sxs-lookup"><span data-stu-id="4ddd2-112">To print the German Intrastat checklist</span></span>  

1.  <span data-ttu-id="4ddd2-113">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Intrastat Buch.-Blätter** ein und wählen dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-113">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intrastat Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="4ddd2-114">Wählen Sie im Feld **Buch.-Blattname** den erforderlichen Buch.-Blattnamen aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-114">In the **Batch Name** field, select the required journal batch name.</span></span>
3.  <span data-ttu-id="4ddd2-115">Wählen Sie die **Bericht-Checkliste** Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-115">Choose the **Checklist Report** action.</span></span>  
4.  <span data-ttu-id="4ddd2-116">Aktivieren Sie im Fenster **Intrastat - Checklist DE** im Inforegister **Optionen** das Kontrollkästchen **Intrastat-Buch.-Blattzeilen anzeigen**.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-116">In the **Intrastat - Checklist DE** window, on the **Options** FastTab, select the **Show Intrastat Journal Lines** check box.</span></span>  

    > [!IMPORTANT]  
    >  <span data-ttu-id="4ddd2-117">Wenn Sie das Kontrollkästchen **Intrastat-Buch.-Blattzeilen anzeigen** deaktivieren, werden im Bericht nur die Informationen angezeigt, die an die Steuerbehörden gemeldet werden müssen, nicht jedoch die Zeilen im Buch.-Blatt.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-117">If you clear the **Show Intrastat Journal Lines** check box, the report displays only the information that must be reported to the tax authorities, and not the lines in the journal.</span></span>  

5.  <span data-ttu-id="4ddd2-118">Optional wählen Sie im Inforegister **Intrastat Buch.-Blattname** die entsprechenden Filter aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-118">Optionally, on the **Intrastat Jnl. Batch** FastTab, select the appropriate filters.</span></span>  
6.  <span data-ttu-id="4ddd2-119">Optional wählen Sie im Inforegister **Intrastat Buch.-Blattname** die entsprechenden Filter aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-119">Optionally, on the **Intrastat Jnl. Line** FastTab, select the appropriate filters.</span></span>  
7.  <span data-ttu-id="4ddd2-120">Wählen Sie die Schaltfläche **Drucken** aus, um die Intrastat-Checkliste zu drucken, oder die Schaltfläche **Vorschau**, um den Bericht auf dem Bildschirm anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-120">Choose the **Print** button to print the Intrastat checklist or choose the **Preview** button to view it on the screen.</span></span>  

## <a name="to-print-the-german-intrastat-form"></a><span data-ttu-id="4ddd2-121">So drucken Sie das Intrastat-Formular für Deutschland</span><span class="sxs-lookup"><span data-stu-id="4ddd2-121">To print the German Intrastat form</span></span>  

1.  <span data-ttu-id="4ddd2-122">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Intrastat Buch.-Blätter** ein und wählen dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-122">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intrastat Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="4ddd2-123">Wählen Sie im Feld **Buch.-Blattname** den erforderlichen Buch.-Blattnamen aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-123">In the **Batch Name** field, select the required journal batch name.</span></span>  
3.  <span data-ttu-id="4ddd2-124">Wählen Sie die Aktion **Formular** aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-124">Choose the **Form** action.</span></span>  
4.  <span data-ttu-id="4ddd2-125">Optional wählen Sie im Inforegister **Intrastat Buch.-Blattname** die entsprechenden Filter aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-125">Optionally, on the **Intrastat Jnl. Batch** FastTab, select the appropriate filters.</span></span>  
5.  <span data-ttu-id="4ddd2-126">Optional wählen Sie im Inforegister **Intrastat Buch.-Blattname** die entsprechenden Filter aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-126">Optionally, on the **Intrastat Jnl. Line** FastTab, select the appropriate filters.</span></span>  
6.  <span data-ttu-id="4ddd2-127">Wählen Sie die Schaltfläche **Drucken** aus, um die Intrastat-Checkliste zu drucken, oder die Schaltfläche **Vorschau**, um den Bericht auf dem Bildschirm anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-127">Choose the **Print** button to print the Intrastat checklist or choose the **Preview** button to view it on the screen.</span></span>  

## <a name="to-export-intrastat-information-to-a-disk"></a><span data-ttu-id="4ddd2-128">So exportieren Sie Intrastat-Informationen auf einen Datenträger</span><span class="sxs-lookup"><span data-stu-id="4ddd2-128">To export Intrastat information to a disk</span></span>  

1.  <span data-ttu-id="4ddd2-129">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Intrastat Buch.-Blätter** ein und wählen dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-129">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intrastat Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="4ddd2-130">Wählen Sie im Feld **Buch.-Blattname** den erforderlichen Buch.-Blattnamen aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-130">In the **Batch Name** field, select the required journal batch name.</span></span>  
3.  <span data-ttu-id="4ddd2-131">Wählen Sie die **Diskette erstellen** Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-131">Choose the **Make Diskette** action.</span></span>  
4.  <span data-ttu-id="4ddd2-132">Geben Sie im Inforegister **Optionen** im Feld **Pfad** den vollständigen Pfad und Namen der Datei ein, in die Sie die Informationen schreiben möchten.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-132">On the **Options** FastTab, in the **Path** field, enter the full path and the name of the file to which you want to write the information.</span></span>  

    <span data-ttu-id="4ddd2-133">Optional wählen Sie im Inforegister **Intrastat Buch.-Blattname** die entsprechenden Filter aus.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-133">Optionally, on the **Intrastat Jnl. Batch** FastTab, select the appropriate filters.</span></span>  

5.  <span data-ttu-id="4ddd2-134">Um die Datei zu exportieren, wählen Sie die Schaltfläche **OK**, um den Export zu starten.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-134">To export the file, choose the **OK** button.</span></span>  

<span data-ttu-id="4ddd2-135">Die Intrastat-Informationen werden exportiert, und Sie können entweder die Daten in einer Datei speichern oder die Datei in einem geeigneten Programm öffnen.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-135">The Intrastat information is exported, and you can either save the data to a file, or you can open the file in the appropriate program.</span></span>  

 <span data-ttu-id="4ddd2-136">Beim Exportieren der Datei wird das Kontrollkästchen **Ausgewertet** im Fenster **Intrastat Jnl. Buch.-Blattnamen** ausgewählt und **Interne Referenznr.**</span><span class="sxs-lookup"><span data-stu-id="4ddd2-136">When the file is exported, the **Reported** check box in the **Intrastat Jnl. Batches** window will be selected, and the **Internal Ref. No.**</span></span> <span data-ttu-id="4ddd2-137">Feld für jeden Posten im Buch.-Blatt ausgefüllt.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-137">field on every entry in the journal will be filled in.</span></span> <span data-ttu-id="4ddd2-138">Sie können manuellen Änderungen in diesem Feld vornehmen.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-138">You can manually change the contents of the field.</span></span> <span data-ttu-id="4ddd2-139">Sie können den Inhalt dieses Feldes auch ändern, wenn beispielsweise eine wiederholte Berichterstattung erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-139">For example, you can make changes when you need to run the report again.</span></span> <span data-ttu-id="4ddd2-140">Weitere Informationen finden Sie unter  Intrastat Stapelverarbeitung.</span><span class="sxs-lookup"><span data-stu-id="4ddd2-140">For more information, see Intrastat Jnl. Batch.</span></span>  

## <a name="see-also"></a><span data-ttu-id="4ddd2-141">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="4ddd2-141">See Also</span></span>  
 [<span data-ttu-id="4ddd2-142">MwSt.-Abrechnung</span><span class="sxs-lookup"><span data-stu-id="4ddd2-142">VAT Reporting</span></span>](vat-reporting.md)  
 [<span data-ttu-id="4ddd2-143">So gehts: Melden von MwSt. an die Steuerbehörden</span><span class="sxs-lookup"><span data-stu-id="4ddd2-143">How to: Report VAT to Tax Authorities</span></span>](../../finance-how-report-vat.md)

