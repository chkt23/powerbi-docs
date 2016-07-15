<properties
pageTitle="Row-level security (RLS) with Power BI Desktop"
description="How to configure row-level security for imported datasets, and DirectQuery, within Power BI Desktop."
services="powerbi"
documentationCenter=""
authors="guyinacube"
manager="mblythe"
backup=""
editor=""
tags=""
qualityFocus="no"
qualityDate=""/>

<tags
ms.service="powerbi"
ms.devlang="NA"
ms.topic="article"
ms.tgt_pltfrm="na"
ms.workload="powerbi"
ms.date="07/13/2016"
ms.author="asaxton"/>
# Row-level security (RLS) with Power BI Desktop (Preview)

Row-level security (RLS) with Power BI Desktop can be used to restrict data access for given users. Filters restrict data at the row level. You can define filters within roles.

> **Note:** RLS is a Pro feature. You can read more about what [Pro content](powerbi-power-bi-pro-content-what-is-it.md) is.

You can now configure RLS for data models imported into Power BI with Power BI Desktop. You can also configure RLS on datasets that are using DirectQuery, such as SQL Server. Previously, you were only able to implement RLS within on-premises Analysis Services models outside of Power BI. For Analysis Services live connections, you configure Row-level security on the on-premises model. The security option will not show up for live connection datasets.

> **Note**: The preview is intended to let users start trying out the feature. It will also allow us to collect feedback for improvements. It is not intended for operational usage. Rules defined during the preview may not be available when the feature is generally available.

> **Important:** If you defined roles/rules within the Power BI service, you will need to recreate those roles within Power BI Desktop and publish the report to the service.

Learn more about options for [RLS within the Power BI Service](powerbi-admin-rls.md).

[AZURE.INCLUDE [include-short-name](../includes/rls-desktop-define-roles.md)]

[AZURE.INCLUDE [include-short-name](../includes/rls-desktop-view-as-roles.md)]

[AZURE.INCLUDE [include-short-name](../includes/rls-limitations.md)]

[AZURE.INCLUDE [include-short-name](../includes/rls-faq.md)]

## See also

[Row-level security (RLS) with the Power BI service (Preview)](powerbi-admin-rls.md)