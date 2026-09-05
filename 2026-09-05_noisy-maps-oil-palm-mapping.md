# Noisy Historical Maps to Time-Series Oil Palm Mapping
**Date:** 2026-09-05
**Keyword:** palm oil
**Source:** arXiv
**URL:** https://arxiv.org/abs/2604.23776

## Summary
A deep learning framework generating 10m-resolution oil palm plantation maps for Indonesia and Malaysia (2020-2024) from Sentinel-2 imagery without requiring new manual annotations. Uses U-Net with Determinant-based Mutual Information to handle label noise from coarse 100m historical labels. Achieves 60-70% accuracy and reveals oil palm coverage peaked in 2022 before declining in 2024.

## Idea angle
Annotation-free mapping from noisy historical labels is a breakthrough for scalability — no need for expensive ground truth collection. The 2024 decline in coverage is a signal worth investigating (is it regulatory enforcement, market dynamics, or methodological artifact?). Building a monitoring dashboard on top of these maps for EUDR compliance reporting would be immediately valuable for sustainability teams.

## Details
Authors: Nuttaset Kuapanich, Juepeng Zheng, et al. | Submitted: 26 Apr 2026 | Subject: Computer Vision (cs.CV) | arXiv:2604.23776 | Dataset publicly available at doi.org/10.5281/zenodo.17768444 | Accuracy: 70.64% (2020), 63.53% (2022), 60.06% (2024)

## Tags
#research-idea #palm-oil #arxiv

## Cross-links
- [[2026-08-15_oil-palm-mapping-time-series]] — Same paper — time-series oil palm mapping from noisy historical maps, now found again via arXiv
- [[2026-08-22_oil-palm-timeseries-mapping]] — Same paper again — time-series oil palm mapping without annotation
- [[2026-08-29_oil-palm-timeseries-mapping]] — Same paper — appears across multiple weekly scans
- [[2026-08-29_geoai-oil-palm-benchmark]] — Both use satellite imagery and deep learning for oil palm mapping in Indonesia — this generates maps, the other provides benchmark datasets
- [[2026-09-05_tree-crop-mapping-deforestation]] — Both use Sentinel imagery for tree crop mapping — this for Indonesia/Malaysia palm oil, the other for South America tree crops
