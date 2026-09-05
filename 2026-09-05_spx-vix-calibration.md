# Global Multi-Maturity SPX-VIX Calibration
**Date:** 2026-09-05
**Keyword:** finance
**Source:** arXiv
**URL:** https://arxiv.org/abs/2609.04087

## Summary
A framework for joint S&P 500 (SPX)-VIX smile calibration across multiple maturities without the conditional-independence restriction of Markovian stitching. Introduces an augmented-Bregman mirror-descent scheme that preserves fit to observable quote moments while controlling martingale and dispersion residuals.

## Idea angle
VIX-SPX joint calibration is the gold standard for volatility modeling. The non-Markovian approach here could power better multi-period derivative pricing engines. Building an open-source implementation of this calibration scheme would fill a gap — most existing tools use the simpler Markovian stitching this paper improves upon.

## Details
Authors: Atithi Acharya, Yue Sun, Brandon Augustino, et al. | Submitted: 3 Sep 2026 | Subject: Computational Finance (q-fin.CP) | arXiv:2609.04087

## Tags
#research-idea #finance #arxiv

## Cross-links
- [[2026-08-16_regime-gated-volatility]] — Both address volatility modeling — this paper calibrates SPX-VIX smiles, the other gates volatility by regime
- [[2026-08-29_m3-market-microstructure]] — Both model market microstructure dynamics — VIX calibration and state-event generative models
