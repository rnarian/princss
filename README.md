# Princss

👸 Princss aims to provide simple print styles to existing projects. Elements such as header, footer, sidebars are simply removed so that only the relevant content is printed.

## Usage:

Make sure to add `media="screen"` to your existing stylesheet. This prevents the screen styles from 'spilling' into the print styles.

Add the following line right below:

```
<link rel="stylesheet" href="path/to/print.css" media="print">
```

Either use the '.unprintable' class to hide elements from print layout, or hide the elements in your styles; e.g.:

```
@media print {
  .site-header,
  .main-nav,
  .footer-nav {
    display: none !important;
  }
}
```
