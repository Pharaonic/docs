---
action:
  label: All Packages
  href: route:packages.index

views: components.packages

breadcrumbs:
  - label: Home
    href: route:home
  - label: Packages
    href: route:packages.index
  - label: "{technology.name} Packages"

seo:
  title: "{technology.name} Packages | Pharaonic"
  description: "Free, open-source {technology.name} packages by Pharaonic: {packageNames}. Documented, {stats.licenses}-licensed, and installed with one Composer command."
  keywords: "{technology.name} packages, Composer libraries, Pharaonic"
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
  name: "{technology.name} Packages | Pharaonic"
  isPartOf:
    "@id": url:/#website
  publisher:
    "@id": url:/#organization
---
