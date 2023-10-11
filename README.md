# masters-graduation-research-project-2023

This repository includes the master's thesis/graduation project of my master's - M.Sc. Data Science & Artificial Intelligence - at Université Côte d'Azur, France. It is published in HAL Open Science and you can find it [here.](https://hal.science/hal-04182931)

The dataset in this work is the [Human Connectome dataset](https://wiki.humanconnectome.org/display/PublicData/HCP-YA+Data+Dictionary-+Updated+for+the+1200+Subject+Release#HCPYADataDictionaryUpdatedforthe1200SubjectRelease) where there are 998 patient's and their brain maps represented as connectivity matrices with shape (116, 116). There are 116 brain regions per matrix and the values represent the number of fiber between regions measured in diffusion tensor images(DTI). 

You can find the Jupyter Notebook and project report. 

# Abstract:

Many common neurological and neurodegenerative disorders, such as Alzheimer’s disease, Parkinson's disease, or autism have been linked with anomalous patterns of biological aging of
the brain. Discovering which brain regions are related to specific neurological disorders or cognitive stimuli became an essential field of neuroimaging research. Diffusion Tensor Images (DTI) can be used to reveal the biological underlying patterns behind the aging process, holds an individual's signs for various brain disorders, and
propose new personalized-treatment approaches. In this work, we used the brain network graph representations of 998 patients. The nodes represent the brain regions and the edges are described as interactions between the regions. We trained a Graph Neural Network to predict four brain age classes (22-25, 26-30, 31-35, 36+). To increase the accuracy of the model we propose a topological graph data augmentation method. We used the Mapper algorithm to convert brain graphs into the topological complex where each feature of the complex represents brain activations between regions. Based on our quantitative results, the GNN gained a 0.64 test accuracy using only raw graphs, and 0.776 test accuracy using both raw graphs and topological augmented graphs. Using topological graph representations of the brain helped to reveal the functional connectivity of the brain and increased the model performance.
