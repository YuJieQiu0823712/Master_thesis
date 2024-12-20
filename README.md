# Master Thesis

Advanced Feature Extraction Methods for Image-based Profiling of Individual Bacterial Cells

Spatial-temporal organization of cellular processes plays an important role in the survival and propagation of bacterial cells. Examining the intracellular architecture and organization of cells can provide insight into cell cycle events, cellular health, changes in processes in a mutant compared to its wild type, and the impact of drugs or other stresses on the cell. A promising strategy for investigating subcellular morphology is image-based profiling, which extracts biological information from microscopy images into a comprehensive set of features.

![alt text](Workflow_of_image-based_profiling.png)
*The typical workflow of image-based profiling is started from image acquisition.*
*Identify cells in an image by using segmentation and manipulate curation to get good-quality segmentation masks.*
*With the mask and contour, we can extract various features based on morphology or fluorescence intensity.*
*After the data preprocessing and data analysis, we can know which features are different between the control and the test group. Subsequently, we can apply downstream analysis and interpretation.*

This work aims to address the deficiency of bacterium-specific features by designing and implementing features related to nucleoid morphology and membrane intensity. Novel nucleoid features include compactness, sinuosity, convexity, and bending energy, providing intricate insights their overall shape. For the membrane, Haralick texture features as well as a method to generate membrane demographs has been developed. These membrane features explore the intensity distribution of the membrane signal and the variation in fluorescence patterns with increasing cell length.


June 2024
