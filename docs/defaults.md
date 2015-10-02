---
layout: default
---

I prefer to adjust settings listed below per each project. List of all
variables is available under `sass/_defaults.sass`.

```sass
$color-ui: $color-silver
$color-btn: $color-black
$color-box: $color-silver
$color-font: $color-black
$color-link: $color-blue
$color-muted: $color-gray

$font-leading: 1.4
$font-size-micro: 11
$font-size-small: 13
$font-size-base: 15
$font-size-lead: 18

$font-family-base: sans-serif
$font-family-headings: $font-family-base
$font-family-monospace: monospace

$grid-container: 1020px
$grid-gutter: $spacing-unit

$responsive-type: mobile-first
$responsive-map: (tablet: 768px 1200px, desktop: 1201px)

$global-extras: true
$global-border-radius: 4px

$link-underline: true
$link-active: true
$link-menu-color: $color-white
$link-menu-background: $color-link

$navbar-background: $color-black
$navbar-color: $color-white
$navbar-link-color: $color-white
$navbar-link-background: rgba($color-white, .15)

$sticky-footer-height: triple($spacing-unit)
```

### Colors

<div class="grid">
  <div class="grid-item 1/6"><div class="color-block color-block-aqua">$color-aqua</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-blue">$color-blue</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-navy">$color-navy</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-teal">$color-teal</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-green">$color-green</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-olive">$color-olive</div></div>

  <div class="grid-item 1/6"><div class="color-block color-block-lime">$color-lime</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-yellow">$color-yellow</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-orange">$color-orange</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-red">$color-red</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-fuchsia">$color-fuchsia</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-purple">$color-purple</div></div>

  <div class="grid-item 1/6"><div class="color-block color-block-maroon">$color-maroon</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-white">$color-white</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-silver">$color-silver</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-gray">$color-gray</div></div>
  <div class="grid-item 1/6"><div class="color-block color-block-black">$color-black</div></div>
</div>

### Size functions

Size functions return a quotient/product of the provided value.

```sass
div
  padding: quarter(12px) // padding: 3px

div
  padding: third(12px) // padding: 4px

div
  padding: halve(12px) // padding: 6px

div
  padding: double(12px) // padding: 24px

div
  padding: triple(12px) // padding: 36px

div
  padding: quadruple(12px) // padding: 48px
```