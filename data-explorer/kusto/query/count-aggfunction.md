---
title: count() (aggregation function) - Azure Data Explorer | Microsoft Docs
description: This article describes count() (aggregation function) in Azure Data Explorer.
services: data-explorer
author: orspod
ms.author: orspodek
ms.reviewer: rkarlin
ms.service: data-explorer
ms.topic: reference
ms.date: 01/23/2020
---
# count() (aggregation function)

Returns a count of the records per summarization group (or in total, if summarization is done without grouping).

* Can be used only in context of aggregation inside [summarize](summarizeoperator.md)
* Use the [countif](countif-aggfunction.md) aggregation function
  to count only records for which some predicate returns `true`.

**Syntax**

summarize `count()`

**Returns**

Returns a count of the records per summarization group (or in total, if summarization is done without grouping).