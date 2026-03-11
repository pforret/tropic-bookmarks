---
title: "Digital Cinema Package (DCP): Specifications &amp; Requirements"
description: "Netflix's official DCP spec: when to use Interop vs SMPTE standard, plus requirements for HFR, Dolby Atmos, and HDR/Dolby Vision."
pubDate: "2026-03-11T20:52:19.891Z"
url: "https://partnerhelp.netflixstudios.com/hc/en-us/articles/4417542010387-Digital-Cinema-Package-DCP-Specifications-Requirements"
heroImage: "/bookmarks/1773262327548.comh"
---

Netflix Partner Help's technical reference for authoring Digital Cinema Packages (DCP) submitted to Netflix. It defines when to use the Interop (IOP) standard versus SMPTE — with SMPTE required for High Frame Rate, Dolby Atmos, and HDR/Dolby Vision content.

Each SMPTE use case has distinct authoring rules. Dolby Atmos DCPs must be fully flattened OV compositions with subtitles burned into the video MXF. HDR/Dolby Vision requires a CompositionMetadataAsset with specific Dolby Vision Extension metadata in the CPL. HFR and Atmos must NOT include the CompositionMetadataAsset. All three must avoid audio MXF MCA sub descriptor label ULs.

Additional requirements cover reel/segment structure (max 22 minutes each), frame boundaries, and seamless conformance for long-play content. This spec is the authoritative starting point for any facility delivering DCP content to Netflix.

[Read more](https://partnerhelp.netflixstudios.com/hc/en-us/articles/4417542010387-Digital-Cinema-Package-DCP-Specifications-Requirements)
