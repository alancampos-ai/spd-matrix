# Spd matrix

#### Article: <small><strong>Affine-invariant metric selection for positive-definite matrix flows</strong> <a href=""><img src="https://cdn.simpleicons.org/doi/2dd4bf" alt="DOI" height="14" align="absmiddle"></a> <a href=""><img src="https://cdn.simpleicons.org/zenodo/2dd4bf" alt="Zenodo" height="14" align="absmiddle"></a> <a href="https://drive.google.com/drive/folders/1OxSaeTzd3MGd0phLvdyxZ-2oeYxJluA4?usp=drive_link"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" alt="Google Drive" height="14" align="absmiddle"></a></small>

We study exponential distance decay for flows on symmetric positive-definite matrices under congruence-invariant Riemannian metrics. Scale–shape decomposition yields a one-parameter spectral problem with positive-rate intervals, quasiconcavity, conditions for optimizer existence, and perturbation and finite-state error bounds. A constructed flow has a higher rate under a nonstandard metric on a compact, geodesically convex, forward-invariant domain with nonempty interior in $\mathcal P_2$. For covariance Riccati flows, $\tau=1$ is optimal, and an invariant order interval yields a positive rate bound. Spectral rate-level search uses scalar feasibility tests and rational verification. Evaluation covers nine Riccati scenarios and 60 paired instances using eleven methods. Its mean reference discrepancy and runtime are $5.452\times10^{-5}$ and 23.696 ms, versus $6.914\times10^{-11}$ and 6.410 ms for bounded Brent search.

#### Dependencies

Experiments ran on Ubuntu 24.04.5 LTS with Python 3.11.15 and the following dependencies:

* NumPy 1.26.4
* SciPy 1.17.0
* Matplotlib 3.11.0
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
