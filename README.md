# RESCEU lecture: strong lensing notebooks

Click a button to open a notebook in Google Colab. You need a Google account and nothing else. Then choose **Runtime → Run all**. The instructions at the top of each notebook explain each step.

| Notebook | |
|---|---|
| **Modeling a quadruply imaged quasar**: simulate a quad lens and fit it with lenstronomy | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amn3142/RESCEU_dm/blob/main/modeling_a_quadruply_imaged_quasar_updated.ipynb) |
| **Flux-ratio anomalies from an SIS perturber**: add a small perturber next to one image, fit with a smooth model, and look at the flux-ratio residuals | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amn3142/RESCEU_dm/blob/main/quad_with_sis_perturber.ipynb) |
| **Mock data challenge**: use fold flux ratios of ten mock lenses and pyHalo CDM subhalos to measure the subhalo concentration `c0` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amn3142/RESCEU_dm/blob/main/03_mock_data_challenge.ipynb) |

To run them on your own computer instead:

```
pip install lenstronomy emcee tqdm jupyter
pip install pyhalo==1.4.6 colossus mcfit multiprocess   # for the mock data challenge
jupyter notebook
```
