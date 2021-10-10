## Breakpoints

Import this file and build **responsive structure** easily.

* 576px for phones.
* 768px for tablets.
* 992px for laptops.
* 1200px for desktop.

```scss
$xs: 576px; // portrait phones
$sm: 768px; // tablets
$md: 992px; // laptops
$lg: 1200px; // desktops

@mixin tablet {
  @media (min-width: $sm) {
    @content;
  }
}

@mixin laptop {
  @media (min-width: $md) {
    @content;
  }
}

@mixin desktop {
  @media (min-width: $lg) {
    @content;
  }
}```
