
---
title: L3VPN Mind Map
layout: none
---

<style>
  html, body { font-family: "Courier New", Courier, monospace; }
  .mermaid svg g.node:hover > rect,
  .mermaid svg g.node:hover > circle,
  .mermaid svg g.node:hover > polygon {
    filter: drop-shadow(0 0 6px rgba(70,180,255,0.50));
    transition: filter 200ms ease;
    cursor: pointer;
  }
</style>

# L3VPN Mind Map (Mermaid)

{% raw %}
<div class="mermaid">
%%{init: {
  "theme": "neutral",
  "securityLevel": "loose",
  "themeVariables": {
    "fontFamily": "Courier New, Courier, monospace",
    "primaryColor": "#4a4a4a",
    "primaryTextColor": "#ffffff",
    "lineColor": "#2f2f2f",
    "tertiaryColor": "#f6f6f6",
    "background": "#ffffff"
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
</div>
{% endraw %}

<script src="https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.min.js"></script>
<script>
  mermaid.initialize({
    startOnLoad: true,
    theme: 'neutral',
    securityLevel: 'loose',
    themeVariables: {
      fontFamily: 'Courier New, Courier, monospace',
      primaryColor: '#4a4a4a',
      primaryTextColor: '#ffffff',
      lineColor: '#2f2f2f',
      tertiaryColor: '#f6f6f6',
      background: '#ffffff'
    }
  });
</script>

