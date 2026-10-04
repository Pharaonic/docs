---
action:
  label: Follow on GitHub
  href: "{contributor.social.github}"

views: components.contributors

seo:
  title: "{contributor.name} - Contributor | Pharaonic"
  description: "{contributor.name} is the #{contributor.rank} contributor to Pharaonic, with {contributionsText} across {packagesText}. See their work, rank, and how to get in touch."
  keywords: "Pharaonic contributor, {contributor.name}, open source contributor, Laravel packages"
  author: Pharaonic
  images:
    - "{contributor.avatar}"
  openGraph:
    type: profile
    siteName: Pharaonic
  twitter:
    card: summary

schema:
  "@type": ProfilePage
  name: "{contributor.name} - Contributor | Pharaonic"
  description: "{contributor.name} is the #{contributor.rank} contributor to Pharaonic, with {contributionsText} across {packagesText}."
  isPartOf:
    "@id": url:/#website
  mainEntity:
    "@type": Person
    name: "{contributor.name}"
    alternateName: "@{contributor.username}"
    jobTitle: "{contributor.title}"
    image: "{contributor.avatar}"
    url: "{contributor.social.github}"
    sameAs: "{sameAs}"
    worksFor:
      "@type": Organization
      "@id": url:/#organization
---
