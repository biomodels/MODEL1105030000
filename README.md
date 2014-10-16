# MODEL1105030000: MODEL1105030000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1105030000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1105030000.git@20140916`

## Usage

Importing the model package.

`import MODEL1105030000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Zhuang2011 - Ecoli FBA with membrane economics

Genome-scale metabolic model of Escherichia coli able to simulate respiro-
fermentation.

This model is described in the article:

[Economics of membrane occupancy and respiro-
fermentation.](http://identifiers.org/pubmed/21694717)

Zhuang K, Vemuri GN, Mahadevan R

Molecular Systems Biology. 2011; 7:500

Abstract:

The simultaneous utilization of efficient respiration and inefficient
fermentation even in the presence of abundant oxygen is a puzzling phenomenon
commonly observed in bacteria, yeasts, and cancer cells. Despite extensive
research, the biochemical basis for this phenomenon remains obscure. We
hypothesize that the outcome of a competition for membrane space between
glucose transporters and respiratory chain (which we refer to as economics of
membrane occupancy) proteins influences respiration and fermentation. By
incorporating a sole constraint based on this concept in the genome-scale
metabolic model of Escherichia coli, we were able to simulate respiro-
fermentation. Further analysis of the impact of this constraint revealed
differential utilization of the cytochromes and faster glucose uptake under
anaerobic conditions than under aerobic conditions. Based on these
simulations, we propose that bacterial cells manage the composition of their
cytoplasmic membrane to maintain optimal ATP production by switching between
oxidative and substrate-level phosphorylation. These results suggest that the
membrane occupancy constraint may be a fundamental governing constraint of
cellular metabolism and physiology, and establishes a direct link between cell
morphology and physiology.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1105030000](http://identifiers.org/biomodels.db/MODEL1105030000) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


