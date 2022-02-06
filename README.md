# Gaussian Processes applied to Botnet Detection

This repo explores the use of Gaussian Processes for detecting C&C botnet communication. We use [CTU13](https://www.stratosphereips.org/datasets-ctu13) dataset as a benchmark. I tested a linear-time approximate inference method proposed by AaltoML research group called [kalman-jax](https://github.com/AaltoML/kalman-jax).

The current experiment file is under kalmanjax > notebooks > `botnet-classification.ipynb`


Note: forking the original repo did not work because I could not push the data file used in the experiment (LFS on public forks is [not supported on Github](https://github.com/git-lfs/git-lfs/issues/1449#issuecomment-239831273)).
