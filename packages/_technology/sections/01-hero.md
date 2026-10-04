---
view: components.packages.hero
badge: "Open Source, {stats.licenses} Licensed"
title: "{technology.name}"
highlight: Packages
buttons:
  - label: "Browse {technology.name} Packages"
    href: "#catalog"
    style: primary
    icon: arrow-down
  - label: Full Catalog
    href: route:packages.index
    style: ghost
    icon: arrow-right
tiles:
  - key: packages
    label: Packages
  - key: downloads
    label: Downloads
  - key: stars
    label: GitHub stars
  - value: "{stats.licenses}"
    label: Free & open source
---

{technology.description}
