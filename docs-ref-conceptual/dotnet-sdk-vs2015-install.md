---
title: "Azure-Tools für Visual Studio 2015"
description: "Informationen zum Abrufen der Tools für das Verwenden der Azure .NET-Bibliotheken in Visual Studio 2015."
keywords: Azure .NET, SDK, VS2015, Visual Studio 2015
author: camsoper
manager: douge
ms.author: casoper
ms.date: 07/25/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.openlocfilehash: bee09801efd4f7291981bc85cd9c6a5d0b795b6e
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-tools-for-visual-studio-2015"></a>Azure-Tools für Visual Studio 2015

Die schnellste und einfachste Methode zum Installieren der Elemente **Azure SDK für Visual Studio 2015** und **Service Fabric SDK und Tools für Visual Studio 2015** ist der [Webplattform-Installer](https://www.microsoft.com/web/downloads/platform.aspx).  Der Microsoft-Webplattform-Installer ist ein kostenloses Tool zum Optimieren des Herunterladens, Installierens und Aktualisierens einiger Komponenten der Microsoft-Webplattform, einschließlich Azure-Tools für Visual Studio 2015.  Diese SDKs können auch über die [Azure-Downloadseite](https://azure.microsoft.com/downloads/) als einzelne Komponenten heruntergeladen und installiert werden. 

## <a name="using-the-web-platform-installer"></a>Verwenden des Webplattform-Installers

1. Laden Sie diesen [Webplattform-Installer-Bootstrapper](https://www.microsoft.com/web/handlers/webpi.ashx?command=getinstallerredirect&appid=VWDOrVs2015AzurePack;MicrosoftAzure-ServiceFabric-VS2015) herunter, und führen Sie ihn aus.  

2. Der Bootstrapper installiert den Webplattform-Installer (bei Bedarf) und legt die neuesten Versionen der Elemente **Azure SDK für Visual Studio 2015** und **Service Fabric SDK und Tools für Visual Studio 2015** automatisch in Ihrer Liste *Zu installierende Elemente* ab.  Klicken Sie auf **Installieren**.

    ![Webplattform-Installer](media/dotnet-sdk-vs2015-install/webpi.png)

3. Klicken Sie auf dem nächsten Bildschirm auf **Ich stimme zu**.  Der Webplattform-Installer beginnt mit dem Herunterladen und Installieren der ausgewählten Komponenten.

4. Nachdem die Installation abgeschlossen ist, wird ein Bestätigungsfenster angezeigt.  Klicken Sie auf **Fertig stellen**.  Sie können den Webplattform-Installer jetzt schließen.

## <a name="verifying-the-installation"></a>Überprüfen der Installation

1. Klicken Sie in Visual Studio 2015 im Menü **Extras** auf **Erweiterungen und Updates...**.

2. Die angezeigte Liste enthält mehrere Azure-Tools, z.B. **Microsoft Azure App Service-Tools**, **Microsoft Azure Storage - verbundener Dienst** und **Service Fabric-Tools**.

    ![Erweiterungen und Updates](media\dotnet-sdk-vs2015-install\ext-tools.png)

## <a name="next-steps"></a>Nächste Schritte

[Erste Schritte mit den Azure-Bibliotheken für .NET](dotnet-sdk-azure-get-started.md)