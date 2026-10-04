---
view: components.packages.quick-start
title: Install in Seconds
subtitle: Require the package, register it on your panel, and you are done.
label: Terminal
code: |
  # 1. Install the package
  composer require pharaonic/filament-<package>

  # 2. (Optional) publish config and migrations, then pick the package
  php artisan vendor:publish

  # 3. Register the plugin in your panel provider (see the package's docs)
---
