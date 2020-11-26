---
title: Ergebnis Cluster "Connectors"
ms.author: manusi
author: manusi
manager: ruppala
ms.audience: Admin
ms.topic: article
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
description: Details der Connectors result Cluster Experience
ms.openlocfilehash: eac4180a247fe17b4e86b57a69f2b7bdb79e56bb
ms.sourcegitcommit: 59cdd3f0f82b7918399bf44d27d9891076090f4f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 11/20/2020
ms.locfileid: "49367744"
---
# <a name="graph-connectors-result-cluster"></a><span data-ttu-id="e57b2-103">Ergebnis Cluster "Graph Connectors"</span><span class="sxs-lookup"><span data-stu-id="e57b2-103">Graph connectors result cluster</span></span>

## <a name="overview-of-the-graph-connectors-result-cluster-preview"></a><span data-ttu-id="e57b2-104">Übersicht über den Ergebnis Cluster "Graph Connectors" (Vorschau)</span><span class="sxs-lookup"><span data-stu-id="e57b2-104">Overview of the Graph connectors result cluster (Preview)</span></span>  

 <span data-ttu-id="e57b2-105">Mit Graph Connectors result Clusters können Unternehmen in Ihrer Standardansicht (Registerkarte alle) in SharePoint und Office.com nach Inhalten aus Drittanbieter-Datenquellen suchen.</span><span class="sxs-lookup"><span data-stu-id="e57b2-105">With Graph connectors result clusters, enterprises can search for content from third party data sources in their default view (the All tab) in SharePoint and Office.com.</span></span>

<span data-ttu-id="e57b2-106">Ergebnis Cluster helfen Benutzern bei der Ermittlung aller Inhalte von Drittanbietern (previoulsy, die an einen einzelnen Connector und eine vertikale Verbindung gebunden sind) an einer Stelle.</span><span class="sxs-lookup"><span data-stu-id="e57b2-106">Result clusters help users discover all third party content (previoulsy tied to a single connector and vertical) in one place.</span></span> <span data-ttu-id="e57b2-107">Die in einem Ergebnis Cluster angezeigten Ergebnisse werden basierend auf der Konfiguration des Mandanten Administrators in einer Such Sparte zusammengefasst.</span><span class="sxs-lookup"><span data-stu-id="e57b2-107">The results shown in a result cluster are grouped together based on how the tenant administrator configures them in a search vertical.</span></span>  

## <a name="how-connector-results-are-selected-and-displayed"></a><span data-ttu-id="e57b2-108">Auswählen und Anzeigen von Verbindungs Ergebnissen</span><span class="sxs-lookup"><span data-stu-id="e57b2-108">How connector results are selected and displayed</span></span>

<span data-ttu-id="e57b2-109">Die im Ergebnis Cluster bereitgestellten Connector-Ergebnisse werden von einzelnen Such vertikalen mit Connector-Inhalten abgeleitet.</span><span class="sxs-lookup"><span data-stu-id="e57b2-109">Connector results provided in the result cluster are derived from individual search verticals with connector content.</span></span> <span data-ttu-id="e57b2-110">Jede vertikale Suche enthält eine Reihe relevanter Ergebnisse, die zu einem Kandidaten Ergebnis Cluster werden.</span><span class="sxs-lookup"><span data-stu-id="e57b2-110">Each search vertical provides a set of relevant results which becomes a candidate result cluster.</span></span> <span data-ttu-id="e57b2-111">Relevante Ergebnisse werden basierend auf der Eigenschaft "Title", dem Ergebnisausschnitt und der Inhaltskomponente jedes Elements ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="e57b2-111">Relevant results are chosen based on the "title" property, result snippet, and content component of each item.</span></span>

<span data-ttu-id="e57b2-112">Um sicherzustellen, dass Inhalte aus den Such vertikalen gefunden werden, wird empfohlen, aussagekräftige Titel für ihre Elemente bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="e57b2-112">To ensure discovery of content from the search verticals, we recommend providing meaningful titles for your items.</span></span> <span data-ttu-id="e57b2-113">Dies wirkt sich positiv auf das Schiedsverfahren von Ergebnis Cluster Kandidaten und die Wahrscheinlichkeit aus, dass Ihre Inhalte in einem Ergebnis Cluster angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="e57b2-113">This positively impacts the arbitration of result cluster candidates and the likelihood of your content showing up in a result cluster.</span></span> <span data-ttu-id="e57b2-114">Vermeiden Sie beispielsweise die Verwendung von IDs als Werte für die Eigenschaft "Title", es sei denn, Ihre Benutzer verwenden IDs, um nach Inhalten zu suchen.</span><span class="sxs-lookup"><span data-stu-id="e57b2-114">For example, avoid the use of IDs as values for the property "title" unless your users are using IDs to look for content.</span></span>

<span data-ttu-id="e57b2-115">Wie oft ein Ergebnis Cluster angezeigt wird, hängt von Faktoren wie der Anzahl der von Ihnen konfigurierten Such vertikalen Elementen und dem Typ des Inhalts ab.</span><span class="sxs-lookup"><span data-stu-id="e57b2-115">How often a result cluster is shown varies on factors such as the number of search verticals that you configure and the type of content.</span></span> <span data-ttu-id="e57b2-116">Wenn Sie Ergebnis Cluster Ergebnisse entweder auswählen oder ignorieren, werden Sie implizit Hinweise bereitstellen, mit denen das Auslösen von Ergebnis Clustern im Laufe der Zeit angepasst wird.</span><span class="sxs-lookup"><span data-stu-id="e57b2-116">By either selecting or ignoring result cluster results, you will implicitly provide hints that will adjust the triggering of result clusters over time.</span></span>

<span data-ttu-id="e57b2-117">Die Suchergebnis Erfahrung für Connector-Elemente, die in ihrem Ergebnis Cluster angezeigt werden, wird vom System generiert und verwendet keine benutzerdefinierten Ergebnis Layouts.</span><span class="sxs-lookup"><span data-stu-id="e57b2-117">The search result experience for connector items shown in your result cluster is system generated and does not use custom result layouts.</span></span> <span data-ttu-id="e57b2-118">Sie müssen die Eigenschaft "Title" und den Elementinhalt während der Verbindungs Registrierung deklarieren, wenn die Ergebnisse im Ergebnis Cluster angezeigt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e57b2-118">You must declare the "title" property and item content during connection registration if you want results to appear in your result cluster.</span></span>

## <a name="enable-result-clusters"></a><span data-ttu-id="e57b2-119">Ergebnis Cluster aktivieren</span><span class="sxs-lookup"><span data-stu-id="e57b2-119">Enable result clusters</span></span>
  
<span data-ttu-id="e57b2-120">Die Ergebnis Cluster Erfahrung ist standardmäßig deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="e57b2-120">The result cluster experience is turned off by default.</span></span>  
<span data-ttu-id="e57b2-121">Führen Sie die folgenden Schritte aus, um die Benutzeroberfläche auf Organisationsebene zu aktivieren:</span><span class="sxs-lookup"><span data-stu-id="e57b2-121">Follow these steps to turn on the experience at the organization level:</span></span>

<span data-ttu-id="e57b2-122">Microsoft 365 Admin Center</span><span class="sxs-lookup"><span data-stu-id="e57b2-122">Microsoft 365 Admin Center</span></span>

1. <span data-ttu-id="e57b2-123">Wechseln Sie im [Microsoft 365 Admin Center](https://admin.microsoft.com/)zu **Einstellungen** für die  >  **Suche & Intelligence**  >  **Customization**  >  **Verticals**.</span><span class="sxs-lookup"><span data-stu-id="e57b2-123">In the [Microsoft 365 admin center](https://admin.microsoft.com/), go to **Settings** > **Search & intelligence** > **Customization** > **Verticals**.</span></span>  
2. <span data-ttu-id="e57b2-124">Wählen Sie die Option **alle** vertikal aus, und wechseln Sie zum Abschnitt **Ergebnisse der Konnektoren anzeigen** .</span><span class="sxs-lookup"><span data-stu-id="e57b2-124">Select  the **All** vertical and go to the **Show connector results** section.</span></span> <span data-ttu-id="e57b2-125">Aktivieren Sie die Benutzeroberfläche auf Websiteebene.</span><span class="sxs-lookup"><span data-stu-id="e57b2-125">Turn on the experience at the site level.</span></span>

<span data-ttu-id="e57b2-126">Share</span><span class="sxs-lookup"><span data-stu-id="e57b2-126">Sharepoint</span></span>

1. <span data-ttu-id="e57b2-127">Wechseln Sie auf der SharePoint-Website, auf der Sie das Ergebnis-Cluster-Erlebnis wünschen, zu **Einstellungen**.</span><span class="sxs-lookup"><span data-stu-id="e57b2-127">On the SharePoint site where you want the result cluster experience, go to **Settings**.</span></span>
2. <span data-ttu-id="e57b2-128">Wechseln Sie zu **Website Informationen** > **Alle Websiteeinstellungen anzeigen**.</span><span class="sxs-lookup"><span data-stu-id="e57b2-128">Go to **Site information**>**View all site settings**.</span></span>
3. <span data-ttu-id="e57b2-129">Wechseln Sie zum Abschnitt Microsoft-Suche, und wählen Sie dann **Microsoft-Suche für diese Websitesammlung konfigurieren** aus.</span><span class="sxs-lookup"><span data-stu-id="e57b2-129">Go to the Microsoft Search section, then select **Configure Microsoft Search for this site collection**.</span></span>
4. <span data-ttu-id="e57b2-130">Wechseln Sie im Navigationsbereich zu **benutzerdefiniertes Erlebnis**, und wählen Sie dann **vertikal** aus.</span><span class="sxs-lookup"><span data-stu-id="e57b2-130">In the navigation pane, go to **Custom experience**, then select **Verticals**.</span></span>
5. <span data-ttu-id="e57b2-131">Wählen Sie die Option **alle** vertikal aus, und aktivieren Sie dann **Show Connector results**.</span><span class="sxs-lookup"><span data-stu-id="e57b2-131">Select the **All** vertical, then enable **Show connector results**.</span></span>

## <a name="view-the-result-cluster-experience-after-it-is-enabled"></a><span data-ttu-id="e57b2-132">Anzeigen der Ergebnis Cluster Erfahrung nach der Aktivierung</span><span class="sxs-lookup"><span data-stu-id="e57b2-132">View the result cluster experience after it is enabled</span></span>

<span data-ttu-id="e57b2-133">Nachdem Sie die Ergebnis Cluster Erfahrung aktiviert haben, kann es einige Minuten dauern, bis Sie Sie anzeigen können.</span><span class="sxs-lookup"><span data-stu-id="e57b2-133">After you turn on the result cluster experience, it might take a few minutes before you can view it.</span></span> <span data-ttu-id="e57b2-134">Wenn Sie die Benutzeroberfläche sofort nutzen möchten, können Sie *cacheClear = true* an die URL in SharePoint und Office anfügen.</span><span class="sxs-lookup"><span data-stu-id="e57b2-134">If you want the experience immediately, you can append *cacheClear=true* to the URL in SharePoint and Office.</span></span>