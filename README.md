# BI work sample

A Power BI work sample on illustrative minerals and metals data, with the
interactive report mock-up it was built from.

All figures are illustrative. None is real platform or market data.

## What's here

- **Approach note (interactive):** open the site link at the top right of this page
- **Report mock-up:** the same site, at `/mockup.html`. The mock-up comes first, so
  stakeholders can explore and agree the look and feel while the Power BI model
  behind it is built.
- **Power BI report:** download `work_sample.pbix` from the Releases section and
  open it in Power BI Desktop

## How the Power BI model is built

- Star schema with Bronze, Silver and Gold Power Query layers
- DAX measures, each entered in a measure basis register (stage, unit, scope,
  period, source, status)
- Row-level security roles
- A migration assurance page comparing a rebuilt result with its reference, row by row

## Versions

The release tagged `submitted` is the version that accompanied a proposal on
20 September 2026. Later work is on the main branch.

Liz Barnes, Special Dimension, Amsterdam
