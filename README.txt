#  Bacterial-EndoV-2023
The file naming is as follows: 

The MD-input directory contains the input files used to prepare the system for running MD simulations and the tleap script used to generate those input files. In the file names, 2w35 refers to the PDB ID of the bacterial EndoV crystal structure from which the starting models for MD were built. "DL" refers to the EndoV model involving direct metal-substrate ligation and "IDL" refers to the model involving indirect metal-substrate ligation.

The MD-snapshots directory contains the MD snapshots that were used to build the QM/MM starting models and file naming describes 'Computational Metholodlogy (Moelcular Dynamics (MD) followed by metal-substrate ligation (direct (DL) or indirect (IDL)), followed by the possible general base (Histidine (H214) or aspartate (D43) or susbstrate phosphate (Phosphate)), which is followed by the possible general acid (MG or Mg-ligated water (MGOW) or lysine (K139)).'

The QM/MM-stationary-points directory contains the QM/MM-optimized structures for each mechanism and the file naming describes 'Metal-substrate ligation (direct (DL) or indirect (IDL)), followed by the general base (Histidine (H214) or aspartate (D43) or susbstrate phosphate (Phosphate)), followed by the general acid (MG or Mg-ligated water (MGOW) or lysine (K139)), which is followed by the nature of the stationary point (reactant complex (RC) or transition state (TS) or intermediate complex (IC) or product complex (PC)). "EE" refers to the stationary points that were optimized using electrostatic embedding.'
