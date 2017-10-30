---
title: 'Vorgehensweise: Einrichten von MwSt.-Berichten'
description: "Informationen aus verschiedenen Rechnungstypen werden verwendet, um Daten in den Ausfuhr-Listenbericht EU zu speisen. Um einen MwSt-Bericht unter dem System ELMA5 von [!INCLUDE[navnow](../../includes/navnow_md.md)] einzurichten, müssen Sie die Parameter melden."
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
ms.openlocfilehash: 9476231caebd23ccaa4e46d23d9831db2a26cff4
ms.contentlocale: de-de
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-vat-reports"></a><span data-ttu-id="d2190-104">Vorgehensweise: Einrichten von MwSt.-Berichten</span><span class="sxs-lookup"><span data-stu-id="d2190-104">How to: Set Up VAT Reports</span></span>
<span data-ttu-id="d2190-105">Informationen aus verschiedenen Rechnungstypen werden verwendet, um Daten in den Ausfuhr-Listenbericht EU zu speisen.</span><span class="sxs-lookup"><span data-stu-id="d2190-105">Information from various invoice types is used to feed data into the EU Sales List report.</span></span> <span data-ttu-id="d2190-106">Um einen MwSt-Bericht unter dem System ELMA5 von [!INCLUDE[navnow](../../includes/navnow_md.md)] einzurichten, müssen Sie die Parameter melden.</span><span class="sxs-lookup"><span data-stu-id="d2190-106">To file a VAT report under the ELMA5 system from [!INCLUDE[navnow](../../includes/navnow_md.md)], you need to set up report parameters.</span></span>  
  
### <a name="to-set-up-a-vat-report"></a><span data-ttu-id="d2190-107">So richten Sie einen MwSt-Bericht ein</span><span class="sxs-lookup"><span data-stu-id="d2190-107">To set up a VAT report</span></span>  
  
1.  <span data-ttu-id="d2190-108">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben die **MwSt.-Berichtseinrichtung** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="d2190-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Report Setup**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="d2190-109">Wählen Sie im Inforegister **Allgemein** das Feld **Übermittelte Berichte bearbeiten** aus, damit Benutzer MwSt.-Erklärungen, die an die Steuerbehörden übermittelt wurden, ändern können.</span><span class="sxs-lookup"><span data-stu-id="d2190-109">On the **General** FastTab, select the **Modify Submitted Reports** check box to let users modify VAT reports that have been submitted to the tax authorities.</span></span>  
  
     <span data-ttu-id="d2190-110">Wenn Sie das Feld leer lassen, müssen Benutzer stattdessen eine Korrektur-MwSt.-Erklärung erstellen.</span><span class="sxs-lookup"><span data-stu-id="d2190-110">If the field is left blank, users must create a corrective VAT report instead.</span></span>  
  
3.  <span data-ttu-id="d2190-111">Wählen Sie das Kontrollkästchen **Stornozeilen exportieren**, wenn Sie Informationen über Stornierungszeilen berücksichtigen wollen, wenn Sie Daten für den MwSt von EU-Verkäufen exportieren.</span><span class="sxs-lookup"><span data-stu-id="d2190-111">Select the **Export Cancellation Lines** check box if you want to include information about cancellation lines when you export data for the VAT report of EU sales.</span></span> <span data-ttu-id="d2190-112">Weitere Informationen finden Sie unter [Gewusst wie: MwSt-Berichte korrigieren](how-to-correct-vat-reports.md).</span><span class="sxs-lookup"><span data-stu-id="d2190-112">For more information, see [How to: Correct VAT Reports](how-to-correct-vat-reports.md).</span></span>  
  
4.  <span data-ttu-id="d2190-113">Geben Sie im Inforegister **Nummerierung** die Nummernserie an, die für Standard-MwSt.-Erklärungen verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d2190-113">On the **Numbering** FastTab, specify the number series that will be used for standard VAT reports.</span></span> <span data-ttu-id="d2190-114">Dieses ist standardmäßig die Seriennummer, die in beliebigen MwSt Berichten verwendet wird, die Sie erstellen.</span><span class="sxs-lookup"><span data-stu-id="d2190-114">This will be the default numbering series that is used on any VAT Report that you then create.</span></span>  
  
     <span data-ttu-id="d2190-115">Abhängig von den Anforderungen können Sie die gleichen Nummernserien für alle MwSt.-Erklärungen oder separate Nummernserien für jede Art von MwSt.-Erklärung verwenden.</span><span class="sxs-lookup"><span data-stu-id="d2190-115">Depending on the requirements, you can use the same number series for all VAT reports, or separate number series for each type of VAT report.</span></span> <span data-ttu-id="d2190-116">Weitere Informationen finden Sie unter Nr.</span><span class="sxs-lookup"><span data-stu-id="d2190-116">For more information, see No.</span></span> <span data-ttu-id="d2190-117">Serien.</span><span class="sxs-lookup"><span data-stu-id="d2190-117">Series.</span></span>  
  
     <span data-ttu-id="d2190-118">Wenn beispielsweise Ihre Unternehmen separate Nummernserien für Standard- und für Korrektur-MwSt.-Erklärungen verwendet, ist diese Nummernserie die Standardnummernserie.</span><span class="sxs-lookup"><span data-stu-id="d2190-118">For example, if your company uses separate number series for standard and corrective VAT reports, this number series is the default number series.</span></span> <span data-ttu-id="d2190-119">Benutzer können eine andere Nummernserie in **Nr.** auswählen</span><span class="sxs-lookup"><span data-stu-id="d2190-119">Users can select a different number series in the **No.**</span></span> <span data-ttu-id="d2190-120">Feld, wenn sie Korrekturberichte erstellen.</span><span class="sxs-lookup"><span data-stu-id="d2190-120">field when they create corrective reports.</span></span>  
  
5.  <span data-ttu-id="d2190-121">Im Inforegister **ZIVIT** können Sie Informationen für die Felder anzeigen.</span><span class="sxs-lookup"><span data-stu-id="d2190-121">On the **ZIVIT** FastTab, specify information for the fields.</span></span>  
  
6.  <span data-ttu-id="d2190-122">Wählen Sie die Schaltfläche **OK** aus.</span><span class="sxs-lookup"><span data-stu-id="d2190-122">Choose the **OK** button.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="d2190-123">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="d2190-123">See Also</span></span>  
 <span data-ttu-id="d2190-124">[MwSt.-Abrechnung](vat-reporting.md) </span><span class="sxs-lookup"><span data-stu-id="d2190-124">[VAT Reporting](vat-reporting.md) </span></span>  
 [<span data-ttu-id="d2190-125">Gewusst wie: MwSt.-Berichte erstellen</span><span class="sxs-lookup"><span data-stu-id="d2190-125">How to: Create VAT Reports</span></span>](how-to-create-vat-reports.md)
