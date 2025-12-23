
---
title: L3VPN Mind Map
layout: none
---

<!-- Global Courier New font -->
<style>
  html, body {
    font-family: "Courier New", Courier, monospace;
  }
  /* Optional: subtle glow on hover over Mermaid nodes */
  .mermaid svg g.node:hover > rect,
  .mermaid svg g.node:hover > circle,
  .mermaid svg g.node:hover > polygon {
    filter: drop-shadow(0 0 6px rgba(70,180,255,0.50));
    transition: filter 200ms ease;
    cursor: pointer;
  }
</style>

# L3VPN Mind Map (Mermaid)

Below is a Mermaid mindmap rendered client-side.  
**Color scheme**: dark gray nodes, white subtopic cards, black-ish connector lines.  
**Font**: Courier New.

```mermaid
%%{init: { 
  "theme": "neutral",
  "securityLevel": "loose",
  "themeVariables": {
    "fontFamily": "Courier New, Courier, monospace",
    "primaryColor": "#4a4a4a",        /* dark gray tabs */
    "primaryTextColor": "#ffffff",     /* white text on dark tabs */
    "lineColor": "#2f2f2f",            /* connector strokes */
    "tertiaryColor": "#f6f6f6",        /* light gray for subtopic cards */
    "background": "#ffffff"            /* page background */
  }
}}%%
mindmap
  root((L3VPN))
    Pre-requisites
      https://yourdomain.example/prereq/ospf
      https://yourdomain.example/prereq/bgp
      https://yourdomain.example/prereq/mpls

    https://yourdomain.example/l3vpn/introduction
      https://yourdomain.example/l3vpn/introduction/subtopic-1
      https://yourdomain.example/l3vpn/introduction/subtopic-2

    https://yourdomain.example/l3vpn/main-topic-5
    https://yourdomain.example/l3vpn/main-topic-9
