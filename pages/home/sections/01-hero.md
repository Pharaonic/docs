---
badge: Open source. Built for developers.
title: Rooted in History
highlight: Engineering the Future
buttons:
  - label: Explore Packages
    href: route:packages.index
    style: primary
    icon: arrow-right
  - label: Contribute
    href: route:contributors.index
    style: ghost
    iconBefore: code
    accent: true
install:
  prefix: "composer require "
  # The most downloaded packages from the DB, rotated every few seconds; the first one is shown on load.
  packages: "{install}"
  copy: Copy
  copied: Copied!
meta:
  - "{stats.packages} packages"
  - "{stats.licenses} licensed"
  - 100% open source
---

Focused packages for {stats.technologyList} developers. Each one solves one common problem (slugs, translations, uploads, Hijri dates, settings) and is documented for every supported version.
