---
description: Configuration attribute for Video Video Viewer.
seo-description: Configuration attribute for Video Video Viewer.
seo-title: CallToAction.direction
solution: Experience Manager
title: CallToAction.direction
topic: Dynamic media
uuid: fe182e8f-696d-4515-afdb-49964a374dae
index: y
internal: n
snippet: y
---

# CallToAction.direction{#calltoaction-direction}

Configuration attribute for Video Video Viewer.

 `[CallToAction.|<containerId>_callToAction.]direction=auto|left|right`

<table id="table_441553CD34C94A58A9D7CBF772DEDDB6"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> auto|left|right </span> </p> </td> 
   <td colname="col2"> <p> Specifies the way thumbnails fill in the view. </p> <p>Set to <span class="codeph"> left </span> to set the left-to-right fill order. </p> <p>Set to <span class="codeph"> right </span> reverses the order so that the view is filled in a right-to-left, top-to-bottom direction. </p> <p>Set to <span class="codeph"> auto </span> to have the component apply right mode when the locale is set to <span class="codeph"> "ja" </span>; otherwise, <span class="codeph"> left </span> is used. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Properties {#section-1e637b22e8a44d759d588e47576891e6}

Optional.

## Default {#section-71fb773f814649b2885aefee68073641}

`auto`

## Example {#section-bce98c31f08a4a0ab262fab7f95ba020}

```
direction=right
```
