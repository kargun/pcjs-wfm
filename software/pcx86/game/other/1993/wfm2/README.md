---
layout: simple
title: "WFM 2.0 (1993)"
permalink: /
machines:
  - id: ibm5170
    type: pcx86
    config: /machines/pcx86/ibm/5170/vga/2048kb/machine.xml
    drives: '[{name:"20Mb Hard Disk",type:2,path:"/gamedisks/pcx86/game/other/1993/wfm2/WFM2-20MB.json"}]'
    autoMount:
      A: "None"
      B: "None"
redirect_from:
  - /wfm
---

{% include machine.html id="ibm5170" %}
