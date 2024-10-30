# virusIntegrationViz
This repo includes scripts to visualize the contig at virus integration from SearcHPV 

## Preprocess for visualization
1. `analysis_MCV.ipynb`

    This script contains the preprocess that takes the output files from [SearcHPV](https://github.com/WenjinGudaisy/SearcHPV) to annotate MCPV integrations. The outputs of this script are Supplimentary table 6 and the inputs of `MCV.r`.
2. `geneModel_MCV.ipynb`

    This scripts implemented the preprocess to visualize MCPV integration gene model in Figure 3 (A-B). The output of this scripts are the inputs of `MCV_model.r`.
## Visualization
1. `MCV.r`

    This script conducted the visualization from Figure 3C and Supplimentary Figure 4.
2. `MCV_model.r`

    This script visualized the MCPV integration gene model in Figure 3C to Supplimentary Figure 4.




