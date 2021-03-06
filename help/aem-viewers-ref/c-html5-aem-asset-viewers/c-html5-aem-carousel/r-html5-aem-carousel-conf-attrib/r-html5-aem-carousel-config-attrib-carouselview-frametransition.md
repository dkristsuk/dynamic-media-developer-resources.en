---
description: null
seo-description: null
seo-title: CarouselView.frametransition
solution: Experience Manager
title: CarouselView.frametransition
topic: Dynamic media
uuid: 9539ede1-08fb-4bfc-8a5a-870c7d84de7f
---

# CarouselView.frametransition{#carouselview-frametransition}

 ` [CarouselView.|<containerId>_carouselView.]frametransition=none|fade|slide[, *`duration`*[, *`spacing`*]`

<table id="table_D5992FCFF26046079089652B211BB6C5"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> none|fade|slide </span> </p> </td> 
   <td colname="col2"> <p>Specifies the type of the effect applied on frame change. <span class="codeph"> none </span> stands for no transition; frame change happens instantly. </p> <p> <span class="codeph"> fade </span> means cross-fade transition between old and new frames. </p> <p> <span class="codeph"> slide </span> activates transition where the old frame slides out of the view and the new frame slides in. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> <span class="varname"> duration </span> </span> </p> </td> 
   <td colname="col2"> <p>Specifies the duration (in second) of <span class="codeph"> fade </span> or <span class="codeph"> slide </span> transition effect. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> <span class="varname"> spacing </span> </span> </p> </td> 
   <td colname="col2"> <p>The spacing between adjacent frames in <span class="codeph"> slide </span> transition, has the range between <span class="codeph"> 0 </span> and <span class="codeph"> 1 </span> and is relative to component's width. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Properties {#section-1e637b22e8a44d759d588e47576891e6}

Optional.

## Default {#section-71fb773f814649b2885aefee68073641}

None.

## Example {#section-bce98c31f08a4a0ab262fab7f95ba020}

`frametransition=fade,0.3` 
