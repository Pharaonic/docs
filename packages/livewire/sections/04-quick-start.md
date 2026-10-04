---
view: components.packages.quick-start
title: Install in Seconds
subtitle: Require the package, publish its assets if needed, and use it in your components.
label: Terminal
code: |
  # 1. Install the package
  composer require pharaonic/livewire-select2

  # 2. (Optional) publish config and assets, then pick the package
  php artisan vendor:publish

  # 3. Service provider is auto-discovered, nothing else to register
---
