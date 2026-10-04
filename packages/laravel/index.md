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
  title: "Laravel Packages - Eloquent, Livewire & SaaS Toolkits | Pharaonic"
  description: "Laravel packages by Pharaonic: localization, translatable models, tagging, file attachments, agent detection, and more. Documented and {stats.licenses}-licensed."
  keywords: "Laravel packages, Eloquent traits, Livewire components, Artisan commands, Composer libraries, Pharaonic"
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
  name: "Laravel Packages - Eloquent, Livewire & SaaS Toolkits | Pharaonic"
  isPartOf:
    "@id": url:/#website
  publisher:
    "@id": url:/#organization
---
