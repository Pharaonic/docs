---
view: components.packages.features
title: How Every Package Is Built
subtitle: The same checks run on every package and every line. You can see them in each repository's GitHub Actions.
items:
  - icon: check
    title: Tested on Every Supported PHP
    text: Each change runs the test suite in GitHub Actions on every PHP version the line supports, with the lowest and highest dependencies.
  - icon: automation
    title: Static Analysis and Style
    text: PHPStan and Pint run alongside the tests on every change.
  - icon: shield-check
    title: Dependencies Kept Current
    text: Dependabot proposes Composer and GitHub Actions updates every week.
  - icon: book
    title: Docs for Every Line
    text: Each maintained line has its own documentation, and each package page lists what every line requires.
---
