---
title: "Gewusst wie: Einrichten von Umsatzsteuervoranmeldungen für ELSTER"
description: "In [!INCLUDE[navnow](../../includes/navnow_md.md)] können Sie die Umsatzsteuervoranmeldungsdatei-Benachrichtigung elektronisch an das ELSTER-Portal übermitteln."
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: d717ccec6da7830a6ff315d595cb50869ab31c34
ms.contentlocale: de-de
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-set-up-sales-vat-advance-notifications-for-elster"></a><span data-ttu-id="4f538-103">Gewusst wie: Einrichten von Umsatzsteuervoranmeldungen für ELSTER</span><span class="sxs-lookup"><span data-stu-id="4f538-103">How to: Set Up Sales VAT Advance Notifications for ELSTER</span></span>
<span data-ttu-id="4f538-104">In [!INCLUDE[navnow](../../includes/navnow_md.md)] müssen Sie zuerst Folgendes einrichten, damit Sie gültige Mehrwertsteuervoranmeldungen an das ELSTER-Portal übermitteln können.</span><span class="sxs-lookup"><span data-stu-id="4f538-104">In [!INCLUDE[navnow](../../includes/navnow_md.md)], to submit valid sales VAT advance notifications to the ELSTER portal, you must set up the following:</span></span>  

- <span data-ttu-id="4f538-105">Die Firmendaten und die Steuerinformationen.</span><span class="sxs-lookup"><span data-stu-id="4f538-105">The company registration information and tax office information.</span></span>  
- <span data-ttu-id="4f538-106">Die Nummern gibt die Mehrwertsteuer-Voranmeldungsnummer an.</span><span class="sxs-lookup"><span data-stu-id="4f538-106">The number series for sales VAT advance notification.</span></span>  
- <span data-ttu-id="4f538-107">Die Benutzerauthentifizierung für die Steuerbehörden.</span><span class="sxs-lookup"><span data-stu-id="4f538-107">The user authentication for the tax authorities.</span></span>  
- <span data-ttu-id="4f538-108">MwSt.-Abrechnung</span><span class="sxs-lookup"><span data-stu-id="4f538-108">The VAT statement.</span></span>  

<span data-ttu-id="4f538-109">Sie müssen Komponenten auch vom ELSTER-Portal herunterladen.</span><span class="sxs-lookup"><span data-stu-id="4f538-109">You must also download components from the ELSTER portal.</span></span> <span data-ttu-id="4f538-110">Weitere Informationen finden Sie unter [ELSTER-Onlineportal](http://go.microsoft.com/fwlink/?LinkId=155998).</span><span class="sxs-lookup"><span data-stu-id="4f538-110">For more information, see the [ELSTER online portal](http://go.microsoft.com/fwlink/?LinkId=155998).</span></span>  

## <a name="to-set-up-company-information"></a><span data-ttu-id="4f538-111">Um Unternehmensinformationen einzurichten:</span><span class="sxs-lookup"><span data-stu-id="4f538-111">To set up company information</span></span>  

1.  <span data-ttu-id="4f538-112">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol "Nach Seite oder Bericht suchen"") aus, geben Sie **Unternehmensdaten** ein, und wählen Sie dann den verknüpften Link aus.</span><span class="sxs-lookup"><span data-stu-id="4f538-112">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Company Information**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="4f538-113">Im Fenster **Firmendaten** im Inforegister **Allgemein**, im Feld **MwSt-Vertreter**, geben Sie die Kontaktperson für MwSt-bezogene Informationen ein.</span><span class="sxs-lookup"><span data-stu-id="4f538-113">In the **Company Information** window, on the **General** FastTab, in the **VAT Representative** field, enter the contact person for VAT related information.</span></span>  
3.  <span data-ttu-id="4f538-114">Füllen Sie im Inforegister **Steuerdienst** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.</span><span class="sxs-lookup"><span data-stu-id="4f538-114">On the **Tax Office** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="4f538-115">Feld</span><span class="sxs-lookup"><span data-stu-id="4f538-115">Field</span></span>|<span data-ttu-id="4f538-116">Description</span><span class="sxs-lookup"><span data-stu-id="4f538-116">Description</span></span>|  
    |------------------------------------|---------------------------------------|  
    |<span data-ttu-id="4f538-117">**Proxyserver verwenden**</span><span class="sxs-lookup"><span data-stu-id="4f538-117">**Use Proxy Server**</span></span>|<span data-ttu-id="4f538-118">Wählen Sie diese Option aus, um einen Proxyserver für die Kommunikation zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="4f538-118">Select to use a proxy server for communication.</span></span>|  
    |<span data-ttu-id="4f538-119">**Proxyserverauth. erforderlich**</span><span class="sxs-lookup"><span data-stu-id="4f538-119">**Proxy Server Authent. Required**</span></span>|<span data-ttu-id="4f538-120">Wählen Sie diese Option aus, um einen Proxyserver für die Authentifizierung zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="4f538-120">Select to use a dedicated proxy server for authentication.</span></span><br /><br /> <span data-ttu-id="4f538-121">Wenn Sie einen Proxyserverr und eine dedizierte Authentifizierung verwenden, müssen Sie das Benutzerkonto und das Kennwort vor der Übertragung eingeben.</span><span class="sxs-lookup"><span data-stu-id="4f538-121">If you use a proxy server and the required dedicated authentication, then you must enter the user account and the password before transmitting.</span></span> <span data-ttu-id="4f538-122">Wenn Sie die Windows-Authentifizierung verwenden, wählen Sie dieses Feld nicht aus.</span><span class="sxs-lookup"><span data-stu-id="4f538-122">If you use Windows authentication, do not select this field.</span></span>|  
    |<span data-ttu-id="4f538-123">**Proxyserver-IP-Adresse/-Port**</span><span class="sxs-lookup"><span data-stu-id="4f538-123">**Proxy Server IP-Address/Port**</span></span>|<span data-ttu-id="4f538-124">Die IP-Adresse und den Port, der für die Kommunikation verwendet wird, wenn Sie einen Proxyserver verwenden.</span><span class="sxs-lookup"><span data-stu-id="4f538-124">The address and the port that will be used for communication if you use a proxy server.</span></span>|  

4.  <span data-ttu-id="4f538-125">Füllen Sie im Inforegister **HTTP-Server** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.</span><span class="sxs-lookup"><span data-stu-id="4f538-125">On the **HTTP Servers** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="4f538-126">Feld</span><span class="sxs-lookup"><span data-stu-id="4f538-126">Field</span></span>|<span data-ttu-id="4f538-127">Description</span><span class="sxs-lookup"><span data-stu-id="4f538-127">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="4f538-128">**HTTP-Server-URL 1**</span><span class="sxs-lookup"><span data-stu-id="4f538-128">**HTTP Server URL 1**</span></span>|<span data-ttu-id="4f538-129">Definiert einen Server der Oberfinanzdirektion (OFD), wie **http://datenannahme1.elster.de/Elster2/EMS**.</span><span class="sxs-lookup"><span data-stu-id="4f538-129">Specifies a server of the Oberfinanzdirektion (OFD), such as **http://datenannahme1.elster.de/Elster2/EMS**.</span></span>|  
    |<span data-ttu-id="4f538-130">**HTTP-Server-URL 2**</span><span class="sxs-lookup"><span data-stu-id="4f538-130">**HTTP Server URL 2**</span></span>|<span data-ttu-id="4f538-131">Definiert einen Server der Oberfinanzdirektion (OFD), wie **http://datenannahme2.elster.de/Elster2/EMS**.</span><span class="sxs-lookup"><span data-stu-id="4f538-131">Specifies a server of the OFD, such as **http://datenannahme2.elster.de/Elster2/EMS**.</span></span>|  
    |<span data-ttu-id="4f538-132">**HTTP-Server-URL 3**</span><span class="sxs-lookup"><span data-stu-id="4f538-132">**HTTP Server URL 3**</span></span>|<span data-ttu-id="4f538-133">Definiert einen Server der Oberfinanzdirektion (OFD), wie **http://datenannahme3.elster.de/Elster2/EMS**.</span><span class="sxs-lookup"><span data-stu-id="4f538-133">Specifies a server of the OFD, such as **http://datenannahme3.elster.de/Elster2/EMS**.</span></span>|  
    |<span data-ttu-id="4f538-134">**HTTP-Server-URL 4**</span><span class="sxs-lookup"><span data-stu-id="4f538-134">**HTTP Server URL 4**</span></span>|<span data-ttu-id="4f538-135">Definiert einen Server der Oberfinanzdirektion (OFD), wie **http://datenannahme4.elster.de/Elster2/EMS**.</span><span class="sxs-lookup"><span data-stu-id="4f538-135">Specifies a server of the OFD, such as **http://datenannahme4.elster.de/Elster2/EMS**.</span></span>|  

    <span data-ttu-id="4f538-136">Jetzt müssen Sie die Benutzer angeben, die Belege an das ELSTER-Portal übermitteln können.</span><span class="sxs-lookup"><span data-stu-id="4f538-136">Now you must specify the users who can submit documents to the ELSTER portal.</span></span>  

5.  <span data-ttu-id="4f538-137">Wählen Sie die **Zertifikate** Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="4f538-137">Choose the **Certificates** action.</span></span>  

    <span data-ttu-id="4f538-138">Weitere Informationen über ELSTER-Zertifikate finden Sie unter [ELSTER-Onlineportal](http://go.microsoft.com/fwlink/?LinkId=155998).</span><span class="sxs-lookup"><span data-stu-id="4f538-138">For more information about ELSTER certificates, see the [ELSTER online portal](http://go.microsoft.com/fwlink/?LinkId=155998).</span></span>  

    1.  <span data-ttu-id="4f538-139">Im Fenster **Zertifikate** im Feld **Benutzer-ID**, geben Sie den Benutzer an, dem Sie die Berechtigung erteilen möchten, Dokumente an ELSTER zu senden.</span><span class="sxs-lookup"><span data-stu-id="4f538-139">In the **Certificates** window, in the **User ID** field, specify the user who you want to authorize to submit documents to ELSTER.</span></span>  
    2.  <span data-ttu-id="4f538-140">Wählen Sie die **Elster-Zertifikat hochladen** Aktion aus, und geben Sie die Zertifikatsdatei, z Coala2019.pem.cer an.</span><span class="sxs-lookup"><span data-stu-id="4f538-140">Choose the **Upload Elster Certificate** action, and then specify the certificate file, such as Coala2019.pem.cer.</span></span>  
    3.  <span data-ttu-id="4f538-141">Wählen Sie **PFX-Datei hochladen** und geben Sie dort die persönlichen Zertifikatsdatei für diesen Benutzer, wie test-soft-pse.pfx an.</span><span class="sxs-lookup"><span data-stu-id="4f538-141">Choose **Upload PFX File**, and then specify the personal certificate file for this user, such as test-soft-pse.pfx.</span></span>  

        > [!IMPORTANT]  
        >  <span data-ttu-id="4f538-142">Wenn Datenverschlüsselung nicht bereits ausgeführt wird, müssen Sie sie aktivieren, bevor Sie fortfahren.</span><span class="sxs-lookup"><span data-stu-id="4f538-142">If data encryption is not already enabled, you must enable it before you proceed.</span></span>

    4.  <span data-ttu-id="4f538-143">Wählen Sie die Option **Kennwort für PFX-Datei festlegen** aus, und geben Sie dann das Kennwort für das persönliche Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="4f538-143">Choose the **Set Pfx File Password** option, and then specify the password for this personal certificate.</span></span>  

6.  <span data-ttu-id="4f538-144">Wiederholen Sie Schritt 5 für andere Benutzer, die Dokumente an ELSTER senden.</span><span class="sxs-lookup"><span data-stu-id="4f538-144">Repeat step 5 for other users who will submit documents to ELSTER.</span></span>  
7.  <span data-ttu-id="4f538-145">Wählen Sie die Schaltfläche **OK** aus.</span><span class="sxs-lookup"><span data-stu-id="4f538-145">Choose the **OK** button.</span></span>  

## <a name="to-set-up-a-vat-statement-for-sales-vat-advance-notifications"></a><span data-ttu-id="4f538-146">Um MwSt-Berichte für Umsatzsteuervoranmeldungs-Benachrichtigungen einzurichten</span><span class="sxs-lookup"><span data-stu-id="4f538-146">To set up a VAT statement for sales VAT advance notifications</span></span>  

1.  <span data-ttu-id="4f538-147">Wählen Sie in der rechten oberen Ecke das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben die **MwSt-Bericht** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="4f538-147">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Statement**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="4f538-148">Wählen Sie im Fenster **MwSt-Bericht** im Feld **Name**, den Drop-Down-Pfeil.</span><span class="sxs-lookup"><span data-stu-id="4f538-148">In the **VAT Statement** window, in the **Name** field, choose the drop-down arrow.</span></span>  
3.  <span data-ttu-id="4f538-149">Im Fenster **MwSt.-Abrechnungsnamen** in der Zeile für den entsprechenden MwSt.-Abrechnungsnamen wählen Sie das Feld **Verkaufs MwSt-Benachrichtigung** aus.</span><span class="sxs-lookup"><span data-stu-id="4f538-149">In the **VAT Statement Names** window, in the line for the appropriate VAT statement name select the **Sales VAT Adv. Notification** field.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="4f538-150">Nur ein MwSt.-Abrechnungsname für eine Umsatzsteuervoranmeldung kann gleichzeitig ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="4f538-150">Only one VAT statement name can be selected for sales VAT advance notification at one time.</span></span> <span data-ttu-id="4f538-151">Die MwSt.-Abrechnung muss eine MwSt.-Abrechnungszeile für jede Kennzahl aufweisen, die vom Finanzamt, in der **Zeilennr.** gefordert wird</span><span class="sxs-lookup"><span data-stu-id="4f538-151">The VAT statement must have a VAT statement line for each key figure required by the tax authority, where the **Row No.**</span></span> <span data-ttu-id="4f538-152">Feld enthält die Kennzahl und das Feld **Betragsart** gibt an, ob es sich um eine Bemessungsgrundlage oder um einen Steuerbetrag handelt.</span><span class="sxs-lookup"><span data-stu-id="4f538-152">field contains the key figure and the **Amount Type** field specifies if this is a base amount or a tax amount.</span></span> <span data-ttu-id="4f538-153">Wenden Sie sich an Ihr Finanzamt, wenn Fragen zu den Schlüsselnummern und ihrer Definition bestehen.</span><span class="sxs-lookup"><span data-stu-id="4f538-153">Ask your tax office if you have questions concerning the key figures and their definition.</span></span>  

4.  <span data-ttu-id="4f538-154">Wählen Sie die Schaltfläche **OK** aus.</span><span class="sxs-lookup"><span data-stu-id="4f538-154">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="4f538-155">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="4f538-155">See Also</span></span>  
 <span data-ttu-id="4f538-156">[Elektronische Übermittlung der Umsatzsteuervoranmeldungen an ELSTER](electronic-submission-of-sales-vat-advance-notifications-to-elster.md) </span><span class="sxs-lookup"><span data-stu-id="4f538-156">[Electronic Submission of Sales VAT Advance Notifications to ELSTER](electronic-submission-of-sales-vat-advance-notifications-to-elster.md) </span></span>  
 [<span data-ttu-id="4f538-157">Gewusst wie: Erstellen und Senden von Umsatzsteuervoranmeldungen</span><span class="sxs-lookup"><span data-stu-id="4f538-157">How to: Create and Submit Sales VAT Advance Notifications</span></span>](how-to-create-and-submit-sales-vat-advance-notifications.md)

