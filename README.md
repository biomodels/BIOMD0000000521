# BIOMD0000000521: MODEL1402250000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000521.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000521.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000521 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Ribba2012 - Low-grade gliomas, tumour growth inhibition model

Using longitudinal mean tumour diameter (MTD) data, this model describe the
size evolution of low-grade glioma (LGG) in patients treated with chemotherapy
or radiotherapy.

This model is described in the article:

[A tumour growth inhibition model for low-grade glioma treated with
chemotherapy or radiotherapy](http://identifiers.org/pubmed/22761472)

Ribba B, Kaloshi G, Peyre M, Ricard D, Calvez V, Tod M, Cajavec-Bernard B,
Idbaih A, Psimaras D, Dainese L, Pallud J, Cartalat-Carel S, Delattre JY,
Honnorat J, Grenier E, Ducray F.

Clin. Cancer Res. 2012 Sep; 18(18): 5071-5080

Abstract:

PURPOSE: To develop a tumor growth inhibition model for adult diffuse low-
grade gliomas (LGG) able to describe tumor size evolution in patients treated
with chemotherapy or radiotherapy.

EXPERIMENTAL DESIGN: Using longitudinal mean tumor diameter (MTD) data from 21
patients treated with first-line procarbazine,
1-(2-chloroethyl)-3-cyclohexyl-l-nitrosourea, and vincristine (PCV)
chemotherapy, we formulated a model consisting of a system of differential
equations, incorporating tumor-specific and treatment-related parameters that
reflect the response of proliferative and quiescent tumor tissue to treatment.
The model was then applied to the analysis of longitudinal tumor size data in
24 patients treated with first-line temozolomide (TMZ) chemotherapy and in 25
patients treated with first-line radiotherapy.

RESULTS: The model successfully described the MTD dynamics of LGG before,
during, and after PCV chemotherapy. Using the same model structure, we were
also able to successfully describe the MTD dynamics in LGG patients treated
with TMZ chemotherapy or radiotherapy. Tumor-specific parameters were found to
be consistent across the three treatment modalities. The model is robust to
sensitivity analysis, and preliminary results suggest that it can predict
treatment response on the basis of pretreatment tumor size data.

CONCLUSIONS: Using MTD data, we propose a tumor growth inhibition model able
to describe LGG tumor size evolution in patients treated with chemotherapy or
radiotherapy. In the future, this model might be used to predict treatment
efficacy in LGG patients and could constitute a rational tool to conceive more
effective chemotherapy schedules.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000521](http://identifiers.org/biomodels.db/BIOMD0000000521) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


