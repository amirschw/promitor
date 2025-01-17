---
date: 2022-11-22T12:46:47+02:00
weight: 1
version:
---

#### Scraper

- {{% tag added %}} Provide support for all label scenarios in StatsD & OpenTelemetry metric sink. This includes
dimensions, customer & default labels.
- {{% tag added %}} Provide support for scraping multiple metrics dimensions.
- {{% tag changed %}} Switch to Mariner distroless base images
- {{% tag security %}} Patch for [CVE-2023-29331](https://github.com/advisories/GHSA-555c-2p6r-68mm) (High)
- {{% tag deprecated %}} Support for scraping single metric dimension by using `metrics[x].azureMetricConfiguration.dimension`.

#### Resource Discovery

- {{% tag changed %}} Switch to Mariner distroless base images
- {{% tag security %}} Patch for [CVE-2023-29331](https://github.com/advisories/GHSA-555c-2p6r-68mm) (High)
