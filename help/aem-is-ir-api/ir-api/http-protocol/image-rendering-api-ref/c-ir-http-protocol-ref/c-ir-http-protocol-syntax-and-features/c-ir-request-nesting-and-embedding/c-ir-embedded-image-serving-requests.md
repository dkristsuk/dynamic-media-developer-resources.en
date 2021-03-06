---
description: An Image Server (IS) request can be used as a material image.
seo-description: An Image Server (IS) request can be used as a material image.
seo-title: Embedded Image Server requests
solution: Experience Manager
title: Embedded Image Server requests
topic: Scene7 Image Serving - Image Rendering API
uuid: dd72880d-8824-40b3-a5da-0f6ff4922939
---

# Embedded Image Server requests{#embedded-image-server-requests}

An Image Server (IS) request can be used as a material image.

Specify the request in the `src=` command as follows:

` …&src=is( *[!DNL imageServingRequest]*)&…`

The `is` token is case-sensitive.

The nested request must not include the Image Serving root path (typically [!DNL http:// *[!DNL server]*/is/image/"]), but may include pre-processing rule tokens.

The following IS commands are ignored when specified in nested requests (either in the request URL or in `catalog::Modifier` or `catalog::PostModifier`):

* `bgc=` 
* `fmt=` 
* `icc=` 
* `iccEmbed=` 
* `printRes=` 
* `qlt=` 
* `quantize=` 
* `req=`

Also ignored are `attribute::MaxPix` and `attribute::DefaultPix` of the image catalog that applies to the embedded IS request.

If the result image of the nested request includes mask (alpha) data, it is always passed to the material. Use a solid color background image layer to avoid unwanted alpha.

The image result of an embedded IS request can be cached optionally by including `cache=on`. By default, caching of intermediate data is disabled. Caching should be enabled only when the intermediate image is expected to be reused in a different request within a reasonable time period. Standard server-side cache management applies. Data is cached in a lossless format. 
