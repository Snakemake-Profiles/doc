# The Snakemake-Profiles project

The Snakemake-profiles project is an effort to create [configuration profiles](https://snakemake.readthedocs.io/en/stable/executing/cli.html#profiles) for executing Snakemake in various computing environments (cluster systems like Slurm, SGE, Grid middleware, cloud computing). Snakemake-profiles has just started, and we need your help to support more computing environments.


## Profiles

In the following, you find a list of available profiles.

| Profile  | Authors |
| -------- |-------- |
| [surfsara-grid](https://github.com/snakemake-profiles/surfsara-grid) | @johanneskoester |
| [pbs-torque](https://github.com/snakemake-profiles/pbs-torque) | @neilav |
| [slurm](https://github.com/Snakemake-Profiles/slurm) | @percyfal |
| [lsf](https://github.com/Snakemake-Profiles/snakemake-lsf) | @mbhall88 |
| [generic](https://github.com/Snakemake-Profiles/generic) | @SilasK |
| [htcondor](https://github.com/Snakemake-Profiles/htcondor) | @jheuel |



## Documentation

### Contribute

Contributing is easy:

1. Create a new repository for your profile with your github account.
2. Ensure that your profile follows our guidelines.
3. Request a inclusion of your profile by [creating a new issue](https://github.com/Snakemake-Profiles/doc/issues/new). After successful review, we will fork your repository into this organization. This makes it easily discoverable by others, while you can still modify it via pull requests.

### Guidelines

1. A profile repository shall consist of one Snakemake profile.
2. The structure of the profile should follow the [surfsara-grid profile](https://github.com/snakemake-profiles/surfsara-grid).
3. The profile has to be installabile via cookiecutter.
4. The readme of the profile has to provide installation instructions.
