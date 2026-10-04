---
view: components.packages.package-hero
badges:
  - label: "{technology.name} Package"
    color: blue
  - label: "{package.license} License"
    color: purple
  - label: "{package.downloadsShort} downloads"
    color: blue
title: "{package.name}"
highlight: "for {technology.name}"
buttons:
  - label: View Full Documentation
    href: "{card.docsUrl}"
    style: primary
    icon: arrow-right
  - label: View on GitHub
    href: "{package.githubUrl}"
    style: ghost
    external: true
install: "{card.install}"
labels:
  copy: Copy
  copied: Copied!
---

{card.description}
