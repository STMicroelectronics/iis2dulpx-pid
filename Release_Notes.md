---
pagetitle: Release Notes for IIS2DULPX Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for IIS2DULPX Component Driver
Copyright &copy; 2022 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the IIS2DULPX component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 12-Feb-2025</label>
<div>

## Main changes

### First release

- First official release [ref. DS v1.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V1.0.1 / 07-Apr-2025</label>
<div>

## Main changes

- fix drdy event clearing
- fix RESET case in init_set()

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V1.0.2 / 16-Apr-2025</label>
<div>

## Main changes

- Fix fifo_mode_set

##

</div>

<input type="checkbox" id="collapse-section4" checked aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V1.1.0 / 07-Jul-2025</label>
<div>

## Main changes

- Fix driver formatting options
- Added pointer to private data in stmdev_ctx_t
- Remove unused status parameter
- Removed useless reg write in emb_fsm_en_get
- Fix inact_odr_t enum variants

##

</div>
:::




:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on IIS2DULPX,
visit:
[IIS2DULPX](https://www.st.com/resource/en/datasheet/iis2dulpx.pdf)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
