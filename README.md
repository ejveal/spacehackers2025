# SpaceHackers 

This is a public repo for testing resources related to accessing NASA data.

To install minimal dependencies:

1. Clone project into local workstation
```
git clone https://...
```
2. Navigate to cloned repo and activate mamba/conda environment.
```
cd spacehackers
mamba activate
```
NOTE: You need to have [miniforge](https://conda-forge.org/download/) installed and your shell (zsh/bash) configured correctly, so that afterwards if you do on your shell

```
which python
```
of (if not aliased)
```
which python3
```
if should display `$prefix/miniforge3/bin/python`. You can install miniforge from official website, or homebrew for OSX. 

3. Once your conda/mamba environment is activate, create the space_hackers environment by running on terminal
```
mamba env create -f environment.yml
```
4. Initialize the environment and run jupyter lab

```
mamba activate space_hackers
jupyter lab
```
