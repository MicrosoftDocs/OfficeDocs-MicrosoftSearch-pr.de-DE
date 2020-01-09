---
title: Verwalten von Akronym-Antworten in der Microsoft-Suche
ms.author: v-pamcna
author: TrishaMc1
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
description: Antworten zum Erstellen und Aktualisieren von Akronymen in Microsoft Search
ms.openlocfilehash: 4f47d5b743709657459ccbc6b03897c29a51e109
ms.sourcegitcommit: 21361af7c244ffd6ff8689fd0ff0daa359bf4129
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 11/14/2019
ms.locfileid: "38626819"
---
# <a name="manage-acronyms-answers-in-microsoft-search"></a><span data-ttu-id="4a159-103">Verwalten von Akronymen Antworten in der Microsoft-Suche</span><span class="sxs-lookup"><span data-stu-id="4a159-103">Manage Acronyms answers in Microsoft Search</span></span>

<span data-ttu-id="4a159-104">Mitarbeiter führen häufig unbekannte Akronyme und Abkürzungen aus, die von Ihrer Organisation oder Ihrem Team verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="4a159-104">Employees often run into unfamiliar acronyms and abbreviations used by their organization or team.</span></span> <span data-ttu-id="4a159-105">Begriffe, die für Organisationen oder Teams spezifisch sind, sind möglicherweise neu für Personen, die von einem Team in ein anderes umziehen, für diejenigen, die mit internen Partnerteams oder neuen Mitarbeitern arbeiten.</span><span class="sxs-lookup"><span data-stu-id="4a159-105">Terms that are specific to organizations or teams might be new to people who move from one team to another, those who work with internal partner teams, or new employees.</span></span>

<span data-ttu-id="4a159-106">Organisationen haben nicht immer einen einzigen Verweis für Ihre Standardterminologie.</span><span class="sxs-lookup"><span data-stu-id="4a159-106">Organizations don't always have a single reference for their standard terminology.</span></span> <span data-ttu-id="4a159-107">Durch das Fehlen eines einzelnen Verweises ist es schwer, Definitionen oder Erweiterungen für diese Akronyme zu finden.</span><span class="sxs-lookup"><span data-stu-id="4a159-107">Lack of a single reference makes it hard to find definitions or expansions for these acronyms.</span></span> <span data-ttu-id="4a159-108">Microsoft Search löst dieses Problem mit Akronymen.</span><span class="sxs-lookup"><span data-stu-id="4a159-108">Microsoft Search solves that problem with Acronyms.</span></span>

## <a name="what-users-experience"></a><span data-ttu-id="4a159-109">Benutzererfahrung</span><span class="sxs-lookup"><span data-stu-id="4a159-109">What users experience</span></span>
<span data-ttu-id="4a159-110">Microsoft Search-Benutzer können Definitionen mit Akronymen in [Bing](https://Bing.com), [Microsoft Office 365](https://Office.com)und [Microsoft SharePoint Online](https://products.office.com/sharepoint/collaboration)abrufen.</span><span class="sxs-lookup"><span data-stu-id="4a159-110">Microsoft Search users can get definitions with Acronyms in [Bing](https://Bing.com), [Microsoft Office 365](https://Office.com), and [Microsoft SharePoint Online](https://products.office.com/sharepoint/collaboration).</span></span> <span data-ttu-id="4a159-111">In den **Such** Feldern in den Kopfzeilenleisten geben Benutzer Abfragen wie diese Beispiele ein:</span><span class="sxs-lookup"><span data-stu-id="4a159-111">In the **Search** boxes in the header bars, users enter queries like these examples:</span></span>

- <span data-ttu-id="4a159-112">*Was ist* DNN</span><span class="sxs-lookup"><span data-stu-id="4a159-112">*What is* DNN</span></span>
- <span data-ttu-id="4a159-113">*Definieren* Sie DNN</span><span class="sxs-lookup"><span data-stu-id="4a159-113">*Define* DNN</span></span>
- <span data-ttu-id="4a159-114">DNN- *Definition*</span><span class="sxs-lookup"><span data-stu-id="4a159-114">DNN *definition*</span></span>
- <span data-ttu-id="4a159-115">*Erweitern* Sie DNN</span><span class="sxs-lookup"><span data-stu-id="4a159-115">*Expand* DNN</span></span>
- <span data-ttu-id="4a159-116">DNN- *Erweiterung*</span><span class="sxs-lookup"><span data-stu-id="4a159-116">DNN *expansion*</span></span>
- <span data-ttu-id="4a159-117">*Bedeutung von* DNN</span><span class="sxs-lookup"><span data-stu-id="4a159-117">*Meaning of* DNN</span></span>
- <span data-ttu-id="4a159-118">DNN *bedeutet*</span><span class="sxs-lookup"><span data-stu-id="4a159-118">DNN *means*</span></span>

<span data-ttu-id="4a159-119">Die vorgeschlagenen Ergebnisse umfassen alle Bedeutungen von DNN, die in der Organisation des Benutzers vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="4a159-119">The suggested results include all the meanings of DNN that are present within the user’s organization.</span></span>

> [!NOTE]
> <span data-ttu-id="4a159-120">Benutzer müssen eine Abfrage eingeben, die die angegebenen *Schlüsselwörter* für das Akronym enthält, um die entsprechenden Antworten auszulösen.</span><span class="sxs-lookup"><span data-stu-id="4a159-120">Users must enter a query that includes the acronym’s specified *keywords* to trigger its corresponding answers.</span></span>  

## <a name="set-up-acronyms-answers"></a><span data-ttu-id="4a159-121">Antworten zum Einrichten von Akronymen</span><span class="sxs-lookup"><span data-stu-id="4a159-121">Set up Acronyms answers</span></span>
<span data-ttu-id="4a159-122">Wechseln Sie im Microsoft 365 [Admin Center](https://admin.microsoft.com)zu **Einstellungen** > **Microsoft-Such** >**Akronyme**, und wählen Sie dann **Akronyme hinzufügen**aus.</span><span class="sxs-lookup"><span data-stu-id="4a159-122">In the Microsoft 365 [admin center](https://admin.microsoft.com), go to **Settings** > **Microsoft Search** >**Acronyms**, and then select **Add acronyms**.</span></span> 

<span data-ttu-id="4a159-123">Microsoft Search fragt zwei Datenquellen ab, um Akronyme Antworten auf die Suchvorgänge von Benutzern bereitzustellen:</span><span class="sxs-lookup"><span data-stu-id="4a159-123">Microsoft Search queries two data sources to provide Acronyms answers to users’ searches:</span></span>

1.  <span data-ttu-id="4a159-124">**Redaktionelle Akronyme**.</span><span class="sxs-lookup"><span data-stu-id="4a159-124">**Editorial acronyms**.</span></span> <span data-ttu-id="4a159-125">Von IT-Administratoren im [Admin Center](https://admin.microsoft.com)bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="4a159-125">Provided by IT administrators in the [admin center](https://admin.microsoft.com).</span></span>
2.  <span data-ttu-id="4a159-126">**Verminte Akronyme**.</span><span class="sxs-lookup"><span data-stu-id="4a159-126">**Mined acronyms**.</span></span> <span data-ttu-id="4a159-127">Durch die Microsoft-Suche von den persönlichen e-Mails und Dokumenten und öffentlich verfügbaren Daten innerhalb der Organisation abgebaut.</span><span class="sxs-lookup"><span data-stu-id="4a159-127">Mined by Microsoft Search from the user’s personal email and documents and publicly available data within the organization.</span></span>

### <a name="set-up-editorial-acronyms"></a><span data-ttu-id="4a159-128">Einrichten von redaktionellen Akronymen</span><span class="sxs-lookup"><span data-stu-id="4a159-128">Set up editorial acronyms</span></span>
<span data-ttu-id="4a159-129">IT-Administratoren können redaktionelle Akronyme auf der [Registerkarte Akronyme](https://admin.microsoft.com/Adminportal/Home#/MicrosoftSearch) im [Microsoft 365 Admin Center]( https://admin.microsoft.com)einrichten.</span><span class="sxs-lookup"><span data-stu-id="4a159-129">IT admins can set up editorial acronyms on the [Acronyms tab](https://admin.microsoft.com/Adminportal/Home#/MicrosoftSearch) in the  [Microsoft 365 admin center]( https://admin.microsoft.com).</span></span> <span data-ttu-id="4a159-130">Sie können Akronyme aus einer internen Website oder einem Repository zum Admin Center hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="4a159-130">You can add acronyms from any internal site or repository to the admin center.</span></span> <span data-ttu-id="4a159-131">Redaktionelle Akronyme können dem **veröffentlichten** oder dem **Entwurfs** Status hinzugefügt werden:</span><span class="sxs-lookup"><span data-stu-id="4a159-131">Editorial acronyms can be added to **Published** or **Draft** state:</span></span>

<span data-ttu-id="4a159-132">**Veröffentlichter Status**.</span><span class="sxs-lookup"><span data-stu-id="4a159-132">**Published state**.</span></span> <span data-ttu-id="4a159-133">Akronyme stehen den Mitarbeitern der Organisation über die Microsoft-Suche zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="4a159-133">Acronyms are available to the organization’s employees through Microsoft Search.</span></span>

> [!NOTE]
> <span data-ttu-id="4a159-134">Es kann bis zu drei Tage dauern, bis Akronyme zum veröffentlichten Status hinzugefügt wurden, um in Microsoft Search verfügbar zu sein.</span><span class="sxs-lookup"><span data-stu-id="4a159-134">It might take up  to three days for acronyms added to Published state to become available in Microsoft Search.</span></span>

<span data-ttu-id="4a159-135">**Entwurfsstatus**.</span><span class="sxs-lookup"><span data-stu-id="4a159-135">**Draft state**.</span></span> <span data-ttu-id="4a159-136">Wenn Administratoren Akronyme Antworten überprüfen möchten, bevor Sie in Microsoft Search verfügbar gemacht werden, können Sie die Akronyme dem Entwurfsstatus hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="4a159-136">If admins want to review Acronyms answers before making them available in Microsoft Search, they can add the acronyms to Draft state.</span></span> <span data-ttu-id="4a159-137">Akronyme, die dem Entwurfsstatus hinzugefügt werden, sind in der Microsoft-Suche nicht verfügbar.</span><span class="sxs-lookup"><span data-stu-id="4a159-137">Acronyms added to Draft state aren’t available in Microsoft Search.</span></span> <span data-ttu-id="4a159-138">Administratoren müssen die Akronyme dem veröffentlichten Status hinzufügen, damit Sie verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="4a159-138">Admins need to add the acronyms to Published state to make them available.</span></span>

<span data-ttu-id="4a159-139">Administratoren können Akronyme einzeln hinzufügen oder Sie in einer CSV-Datei Massenimportieren.</span><span class="sxs-lookup"><span data-stu-id="4a159-139">Admins can add acronyms individually or bulk import them in a CSV file.</span></span> <span data-ttu-id="4a159-140">Laden Sie eine CSV-Datei mit den in der folgenden Tabelle gezeigten Feldern hoch:</span><span class="sxs-lookup"><span data-stu-id="4a159-140">Upload a CSV file with the fields shown in the following table:</span></span>

| <span data-ttu-id="4a159-141">Akronym (obligatorisch)</span><span class="sxs-lookup"><span data-stu-id="4a159-141">Acronym (mandatory)</span></span> | <span data-ttu-id="4a159-142">Expansion (obligatorisch)</span><span class="sxs-lookup"><span data-stu-id="4a159-142">Expansion (mandatory)</span></span> | <span data-ttu-id="4a159-143">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="4a159-143">Description</span></span>  | <span data-ttu-id="4a159-144">Quelle</span><span class="sxs-lookup"><span data-stu-id="4a159-144">Source</span></span> | <span data-ttu-id="4a159-145">Status (obligatorisch)</span><span class="sxs-lookup"><span data-stu-id="4a159-145">State (mandatory)</span></span> |
| --------- | --------- | ---------- | --------- |--------- |
| <span data-ttu-id="4a159-146">*XXX*</span><span class="sxs-lookup"><span data-stu-id="4a159-146">*XXX*</span></span> | <span data-ttu-id="4a159-147">*Abkürzung für buchstabiert*</span><span class="sxs-lookup"><span data-stu-id="4a159-147">*Spelled out abbreviation*</span></span> |  | <span data-ttu-id="4a159-148">*URL*</span><span class="sxs-lookup"><span data-stu-id="4a159-148">*URL*</span></span> | <span data-ttu-id="4a159-149">*Veröffentlicht oder Entwurf*</span><span class="sxs-lookup"><span data-stu-id="4a159-149">*Published or Draft*</span></span> |

### <a name="csv-fields"></a><span data-ttu-id="4a159-150">CSV-Felder</span><span class="sxs-lookup"><span data-stu-id="4a159-150">CSV fields</span></span>
<span data-ttu-id="4a159-151">**Akronym**.</span><span class="sxs-lookup"><span data-stu-id="4a159-151">**Acronym**.</span></span> <span data-ttu-id="4a159-152">Enthält das tatsächliche kurze Formular oder Akronym.</span><span class="sxs-lookup"><span data-stu-id="4a159-152">Contains the actual short form or acronym.</span></span> <span data-ttu-id="4a159-153">Ein Beispiel ist *DNN*.</span><span class="sxs-lookup"><span data-stu-id="4a159-153">An example is *DNN*.</span></span>

<span data-ttu-id="4a159-154">**Erweiterung**.</span><span class="sxs-lookup"><span data-stu-id="4a159-154">**Expansion**.</span></span> <span data-ttu-id="4a159-155">Enthält die Erweiterung des Akronyms.</span><span class="sxs-lookup"><span data-stu-id="4a159-155">Contains the expansion of the acronym.</span></span> <span data-ttu-id="4a159-156">Ein Beispiel ist ein *tiefes neuronales Netzwerk*.</span><span class="sxs-lookup"><span data-stu-id="4a159-156">An example is *Deep Neural Network*.</span></span>

<span data-ttu-id="4a159-157">**Beschreibung**.</span><span class="sxs-lookup"><span data-stu-id="4a159-157">**Description**.</span></span> <span data-ttu-id="4a159-158">Eine kurze Beschreibung des Akronyms, mit der Benutzer schnell Einblicke in die Bedeutung des Akronyms und seiner Erweiterung erhalten.</span><span class="sxs-lookup"><span data-stu-id="4a159-158">A brief description of the acronym that gives users quick insight into what the acronym and its expansion mean.</span></span> <span data-ttu-id="4a159-159">*Ein tiefes neuronales Netzwerk ist beispielsweise ein neuronales Netzwerk mit einem gewissen Grad an Komplexität, ein neuronales Netzwerk mit mehr als zwei Schichten*.</span><span class="sxs-lookup"><span data-stu-id="4a159-159">For example, *A deep neural network is a neural network with a certain level of complexity, a neural network with more than two layers*.</span></span>

<span data-ttu-id="4a159-160">**Source**.</span><span class="sxs-lookup"><span data-stu-id="4a159-160">**Source**.</span></span> <span data-ttu-id="4a159-161">Die URL der Seite oder Website, auf der Benutzer weitere Informationen zum Akronym erhalten möchten.</span><span class="sxs-lookup"><span data-stu-id="4a159-161">The URL of the page or website where you want users to go for more information about the acronym.</span></span>

<span data-ttu-id="4a159-162">**State**.</span><span class="sxs-lookup"><span data-stu-id="4a159-162">**State**.</span></span> <span data-ttu-id="4a159-163">Dieses Feld kann zwei Werte annehmen:</span><span class="sxs-lookup"><span data-stu-id="4a159-163">This field can take two values:</span></span>

- <span data-ttu-id="4a159-164">**Entwurf**.</span><span class="sxs-lookup"><span data-stu-id="4a159-164">**Draft**.</span></span> <span data-ttu-id="4a159-165">Das Akronym wird dem Status Entwurf hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="4a159-165">Adds  the acronym to the Draft state.</span></span>
- <span data-ttu-id="4a159-166">**Veröffentlicht**</span><span class="sxs-lookup"><span data-stu-id="4a159-166">**Published**.</span></span> <span data-ttu-id="4a159-167">Das Akronym wird dem veröffentlichten Zustand hinzugefügt und wird in der Microsoft-Suche zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="4a159-167">Adds the acronym to the Published state and makes it available in Microsoft Search.</span></span>

### <a name="mined-acronyms"></a><span data-ttu-id="4a159-168">Verminte Akronyme</span><span class="sxs-lookup"><span data-stu-id="4a159-168">Mined acronyms</span></span>
<span data-ttu-id="4a159-169">Es kann eine Herausforderung für Administratoren sein, alle in einer Organisation verwendeten Akronyme für Antworten hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="4a159-169">It might be a challenge for admins to add all the acronyms used within an organization to Answers.</span></span> <span data-ttu-id="4a159-170">Dieses Feature kann Akronyme finden, von denen die Suchadministratoren gar nicht wissen.</span><span class="sxs-lookup"><span data-stu-id="4a159-170">This feature can find acronyms that search administrators aren’t even aware of.</span></span> <span data-ttu-id="4a159-171">Dafür werden in Microsoft Search auch Akronyme aus folgenden Quellen untersucht:</span><span class="sxs-lookup"><span data-stu-id="4a159-171">To do that work, Microsoft Search also mines acronyms from these sources:</span></span>

- <span data-ttu-id="4a159-172">Benutzer-e-Mails.</span><span class="sxs-lookup"><span data-stu-id="4a159-172">Users’ emails.</span></span>
- <span data-ttu-id="4a159-173">Dokumente in [SharePoint](https://products.office.com/sharepoint/collaboration), [Microsoft OneDrive]( https://onedrive.live.com/about/) und [Microsoft OneNote](http://www.onenote.com/).</span><span class="sxs-lookup"><span data-stu-id="4a159-173">Documents in [SharePoint](https://products.office.com/sharepoint/collaboration), [Microsoft OneDrive]( https://onedrive.live.com/about/) and [Microsoft OneNote](http://www.onenote.com/).</span></span>
- <span data-ttu-id="4a159-174">Öffentliche Dokumente innerhalb der Organisation, auf die Benutzer in SharePoint, OneDrive oder OneNote zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="4a159-174">Public documents within the organization that users have access to in SharePoint, OneDrive, or OneNote.</span></span>

<span data-ttu-id="4a159-175">Die Microsoft-Suche stellt sicher, dass nur Benutzer mit Zugriff und Berechtigungen für ein Dokument die von dieser abgebauten Akronyme sehen können.</span><span class="sxs-lookup"><span data-stu-id="4a159-175">Microsoft Search makes sure that only users with access and permissions to a document can see the acronyms that are mined from it.</span></span> <span data-ttu-id="4a159-176">Die Akronyme werden aus dem Posteingang eines Benutzers abgebaut und im Benutzer Fragment gespeichert.</span><span class="sxs-lookup"><span data-stu-id="4a159-176">The acronyms are mined from a user’s inbox and stored in the user shard.</span></span> <span data-ttu-id="4a159-177">Nur der Benutzer kann auf die im Posteingang des Benutzers verminten Akronyme zugreifen.</span><span class="sxs-lookup"><span data-stu-id="4a159-177">Only the user can access the acronyms mined from the user’s own inbox.</span></span>

> [!NOTE]
> <span data-ttu-id="4a159-178">Für verminte Akronyme ist kein IT-Administratorsetup erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4a159-178">No IT admin setup is needed for mined acronyms.</span></span>

## <a name="frequently-asked-questions"></a><span data-ttu-id="4a159-179">Häufig gestellte Fragen</span><span class="sxs-lookup"><span data-stu-id="4a159-179">Frequently asked questions</span></span>
<span data-ttu-id="4a159-180">**F.: wie werden redaktionelle und verminte Daten bewertet?**</span><span class="sxs-lookup"><span data-stu-id="4a159-180">**Q: How is editorial and mined data ranked?**</span></span>

<span data-ttu-id="4a159-181">**A:** Das Feature zählt derzeit redaktionelle Akronyme oberhalb der abgebauten Akronyme.</span><span class="sxs-lookup"><span data-stu-id="4a159-181">**A:** The feature currently ranks editorial acronyms above mined acronyms.</span></span>

<span data-ttu-id="4a159-182">**F.: wie lange dauert es, bis redaktionelle Akronyme in der Microsoft-Suche sichtbar sind, nachdem Sie veröffentlicht wurden?**</span><span class="sxs-lookup"><span data-stu-id="4a159-182">**Q: How long does it take for editorial acronyms to be visible in Microsoft Search after they’re published?**</span></span>

<span data-ttu-id="4a159-183">**A:**  Es dauert bis zu drei Tage, bis Akronyme zum veröffentlichten Status hinzugefügt wurden, um in Microsoft Search verfügbar zu sein.</span><span class="sxs-lookup"><span data-stu-id="4a159-183">**A:**  It takes up  to three days for acronyms added to Published state to become available in Microsoft Search.</span></span> 

<span data-ttu-id="4a159-184">**F.: wie lösen Benutzer Akronyme Antworten aus?**</span><span class="sxs-lookup"><span data-stu-id="4a159-184">**Q: How do users trigger Acronyms answers?**</span></span>

<span data-ttu-id="4a159-185">**A**: um Akronyme Antworten zu erhalten, müssen Benutzer bestimmte Abfragemuster in einem [Bing](https://bing.com)-, [Office 365](https://Office.com)-oder [SharePoint](https://products.office.com/sharepoint/collaboration) - **Suchfeld** eingeben.</span><span class="sxs-lookup"><span data-stu-id="4a159-185">**A**: To get Acronyms answers, users must enter specific query patterns in a [Bing](https://bing.com), [Office 365](https://Office.com), or [SharePoint](https://products.office.com/sharepoint/collaboration) **Search** box.</span></span> <span data-ttu-id="4a159-186">Beispiele für Abfragen, die Antworten für den Begriff *DNN* finden, lauten wie folgt:</span><span class="sxs-lookup"><span data-stu-id="4a159-186">Examples of queries that find answers for the term *DNN* are as follows:</span></span>

- <span data-ttu-id="4a159-187">*Was ist* DNN</span><span class="sxs-lookup"><span data-stu-id="4a159-187">*What is* DNN</span></span>
- <span data-ttu-id="4a159-188">*Definieren* Sie DNN</span><span class="sxs-lookup"><span data-stu-id="4a159-188">*Define* DNN</span></span>
- <span data-ttu-id="4a159-189">DNN- *Definition*</span><span class="sxs-lookup"><span data-stu-id="4a159-189">DNN *definition*</span></span>
- <span data-ttu-id="4a159-190">*Erweitern* Sie DNN</span><span class="sxs-lookup"><span data-stu-id="4a159-190">*Expand* DNN</span></span>
- <span data-ttu-id="4a159-191">DNN- *Erweiterung*</span><span class="sxs-lookup"><span data-stu-id="4a159-191">DNN *expansion*</span></span>
- <span data-ttu-id="4a159-192">*Bedeutung von* DNN</span><span class="sxs-lookup"><span data-stu-id="4a159-192">*Meaning of* DNN</span></span>
- <span data-ttu-id="4a159-193">DNN *bedeutet*</span><span class="sxs-lookup"><span data-stu-id="4a159-193">DNN *means*</span></span>

<span data-ttu-id="4a159-194">**F.: wie lange dauert es, bis abgebaute Akronyme angezeigt werden, nachdem Sie eine neue e-Mail oder ein neues Dokument empfangen oder gesendet haben?**</span><span class="sxs-lookup"><span data-stu-id="4a159-194">**Q: How long does it take for mined acronyms to appear after you receive or send a new email or document?**</span></span>

<span data-ttu-id="4a159-195">**A:** Verminte Akronyme aus einer neuen e-Mail oder einem Dokument benötigen bis zu sieben Tage, um in Microsoft-Suchergebnissen angezeigt zu werden.</span><span class="sxs-lookup"><span data-stu-id="4a159-195">**A:** Mined acronyms from a new email or document take up to seven days to appear in Microsoft Search results.</span></span>

<span data-ttu-id="4a159-196">**F.: müssen Dokumente in einem bestimmten Format vorliegen, damit Sie von Mining abgeholt werden können?**</span><span class="sxs-lookup"><span data-stu-id="4a159-196">**Q: Do documents need to be in a specific format for mining to pick them up?**</span></span>

<span data-ttu-id="4a159-197">**A:** Nein.</span><span class="sxs-lookup"><span data-stu-id="4a159-197">**A:** No.</span></span> <span data-ttu-id="4a159-198">Wir unterstützen alle Dateitypen außer Bild, Ordner und ZIP-Dateien.</span><span class="sxs-lookup"><span data-stu-id="4a159-198">We support all file types except image, folders, and zip files.</span></span>

<span data-ttu-id="4a159-199">**F.: werden Microsoft-Akronyme aus Dokumenten in allen Sprachen erhalten?**</span><span class="sxs-lookup"><span data-stu-id="4a159-199">**Q: Will Microsoft mine acronyms from documents in all languages?**</span></span>

<span data-ttu-id="4a159-200">**A**: Microsoft unterstützt nur das Mining von Dokumenten in englischer Sprache.</span><span class="sxs-lookup"><span data-stu-id="4a159-200">**A**: Microsoft only supports mining from documents in English.</span></span> <span data-ttu-id="4a159-201">Unterstützung für andere Sprachen wird in Phasen hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="4a159-201">Support for other languages will be added in phases.</span></span>

<span data-ttu-id="4a159-202">**F.: Was geschieht, wenn meine Organisation keine verminten Akronyme anzeigen möchte? Kann ich das Anzeigen von verminten Akronymen in Suchergebnissen beenden?**</span><span class="sxs-lookup"><span data-stu-id="4a159-202">**Q: What if my organization doesn’t want to show mined acronyms? Can I stop showing mined acronyms in search results?**</span></span>

<span data-ttu-id="4a159-203">**A**: um die Anzeige von verminten Akronymen in Suchergebnissen zu deaktivieren, erstellen Sie ein Kundensupport Ticket, indem Sie die Anweisungen unter [Contact Support for Business Products](https://docs.microsoft.com/office365/admin/contact-support-for-business-products?redirectSourcePath=%252fen-us%252farticle%252fContact-Office-365-for-business-support-32a17ca7-6fa0-4870-8a8d-e25ba4ccfd4b&view=o365-worldwide&tabs=online#BKMK_call_support)befolgen.</span><span class="sxs-lookup"><span data-stu-id="4a159-203">**A**: To turn off showing mined acronyms in search results, create a customer support ticket by following the instructions at [Contact support for business products](https://docs.microsoft.com/office365/admin/contact-support-for-business-products?redirectSourcePath=%252fen-us%252farticle%252fContact-Office-365-for-business-support-32a17ca7-6fa0-4870-8a8d-e25ba4ccfd4b&view=o365-worldwide&tabs=online#BKMK_call_support).</span></span>
<span data-ttu-id="4a159-204">Nachdem Sie ein Support Ticket erstellt haben, dauert es bis zu 48 Stunden, damit verminte Akronyme nicht mehr in den Suchergebnissen angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="4a159-204">After you create a support ticket, it takes up to 48 hours for mined acronyms to stop appearing in search results.</span></span> 

<span data-ttu-id="4a159-205">**F.: Wann werden Akronyme Antworten in [Office 365](https://Office.com) und [SharePoint Online](https://products.office.com/sharepoint/collaboration)angezeigt?**</span><span class="sxs-lookup"><span data-stu-id="4a159-205">**Q: When will I see Acronyms answers in [Office 365](https://Office.com) and [SharePoint Online](https://products.office.com/sharepoint/collaboration)?**</span></span>

<span data-ttu-id="4a159-206">**A**: Akronyme Antworten sind derzeit nur in der Microsoft-Suche in [Bing](https://bing.com)verfügbar.</span><span class="sxs-lookup"><span data-stu-id="4a159-206">**A**: Acronyms answers are currently only available in Microsoft Search in [Bing](https://bing.com).</span></span> <span data-ttu-id="4a159-207">Sie werden in Office 365 und SharePoint Online in 2020 eingeführt.</span><span class="sxs-lookup"><span data-stu-id="4a159-207">They’ll be rolled out to Office 365 and SharePoint Online in 2020.</span></span>