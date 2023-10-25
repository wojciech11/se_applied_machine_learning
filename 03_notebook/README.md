# Notebook intro 03

```bash
# create the conda env:
conda create -n teaching_appl_ml_03
conda activate teaching_appl_ml_03
```

Korzystamy channels z [conda-forge](https://anaconda.org/conda-forge/repo) i [fastchan](https://anaconda.org/fastchan):

```bash
# basic libs:
conda install --channel fastchan -y jupyterlab ipywidgets
conda install --channel fastchan -y nbdev
conda install --channel conda-forge -y scikit-learn \
	matplotlib \
	pandas

# examples with fastai
conda install  --channel fastchan --yes fastai
pip install -Uqq fastbook
```

Zainstaluj `quarto` z pomocą instrukcji na [oficjalnej stronie](https://quarto.org/docs/get-started/) lub użyj komendy z `nbdev`:

```bash
nbdev_install_quarto
```

Teraz jesteśmy gotowi do działania:

```bash
jupyter lab
```

Zainstaluj z pomocą Jupyter mgmt, pluginy: `jupyter_quarto`.

## Materiały dodatkowe

- [Tutorial nbenv](https://nbdev.fast.ai/tutorials/tutorial.html).
