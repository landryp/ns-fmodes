Astrophysical constraints on neutron star f-modes with a nonparametric equation of state representation: Neutron star equation of state posterior samples
Sailesh Ranjan Mohanty, Utkarsh Mali, H.C. Das, Bharat Kumar, and Philippe Landry; doi:10.5281/zenodo.13952437

This data release contains equation of state posterior samples associated with Sailesh et al., "Astrophysical constraints on neutron star f-modes with a nonparametric equation of state representation," 

Three sets of around 1e4 samples from the posterior distribution over equations of state are provided. These sets are drawn from the posterior conditioned on different combinations of radio pulsar observations, gravitational wave data, and NICER x-ray measurements. The data release contains the equation of state table and the corresponding table of neutron star observables for each sample. 

***

Contents:

EoS_posterior_samples_PSR.h5
EoS_posterior_samples_PSR+GW.h5
EoS_posterior_samples_PSR+GW+NICER.h5

Each file in the data release is an hdf5 container with three groups: "id", "eos", and "ns". The "id" group associates the equation of state label (e.g. "eos_0") to a unique identifier for book-keeping purposes across hdf5 files. The "eos" group contains the equation of state tables, indexed by equation of state label. The tables have columns of pressure/c^2 (g/cm^3), energy density/c^2 (g/cm^3) and baryon density (g/cm^3). The "ns" group contains the table of neutron star observables for the Tolman-Oppenheimer-Volkov sequence that corresponds to each equation of state. The tables are indexed by equation of state label and have columns of central baryon density (g/cm^3), mass (Msun), radius (km), dimensionless tidal deformability, and quadrapolar f-mode frequency (kHz).

The equation of state samples in LCEHL_EOS_posterior_samples_PSR.h5 are drawn from the posterior distribution conditioned on the Fonseca et al. [Astrophys. J. Lett. 915, L12 (2021)] mass measurement for PSR J0740+6620 and the Antoniadis et al. [Science 340, 1233232 (2013)] mass measurement for PSR J0348+0432. Those in LCEHL_EOS_posterior_samples_PSR+GW.h5 are additionally conditioned on the  Abbott et al. [Phys. Rev. X 9, 011001 (2019)] mass and tidal deformability measurements for GW170817 and the Abbott et al. [Astrophys. J. Lett. 892, L3 (2020)] mass and tidal deformability measurements for GW190425. Those in LCEHL_EOS_posterior_samples_PSR+GW+NICER.h5 are conditioned on the gravitational wave observations, the PSR J0348+0432 mass measurement, the Miller et al. [Astrophys. J. Lett. 887, L24 (2019)] mass and radius measurements for PSR J0030+0451, and the Miller et al. [Astrophys. J. Lett. 918, L28 (2021)] mass and radius measurements for PSR J0740+6620.

