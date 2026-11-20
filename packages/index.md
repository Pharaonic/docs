---
action:
  label: Community
  href: https://github.com/orgs/Pharaonic/discussions
  icon: chat

views: components.packages

breadcrumbs:
  - label: Home
    href: route:home
  - label: Packages

seo:
  title: PHP Packages - Composer Libraries | Pharaonic
  description: "Open-source {stats.technologyList} packages by Pharaonic: focused Composer libraries, tested on every PHP version they support and documented for every line."
  keywords: Pharaonic packages, PHP packages, Laravel packages, Composer libraries
  author: Pharaonic
  images:
    - url:/assets/og-image.jpg
  openGraph:
    type: website
    siteName: Pharaonic
  twitter:
    card: summary_large_image

schema:
  "@type": CollectionPage
  "@id": route:packages.index#webpage
  url: route:packages.index
  name: "{stats.technologyList} Packages"
  isPartOf:
    "@id": url:/#website
  publisher:
    "@id": url:/#organization
---
