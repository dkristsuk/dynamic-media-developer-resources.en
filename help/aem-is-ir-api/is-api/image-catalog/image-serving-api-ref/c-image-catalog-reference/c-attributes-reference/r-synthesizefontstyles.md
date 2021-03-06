---
description: Enable synthesized font variations. Controls whether the server should generate an error response or synthesize a bold, italic, or bold/italic font style if such a style is requested but cannot be found in the font map.
seo-description: Enable synthesized font variations. Controls whether the server should generate an error response or synthesize a bold, italic, or bold/italic font style if such a style is requested but cannot be found in the font map.
seo-title: SynthesizeFontStyles
solution: Experience Manager
title: SynthesizeFontStyles
topic: Scene7 Image Serving - Image Rendering API
uuid: f1c67490-7f14-4a6c-a7ba-5a476231ef34
---

# SynthesizeFontStyles{#synthesizefontstyles}

Enable synthesized font variations. Controls whether the server should generate an error response or synthesize a bold, italic, or bold/italic font style if such a style is requested but cannot be found in the font map.

>[!NOTE]
>
>Synthesizing font styles often result in lower-quality renderings than using actual fonts for such styles.

## Properties {#section-3205560a74774ebf9c916b07bd15aca6}

Flag. Set to 0 to disable and to 1 to enable synthetic font styles.

## Default {#section-71f94aa65e404d14b441674c040b59e3}

Inherited from `default::SynthesizeFontStyles` if not defined or if empty.

## See also {#section-47a79659cc844272b6d5f36c946e12ac}

[Font Map Reference](../../../../../is-api/image-catalog/image-serving-api-ref/c-image-catalog-reference/c-font-map-reference/c-font-map-reference.md#concept-f81f319d03c646c5a8ef87b3277dd37d) 
