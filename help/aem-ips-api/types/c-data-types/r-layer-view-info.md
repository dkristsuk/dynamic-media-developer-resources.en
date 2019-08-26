---
description: Layer view properties.
seo-description: Layer view properties.
seo-title: LayerViewInfo
solution: Experience Manager
title: LayerViewInfo
topic: Scene7 Image Production System API
uuid: d02306ee-ac45-4700-8c86-1be25d0c7751
index: y
internal: n
snippet: y
---

# LayerViewInfo{#layerviewinfo}

Layer view properties.

 Syntax 

## Parameters {#section-2fc9bea56b6d4b72b80d4f04c5f9b862}

|  Name  | Type  | Description  |
|---|---|---|
|  ` *`url`*`  | `xsd:string`  |Image server URL that represents the template. Combines `urlModifier` and `urlPostAp- plyModifier` fields.  |
|  ` *`urlModifier`*`  | `xsd:string`  |Image serving protocol commands to apply prior to request or `urlPostApplyModifier` commands.  |
|  ` *`urlPostApplyModifier`*`  | `xsd:string`  |Image serving protocol commands to apply after `urlModifier` and request commands.  |
