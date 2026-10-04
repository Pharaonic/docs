---
# The site header navigation, shared by every page.
#
# Each link is active (highlighted) when the current route matches one of its `active` route names;
# `*` is a wildcard, so `packages.*` covers every page under /packages. Without `active`, a link is
# active only on its own exact URL. Set `hidden: true` to hide a link without deleting it.

home:
  label: Pharaonic
  href: route:home

links:
  - label: Packages
    href: route:packages.index
    active: packages.*
  - label: Contributors
    href: route:contributors.index
    active: contributors.*
  - label: About
    href: route:about
    active: about
  - label: Contact
    href: route:contact
    active: contact

github:
  label: GitHub
  href: https://github.com/pharaonic

# The search button appears once DOCSEARCH_* is set in .env.
search: Search

toggle: Toggle menu
---
