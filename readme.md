# Hawaiian Paleointensities 

This repository contains three notebooks, "Hawaii_Figures.ipynb", "Make_BiCEP_Figures.ipynb" and "Make_Map_Figure.ipynb".

"Hawaii_Figures.ipynb" contains the code used to produce Figures 1, 4 and 8 in the paper "Changes in non-dipolar field structure over the Plio-Pleistocene: New paleointensity results from Hawai'i compared to global datasets" (Cych et al, in prep). 

"Make_BiCEP_Figures.ipynb" contains the code used to produce Figures 3 and 5 in the paper. These figures require the `BiCEP_GUI` package (Cych et al 2021, http://github.com/bcych/BiCEP_GUI) and will require a separate python environment to run. Make_BiCEP_Figures.ipynb also performs the BiCEP analysis used in the paper in commented out cells.

"Make_Map_Figure.ipynb" contains the code to produce the map in Figure 2- unfortunately the Digital Elevation Models required by this map are too large to include here. Watch this space as we will upload these dems in the correct coordinate system soon. However, the code can still be inspected to understand how such a map figure can be produced in python. To work, this will require the `geopandas` package which we recommending installing to another separate python environment.

### Licensing
PmayPy, BiCEP_GUI and this code are licensed under a BSD 3-clause license, see (https://opensource.org/licenses/BSD-3-Clause)