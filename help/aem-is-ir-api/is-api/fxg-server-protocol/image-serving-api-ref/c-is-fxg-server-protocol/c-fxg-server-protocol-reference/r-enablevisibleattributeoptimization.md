---
description: Enables the optimization of FXG.
seo-description: Enables the optimization of FXG.
seo-title: enableVisibleAttributeOptimization
solution: Experience Manager
title: enableVisibleAttributeOptimization
topic: Scene7 Image Serving - Image Rendering API
uuid: 7f79aa12-6364-4b34-b547-88d4a778c015
---

# enableVisibleAttributeOptimization{#enablevisibleattributeoptimization}

Enables the optimization of FXG.

<table id="simpletable_FDE0D8786BC747AF87A336452500E695"> 
 <tr class="strow"> 
  <td class="stentry"> <p><span class="codeph"> &amp;enableVisibleAttributeOptimization</span> </p> </td> 
  <td class="stentry"> <p>0|1 </p></td> 
 </tr> 
</table>

Removes the elements whose visibility is set as false in FXG while passing this FXG which in turn reduces the processing time of FXG. Though it removes only those elements with visibility as false that would not impact any other element in FXG. For example, if there is text on `Path` and visibility of `Path` is set as false, then it is not removed from FXG even with this modifier enabled because text needs to be drawn on this path.

Default is 1. 
