---
description: Property data consists of a text string representing one or more properties.
seo-description: Property data consists of a text string representing one or more properties.
seo-title: Property data
solution: Experience Manager
title: Property data
topic: Scene7 Image Serving - Image Rendering API
uuid: 7fa6ae70-8d70-41d6-9e47-7df3d616874c
---

# Property data{#property-data}

Property data consists of a text string representing one or more properties.

A property consists of a property name and a property value, separated by =.

Multiple properties are separated by line separators, which may be either `??` or `<CR><LF>`. If the entire property data string is not enclosed in quotation marks, the server replaces each occurrence of `??` with `<CR><LF>` before transmitting the data to the client. Property names may consist of letters, numbers, '.', '-', and '_'. Property names are not case sensitive.

Property values must not include line separators.

See [Text String](../../../../../../is-api/image-catalog/image-serving-api-ref/c-image-catalog-reference/c-overview/c-common-data-types/r-text-string.md#reference-ae0a9e181b0e40c6bcdb43af7f481d63) for additional rules applied to Property Data. 
