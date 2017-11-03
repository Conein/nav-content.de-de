---
title: "Elektronische Übermittlung der Umsatzsteuervoranmeldungen an ELSTER"
description: "In [!INCLUDE[navnow](../../includes/navnow_md.md)] können Sie Steuerbelege und MwSt.-Abrechnungen, wie die Umsatzsteuervoranmeldung, an das Finanzamt elektronisch übermitteln."
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
ms.openlocfilehash: 22ed995198fbe9887e236e0c3dba8fd9dea14a95
ms.contentlocale: de-de
ms.lasthandoff: 10/23/2017

---
# <a name="electronic-submission-of-sales-vat-advance-notifications-to-elster"></a>Elektronische Übermittlung der Umsatzsteuervoranmeldungen an ELSTER
In [!INCLUDE[navnow](../../includes/navnow_md.md)] können Sie Steuerbelege und MwSt.-Abrechnungen, wie die Umsatzsteuervoranmeldung, an das Finanzamt elektronisch übermitteln.  

## <a name="sales-vat-advance-notifications"></a>Umsatzsteuervoranmeldungen  
[!INCLUDE[navnow](../../includes/navnow_md.md)] erstellt ein XML-Dokument, das die Steuerbeträge und Bemessungsgrundlagen zusammen mit den Firmeninformationen enthält. Sie können die Daten überprüfen, bevor Sie sie an das Finanzamt übermitteln. Sie können das XML-Dokument mithilfe des Layouts einrichten, das in der Formatvorlage der Finanzämter definiert ist. Sie können dann das XML-Dokument an die Schnittstelle des Onlineportals „Elektronische Steuererklärungen (ELSTER)” der Finanzämter übermitteln.  

Sie müssen zunächst [!INCLUDE[navnow](../../includes/navnow_md.md)] einrichten, damit Sie Mehrwertsteuervoranmeldungen an das ELSTER-Onlineportal senden können. Weitere Informationen finden Sie unter [Gewusst wie: Einrichten von Umsatzsteuervoranmeldungen für ELSTER](how-to-set-up-sales-vat-advance-notifications-for-elster.md). Sie können nun Mehrwertsteuervoranmeldungen erstellen und sie an das Finanzamt übertragen. Weitere Informationen finden Sie unter [Gewusst wie: Einrichten von Mehrwersteuervoranmeldungen für ELSTER](how-to-create-and-submit-sales-vat-advance-notifications.md).

Der Server der Finanzämter verarbeitet das übermittelte XML-Dokument und sendet als Antwort ein XML-Dokument. Dieses Antwortdokument zeigt Codes und Beschreibungen für Fehler an, die während der Verarbeitung des übermittelten XML-Dokuments aufgetreten sind. Die XML-Dokumente sind während der Übermittlung verschlüsselt. Weitere Informationen finden Sie unter [ELSTER-Onlineportal](http://go.microsoft.com/fwlink/?LinkId=155998).  

## <a name="architectural-overview"></a>Architekturübersicht  
[!INCLUDE[navnow](../../includes/navnow_md.md)] umfasst eine Schnittstelle zum ELSTER-Portal, die Microsoft.Dynamics.ElsterTransferHandler.dll-Assembly. Die Montage verwaltet die Kommunikation mit dem ELSTER-Portal und wird installiert, wenn Sie den Windows-Client [!INCLUDE[navnow](../../includes/navnow_md.md)] einrichten. Weitere Informationen finden Sie unter [ELSTER-Übertragung-Onlineportal](elster-transmission-overview.md).

Das ELSTER-Portal hat Anforderungen an Computer, die Belege übermitteln. Dies umfasst ein Softwarezertifikat, das Sie für jeden Benutzer erwerben müssen, der Dokumente an ELSTER übermittelt. Sie müssen Ihre Installation anhand von Informationen überprüfen, die im [ELSTER-Onlineportal](http://go.microsoft.com/fwlink/?LinkId=155998) verfügbar sind. Im nächsten Abschnitt werden Installationsüberlegungen für Ihre [!INCLUDE[navnow](../../includes/navnow_md.md)]-Implementierung beschrieben.  

### <a name="installation-considerations"></a>Installationsüberlegungen  
Die Microsoft.Dynamics.ElsterTransferHandler.dll-Assembly wird als Teil der Installation des [!INCLUDE[navnow](../../includes/navnow_md.md)] installiert.  

> [!NOTE]  
>  Zuvor installieren Sie eine neue Version von [!INCLUDE[navnow](../../includes/navnow_md.md)].  

ELSTER benötigt Zertifikate, um das Unternehmen und die Person zu identifizieren, die das jeweilige Dokument übermittelt. Auf dem Computer jedes Benutzers, der eine Erklärung an ELSTER sendet, müssen Sie die folgenden Zertifikate installieren:  

- Das öffentliche Zertifikat der Finanzämter.  
- Ein persönliches PFX-Zertifikat für diesen Benutzer.  

Sie müssen dann die Benutzer und die Anzeigenamen der Zertifikate im Fenster **Zertifikate** aufführen. Weitere Informationen darüber, wie ein Zertifikat installiert wird und wie Sie den Anzeigenamen suchen, finden Sie in der Hilfe zum Betriebssystem.  

Wenn Sie einen Proxyserver verwenden, um die ELSTER-Dokumente zu senden, müssen Sie die Einstellungen im Fenster **Elektronische Umsatzsteuererklärung – Einrichtung** angeben.  

Weitere Informationen finden Sie unter [Gewusst wie: Einrichten von Umsatzsteuervoranmeldungen für ELSTER](how-to-set-up-sales-vat-advance-notifications-for-elster.md).  

## <a name="certificates-and-style-sheets"></a>Zertifikate und Formatvorlagen  
Ihr Unternehmen muss sich im ELSTER-Onlineportal registrieren, sodass Sie die erforderlichen Zertifikate erhalten können. Wenn Sie sich bereits registriert haben, müssen Sie sich nicht erneut registrieren.  

> [!IMPORTANT]  
> Das ELSTER-Onlineportal bietet drei Methoden der Verbindung, aber [!INCLUDE[navnow](../../includes/navnow_md.md)] unterstützt nur das Software-Zertifikat, das in der ELSTER-Basiszertifizierungsmethode enthalten ist. Das ELSTER-Spezial und die ELSTER Methoden sind nicht im [!INCLUDE[navnow](../../includes/navnow_md.md)] verfügbar.  

Nachdem Sie sich im ELSTER-Onlineportal registriert haben, müssen Sie ein persönliches Zertifikat erwerben. Sie müssen auch das öffentliche Zertifikat der Finanzämter und die Formatvorlagen herunterladen, die für die Datenübermittlungen benötigt werden. Wenn Sie das persönliche Zertifikat auf dem Computer des Benutzers installieren, werden Sie aufgefordert, ein Kennwort anzugeben.  

Das öffentliche Zertifikat der Finanzämter steht zum Download vom ELSTER-Onlineportal zur Verfügung. Der aktuelle Dateiname ist Coala2019.pem.cer.  

Das persönliche PFX-Zertifikat wird benötigt, um den Benutzer deutlich zu identifizieren, der die Belege an das Finanzamt übermittelt. Das persönliche Zertifikat enthält eine digitale Signatur, die in den übermittelten XML-Dateien enthalten ist. Der Name des Benutzers, der die Dateien übermittelt hat, ist auch enthalten.  

Sie müssen alle relevanten Formatvorlagen herunterladen, die die Finanzämter zur Verfügung stellen. Dazu gehört die Formatvorlage ustva.xsl, die Sie im Fenster **MwSt.-Voranmeldungskarte** angeben müssen, aber die Finanzämter benötigen möglicherweise zusätzliche Formatvorlagen, die sich im selben Ordner, wie die Formatvorlage ustva.xsl befinden müssen.  

Weitere Informationen finden Sie unter [ELSTER-Onlineportal](http://go.microsoft.com/fwlink/?LinkId=155998)  

## <a name="transmissions"></a>Übermittlungen  
Im Fenster **MwSt-Voranmeldungsübersicht**” können Sie Mehrwertsteuerrvoranmeldungen erstellen und senden. Wenn Sie ein Dokument erstellen, können Sie dieses in der Vorschau anzeigen, bevor Sie es an das ELSTER-Portal senden. Die Dokumente, die erstellt werden, basieren auf den XML-Formatvorlagen, die im ELSTER-Portal veröffentlicht werden, und auf dem Zertifikat und anderen Informationen, die Sie in [!INCLUDE[navnow](../../includes/navnow_md.md)] eingerichtet haben .  

Nachdem Sie ein Dokument an ELSTER gesendet haben, wird ein Eintrag im Fenster **MwSt.-Übertragungsprotokollposten** vorgenommen. Wenn das ELSTER-Onlineportal das übertragene Dokument verarbeitet hat, können Fehler auftreten und  [!INCLUDE[navnow](../../includes/navnow_md.md)] zeigt eine Fehlermeldung an, die auf dem Fehlercode aus ELSTER basiert. In den meisten Fällen wird der Fehler durch Probleme mit dem benutzerspezifischen Zertifikat oder der Netzwerkkonnektivität verursacht. Weitere Informationen finden Sie unter [Fehlermeldungen des ElsterTransferHandler und ELSTER-Übertragungsüberblick](error-messages-of-the-elstertransferhandler.md).

## <a name="see-also"></a>Siehe auch  
 [Gewusst wie: Einrichten von Umsatzsteuervoranmeldungen für ELSTER](how-to-set-up-sales-vat-advance-notifications-for-elster.md)   
 [Gewusst wie: Erstellen und Senden von Umsatzsteuervoranmeldungen](how-to-create-and-submit-sales-vat-advance-notifications.md)   
 [ELSTER-Onlineportal](http://go.microsoft.com/fwlink/?LinkId=155998)

