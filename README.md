# Spd matrix

#### Article: <small><strong>Affine-invariant metric selection for positive-definite matrix flows</strong> <a href=""><img src="https://cdn.simpleicons.org/doi/2dd4bf" alt="DOI" height="14" align="absmiddle"></a> <a href=""><img src="https://cdn.simpleicons.org/zenodo/2dd4bf" alt="Zenodo" height="14" align="absmiddle"></a> <a href="https://drive.google.com/drive/folders/1OxSaeTzd3MGd0phLvdyxZ-2oeYxJluA4?usp=drive_link"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" alt="Google Drive" height="14" align="absmiddle"></a></small>

We study exponential distance decay for flows on symmetric positive-definite matrices under congruence-invariant metrics. Scale–shape decomposition reduces metric selection to a one-parameter spectral problem. We characterize positive-rate intervals, establish quasiconcavity and optimizer existence under stated conditions, and derive perturbation and finite-state error bounds. On the constructed invariant flat, $\tau=2$ yields rate 3, a 20% improvement over the standard metric. For covariance Riccati flows, $\tau=1$ is optimal. A logarithmic grid provides a deterministic objective-gap bound. Evaluation covers nine Riccati scenarios and 20 paired synthetic instances with eleven methods. The grid's mean rate error and runtime are $3.133\times10^{-4}$ and 227.021 ms, versus $2.665\times10^{-16}$ and 18.918 ms for bounded Brent search. The accuracy difference is significant after Holm correction ($p=1.91\times10^{-5}$).

#### Dependencies

The experiments used Ubuntu 26.04.1 LTS and Python 3.12.7 with the following dependencies:

* NumPy 2.3.5
* SciPy 1.17.0
* Matplotlib 3.10.8
* psutil 7.2.2
* PyYAML 6.0.3

#### Installation

```bash
docker build --pull -f docker/Dockerfile -t affine-metric-selection:main .
docker run --rm affine-metric-selection:main
```

#### License (MIT)

* Copyright (c) alancampos-ai
* Code released under the MIT License.
