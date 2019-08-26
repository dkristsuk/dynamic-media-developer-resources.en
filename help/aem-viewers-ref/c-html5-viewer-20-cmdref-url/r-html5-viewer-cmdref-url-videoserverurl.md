---
description: Parameter common to all viewers.
seo-description: Parameter common to all viewers.
seo-title: videoServerUrl
solution: Experience Manager
title: videoServerUrl
topic: Dynamic media
uuid: ef9870f9-599b-449d-b713-66abafb80311
index: y
internal: n
snippet: y
---

# videoServerUrl{#videoserverurl}

Parameter common to all viewers.

>[!NOTE]
>
>This command does not apply to Video Image Viewer.

` videoServerUrl= *`videoRootPath`*`

<table id="table_9B98C97485DD4DEB8A6ECBCE8DF6B886"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> <span class="varname"> videoRootPath</span> </span> </p> </td> 
   <td colname="col2"> <p> The video server root path. If no domain is specified, then the domain from which the page is served is applied instead. Standard URI path resolution applies. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Properties {#section-10ee45d637134e0fbcd943c62578cb78}

Optional. Not needed for standard software as a service usage.

## Default {#section-d411e450028c460392cb8508f8ccc5d9}

`/is/content/`

## Example {#section-a8afbf76f8384aa0a83ed1feeccd5b9a}

```
videoServerUrl=http://s7d1.scene7.com/is/content/
```
