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
  title: "Filament Packages - Plugins for Filament Panels | Pharaonic"
  description: "Filament packages by Pharaonic: plugins, fields, and components for Filament panels, forms, and tables. Documented and {stats.licenses}-licensed."
  keywords: "Filament packages, Filament plugins, Filament admin panel, Laravel admin, Pharaonic"
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
  name: "Filament Packages - Plugins for Filament Panels | Pharaonic"
  isPartOf:
    "@id": url:/#website
  publisher:
    "@id": url:/#organization
---
