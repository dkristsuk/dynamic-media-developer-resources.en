---
description: JavaScript API reference for Video360 Viewer.
seo-description: JavaScript API reference for Video360 Viewer.
seo-title: setAsset
solution: Experience Manager
title: setAsset
topic: Dynamic media
uuid: db1321fb-6d52-4add-8877-0c13eb12e6af
index: y
internal: n
snippet: y
---

# setAsset{#setasset}

JavaScript API reference for Video360 Viewer.

 `setAsset(asset)`

Sets the new asset. You can call this parameter at any time, either before or after `init()`. If it is called after `init()`, the viewer swaps the asset at runtime.

See also [init](../../../c-html5-aem-asset-viewers/c-html5-aem-video360/c-html5-aem-video360-javascriptapiref/r-html5-aem-video360-javascriptapiref-init.md#reference-aee94dd92a28410784f7a1792e28683b).

<table id="table_896DFF34A68A403DB93A6D597461A573"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> asset </span> </p> </td> 
   <td colname="col2"> <p>{<span class="codeph"> String</span>} new asset ID. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Returns {#section-1d3cf85bc7cc4dfe9670e038d02b9101}

None.

## Example {#section-9e9332aa86b74a5fb321375c03fdc5b3}

```
<instance>.setAsset("Viewers/space_station_360-AVS")
```
