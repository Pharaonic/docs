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
  title: "PHP Packages - Framework-Agnostic Composer Libraries | Pharaonic"
  description: "Framework-agnostic PHP packages by Pharaonic. Work in any Composer project: Laravel, Symfony, Slim, or plain PHP. {stats.licenses}-licensed."
  keywords: "PHP packages, framework-agnostic PHP, Composer libraries, Pharaonic"
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
  name: "PHP Packages - Framework-Agnostic Composer Libraries | Pharaonic"
  isPartOf:
    "@id": url:/#website
  publisher:
    "@id": url:/#organization
---
