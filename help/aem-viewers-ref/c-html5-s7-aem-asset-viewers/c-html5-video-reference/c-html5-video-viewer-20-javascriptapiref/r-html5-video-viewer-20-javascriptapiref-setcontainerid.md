---
description: JavaScript API reference for Video Viewer.
seo-description: JavaScript API reference for Video Viewer.
seo-title: setContainerId
solution: Experience Manager
title: setContainerId
topic: Dynamic media
uuid: a4b741a1-b0b3-4bc3-aeab-9d0e44ec4e79
index: y
internal: n
snippet: y
---

# setContainerId{#setcontainerid}

JavaScript API reference for Video Viewer.

 ` setContainerId( *`containerId`*)`

Sets the ID of the DOM container (normally a `DIV`) that the viewer is inserted into. It is not necessary to have the container element created by the time this method is called. However, the container must exist when `init()` is run. This parameter is called before `init()`. This method is optional if the viewer configuration information is passed with `config` JSON object to the constructor.

<table id="table_896DFF34A68A403DB93A6D597461A573"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> <span class="varname"> containerId </span> </span> </p> </td> 
   <td colname="col2"> <p> <span class="codeph"> {string} </span> ID of container. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Returns {#section-1d3cf85bc7cc4dfe9670e038d02b9101}

None.

## Example {#section-9e9332aa86b74a5fb321375c03fdc5b3}

```
<instance>.setContainerId("s7viewer");
```
