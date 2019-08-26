---
description: null
seo-description: null
seo-title: ThumbnailGridView.fmt
solution: Experience Manager
title: ThumbnailGridView.fmt
topic: Dynamic media
uuid: 6aaac931-af78-4f63-9345-6c2580f52414
index: y
internal: n
snippet: y
---

# ThumbnailGridView.fmt{#thumbnailgridview-fmt}

 `[ThumbnailGridView.|<containerId>_gridView.]fmt=jpg|jpeg|png|png-alpha|gif|gif-alpha`

<table id="table_4620F51BD77149FDB68F1FBECC443801"> 
 <tbody> 
  <tr> 
   <td> <p> <span class="codeph"> jpg|jpeg|png|png-alpha|gif|gif-alpha</span> </p> </td> 
   <td> <p>Specifies the image format that the component uses for loading images from Image Server. It can be any value that Image Server and the client browser supports. If the specified format ends with <span class="codeph"> -alpha</span>, the component renders images as transparent content. For all other image formats the component treats images as opaque. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Properties {#section-ffe8ccc3a5f2474db47a68c2ad9a96d6}

Optional.

## Default {#section-502c098dbae1452180c7f575a1d9dc8b}

`jpeg`

## Example {#section-5cde7b856ba646c293cfd3d79e47c507}

`fmt-png-alpha` 