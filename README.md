# Provenance analysis notebooks

Here we provide 3 different notebooks that use python code.

The first (0_Bia_BasinIDs_sed) can be used to select the catchments that contribute sediments to the analysed sink. This notebook first used the netCDFs from the goSPL simulation and then separates the catchments that overlap with our sink, and analyses their sediment flux into the sink. The notebook shows ways of separating catchments that can be removed in case they are unrealistic from a scientific perspective.

The second notebook (8_PlotInputsFrom_npz) has been produced to plot the files used in the initial simulation (.npz), which are the mesh files with different parameters, just for a check up.

The last notebook, 9_CalculateSourceDifferences has been developed to plot results from different simulations and compare them. 

All the notebooks provided here have been built collaboratively between Tristan Salles, Claire Mallard and Beatriz Hadler Boggiani (biahadler).
