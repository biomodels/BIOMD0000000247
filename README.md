# BIOMD0000000247: ralser

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000247.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000247.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000247 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the model with _unfitted_ parameters described in the article  
**Dynamic rerouting of the carbohydrate flux is key to counteracting oxidative stress**   
Markus Ralser, Mirjam M Wamelink, Axel Kowald, Birgit Gerisch, Gino Heeren,
Eduard A Struys, Edda Klipp, Cornelis Jakobs, Michael Breitenbach, Hans
Lehrach and Sylvia Krobitsch, _J Biol_ 2007 6(4):10; PMID:
[18154684](http://www.ncbi.nlm.nih.gov/pubmed/18154684) , doi:
[10.1186/jbiol61](http://dx.doi.org/10.1186/jbiol61)  
Abstract:  
BACKGROUND: Eukaryotic cells have evolved various response mechanisms to
counteract the deleterious consequences of oxidative stress. Among these
processes, metabolic alterations seem to play an important role.  
RESULTS: We recently discovered that yeast cells with reduced activity of the
key glycolytic enzyme triosephosphate isomerase exhibit an increased
resistance to the thiol-oxidizing reagent diamide. Here we show that this
phenotype is conserved in Caenorhabditis elegans and that the underlying
mechanism is based on a redirection of the metabolic flux from glycolysis to
the pentose phosphate pathway, altering the redox equilibrium of the
cytoplasmic NADP(H) pool. Remarkably, another key glycolytic enzyme,
glyceraldehyde-3-phosphate dehydrogenase (GAPDH), is known to be inactivated
in response to various oxidant treatments, and we show that this provokes a
similar redirection of the metabolic flux.  
CONCLUSION: The naturally occurring inactivation of GAPDH functions as a
metabolic switch for rerouting the carbohydrate flux to counteract oxidative
stress. As a consequence, altering the homoeostasis of cytoplasmic metabolites
is a fundamental mechanism for balancing the redox state of eukaryotic cells
under stress conditions.

Different realtive enzyme velocities can be simulated by varying the
parameters **k_rel_TPI** and **k_rel_GAPDH** .

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2010 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


