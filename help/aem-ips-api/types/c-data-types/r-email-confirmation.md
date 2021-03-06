---
description: Sends an email to a designated recipient in response to a cdnCacheInvalidation operation.
seo-description: Sends an email to a designated recipient in response to a cdnCacheInvalidation operation.
seo-title: EmailConfirmation
solution: Experience Manager
title: EmailConfirmation
topic: Scene7 Image Production System API
uuid: c3b7aada-a03a-418d-80b2-31a86a1af786
---

# EmailConfirmation{#emailconfirmation}

Sends an email to a designated recipient in response to a cdnCacheInvalidation operation.

 Syntax 

## Parameters {#section-490717fe96bf40c2a5a2f7ccbfaab3d0}

|  Name  | Type  | Description  |
|---|---|---|
|  ` *`ccOriginator`*`  | `xsd:boolean`  | If true, includes the user's web service user account, which is a list of emails designated to receive an email confirmation from the Scene7 CDN.  |
|  ` *`ccOthersArray`*`  | `types:EmailArray`  | An array of email addresses (5 maximum) designated to receive the confirmation notification from the Scene7 CDN.  |

