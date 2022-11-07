# Physics skills

This repository contains a [Jupyter](https://jupyter.org/) notebook
for investigating a physics-skills problem relating to rolling balls
along a surface, with and without a depression along the way.  Other
notebooks may follow.

Running the notebook Python 3 and the packages:

- [jupyterlab](https://jupyter.org/install)
- [matplotlib](https://matplotlib.org/stable/users/installing/index.html)
- [numpy](https://numpy.org/install/)

One approach for obtaining the software and running the notebook is as follows, where the commands given should be executed from a terminal window:

1. If not already available, install [git](https://git-scm.com/download).
2. If not already avialable, install
[Miniconda](https://docs.conda.io/en/latest/miniconda.html).
3. Clone the `physics-skills` repository:
```
git clone https://github.com/kh296/physics-skills
```
4. Create a `physics-skills` environment:
```
cd physics-skills
conda env create --file environment.yml
```
5. Once created, the environment can be activated with:
```
conda activate physics-skills
```
and can be deactivated with:
```
conda deactivate
```

With the environment activated, the notebook can be started with:
```
jupyter lab notebooks/rolling_balls.ipynb
```
Variables defined in the last cell can be altered to investigate
the effect of changing initial ball velocity, depression length,
depression depth, slope of depression sides
