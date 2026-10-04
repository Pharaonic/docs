---
view: components.packages.quick-start
title: Install in Seconds
subtitle: Require the package, publish its config if needed, and you are done.
label: Terminal
code: |
  # 1. Install the package
  composer require pharaonic/laravel-localization

  # 2. (Optional) publish config and migrations, then pick the package
  php artisan vendor:publish

  # 3. Service provider is auto-discovered, nothing else to register
---
