---
description: Image catalogs are used to provide information about images and supporting data (such as fonts and ICC profiles) to the server.
seo-description: Image catalogs are used to provide information about images and supporting data (such as fonts and ICC profiles) to the server.
seo-title: Overview
solution: Experience Manager
title: Overview
topic: Scene7 Image Serving - Image Rendering API
uuid: e8c0401b-9161-4624-babb-6c7afb443e65
---

# Overview{#overview}

Image catalogs are used to provide information about images and supporting data (such as fonts and ICC profiles) to the server.

 Image catalogs are used to provide information about images and supporting data (such as fonts and ICC profiles) to the server.

Each image catalog consists of a required catalog attribute file and a set of optional catalog data files:

* The image data file, which itemizes images and templates and their associated metadata. 
* The SVG data file, which itemizes SVG files and their associated metadata. 
* The macro definitions file, which provides definitions for request macros. 
* The font map file, which keeps track of text fonts. 
* The profile map file, which itemizes ICC color profiles. 
* The rule set file, which defines HTTP request pre-processing rules.

Catalog data files are associated with image catalogs by file references in the catalog attribute file. The same catalog data file can be shared by multiple image catalogs.

Catalog attribute files must have an [!DNL .ini] file suffix and must be located in the Platform Server's catalog folder ( `PlatformServer::catalog.rootPath`). Catalog data files can be located in the same folder or any other folder accessible to the Platform Server.

This document describes the Image Catalog file format for the Scene7 Image Serving system. The intended audience is experienced programmers and web site developers who want to leverage Scene7 Image Serving for a web or custom application.

It is assumed that the reader is generally familiar with the Scene7 Image Serving system, general HTTP protocol standards and conventions, and basic imaging terminology. 
