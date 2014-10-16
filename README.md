# BIOMD0000000334: Bungay2003_Thrombin_Generation

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000334.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000334.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000334 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
** A mathematical model of lipid-mediated thrombin generation **   
Bungay Sharene D., Gentry Patricia A., Gentry Rodney D. _Mathematical Medicine
and Biology_Volume 20, Issue 1, 1 March 2003, Pages 105-29
[12974500](http://www.ncbi.nlm.nih.gov/pubmed/12974500),  
**Abstract:**   
Thrombin is an enzyme that is generated in both vascular and non-vascular
systems. In blood coagulation, a fundamental process in all species, thrombin
induces the formation of a fibrin clot. A dynamical model of thrombin
generation in the presence of lipid surfaces is presented. This model also
includes the self-regulating thrombin feedback reactions, the thrombomodulin-
protein C-protein S inhibitory system, tissue factor pathway inhibitor (TFPI),
and the inhibitor, antithrombin (AT). The dynamics of this complex system were
found to be highly lipid dependent, as would be expected from experimental
studies. Simulations of this model indicate that a threshold lipid level is
required to generate physiologically relevant amounts of thrombin. The
dependence of the onset, the peak levels, and the duration of thrombin
generation on lipid was saturable. The lipid concentration affects the way in
which the inhibitors modulate thrombin production. A novel feature of this
model is the inclusion of the dynamical protein C pathway, initiated by
thrombin feedback. This inhibitory system exerts its effects on the lipid
surface, where its substrates are formed. The maximum impact of TFPI occurs at
intermediate vesicle concentrations. Inhibition by AT is only indirectly
affected by the lipid since AT irreversibly binds only to solution phase
proteins. In a system with normal plasma concentrations of the proteins
involved in thrombin formation, the combination of these three inhibitors is
sufficient both to effectively stop thrombin generation prior to the
exhaustion of its precursor, prothrombin, and to inhibit all thrombin formed.
This model can be used to predict thrombin generation under extreme lipid
conditions that are difficult to implement experimentally and to examine
thrombin generation in non-vascular systems.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


