##### ns-fmodes
### constraints on neutron star fundamental-mode oscillation frequencies from astronomical data
philippe landry (pgjlandry@gmail.com) 02/2024

*dynamical tides that excite the internal oscillation modes of a neutron star are an important aspect of the tidal interaction of a compact binary during inspiral. what is the most probable fundamental-mode frequency in the merging neutron star population? how detectable is it with current or future-generation gravitational-wave detectors?*

*this repository contains python scripts for constraining the f-mode frequencies of neutron stars in merging binaries. the constraints enable the most common f-mode frequency in the astrophysical population to be estimated, such that its measurability can be assessed.*

for more, please see Mohanty,Mali,Das+Landry 2024 (in prep)

### Notebooks

*these notebooks offer a demonstration of the analysis and showcase the key results*

... *# ...*

### Data

*the etc/ directory contains the data and utilities needed for the analysis*

... *# ...*


bash batch/CalculateEnrichmentHistory_DAG.sh $(cat batch/CalculateEnrichmentHistory_DAG.in) \
condor_submit_dag calculate_batch/CalculateEnrichmentHistory.dag

bash batch/InferBNSDTD_DAG.sh $(cat batch/InferBNSDTD_DAG.in) \
condor_submit_dag infer_batch/InferBNSDTD.dag \
bash batch/InferBNSDTD_merge.sh
