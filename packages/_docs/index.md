---
action:
  label: Star on GitHub
  href: "{package.githubUrl}"

breadcrumbs:
  - label: Home
    href: route:home
  - label: Packages
    href: route:packages.index
  - label: "{technology.name} Packages"
    href: "url:/packages/{technology.slug}"
  - label: "{package.name}"
    href: "{package.url}"
  - label: "{versionLabel}"

labels:
  latest: Latest
  latestGroup: Latest
  previousGroup: Previous Versions
  overview: ← Overview
  technology: "← Back to {technology.name}"
  home: ← Back to Home
  backHome: Back to Home
  viewOnGithub: View on GitHub
  quickActions: Quick Actions
  packagist: View on Packagist
  star: Star on GitHub
  issue: Report Issue
  changelog: Changelog
  stats: Package Stats
  downloads: Total Downloads
  stars: GitHub Stars
  published: First Released
  toggleNav: Toggle docs navigation
  promoTitle: Boost Your Application
  promoText: Discover more powerful packages from Pharaonic
  promoLink: Explore Packages

contributors:
  title: Contributors
  subtitle: Amazing people who made this package possible
  text: "This package wouldn't exist without the contributions of our amazing community. A huge thank you to everyone who has helped improve {package.name}!"
  # all: View All Contributors on GitHub
  contributions: "{count} contributions"
  contribution: "{count} contribution"
  ctaTitle: Want to Contribute?
  ctaText: "We welcome contributions from everyone! Whether it's bug fixes, new features, or documentation improvements - every contribution counts."
  fork: Fork on GitHub
  team: Meet the Team

seo:
  title: "{package.name} Documentation ({versionLabel}) | Pharaonic"
  description:
    - "{package.name} {versionLabel} documentation: {card.description}"
    - "{card.description}"
  keywords: "{package.name} documentation, {package.composer}, {technology.name} package docs, Pharaonic"
  author: Pharaonic
  images:
    - "{package.cover}"
  openGraph:
    type: article
    siteName: Pharaonic
  twitter:
    card: summary_large_image

schema:
  "@type": TechArticle
  headline: "{package.name} Documentation ({versionLabel})"
  image: "{package.cover}"
  description: "{package.name} {versionLabel} documentation: {card.description}"
  version: "{version}"
  dateModified: "{package.updatedAt}"
  inLanguage: en
  isPartOf:
    "@id": url:/#website
  author:
    "@id": url:/#organization
  publisher:
    "@id": url:/#organization
  about:
    "@type": SoftwareSourceCode
    "@id": "{package.url}#software-source-code"
    name: "{package.name}"
    url: "{package.url}"
    codeRepository: "{package.githubUrl}"
    programmingLanguage: PHP
    license: "https://opensource.org/licenses/{package.license}"
---
