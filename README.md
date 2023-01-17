Coiled Hands-On
===============

This repository contains Coiled/Dask examples that are both easy and
non-trivial.  They are intended for quick demonstrations when first trying out
the product.

Instructions
------------

Clone repository

```
git clone https://github.com/mrocklin/coiled-hands-on
cd coiled-hands-on
```

Install software

```bash
conda env create -f environment.yml -y
conda activate hands-on
```

Log in to Coiled

```bash
coiled login
```

If you're working within the context of a Coiled team account (common for
demonstrations) you may want to specify a default account:

```bash
coiled login --account PROVIDED_ACCOUNT
```

Open up Jupyter and play around

```bash
jupyter lab
```
