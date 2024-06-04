
This ELLIS Symposium is organized by [ELLIS Health](https://ellis.eu/programs/ellis-health) and [ELLIS ML4Molecules](https://ellis.eu/programs/machine-learning-for-molecule-discovery).

## Participate
Date: Tuesday, June 4, 2024  
Time: 13:00 - 16:00 CEST  
Place: via Zoom (to request meeting details, please send an email to ml4molecules@ml.jku.at)  

## Program

### 13:00 Keynote by Prof. Francesca Grisoni
Eindhoven University of Technology, Dept. Biomedical Engineering,  
Institute for Complex Molecular Systems and Eindhoven AI Systems Institute, Eindhoven, Netherlands  
Centre for Living Technologies, Alliance TU/e, WUR, UU, UMC Utrecht, Netherlands.

**Harnessing deep learning for low-data drug discovery: lessons learned and opportunities**  
Deep learning has had an incredible impact in various fields of science and technology, such as protein structure prediction and organic reaction planning. However, it is known to be particularly effective when large-scale datasets are available. Drug discovery, on the other hand, is usually a low-data endeavour – which limits the potential of ‘out-of-the-box’ deep learning approaches. This talk will reflect on lessons learned in applying deep learning to low-data drug discovery and highlight some successful strategies to address these challenges and discover bioactive molecules.
				
### 14:00 Talk by Johannes Schimunek
ELLIS Unit Linz and LIT AI Lab, Institute for Machine Learning,  
Johannes Kepler University Linz, Austria 


**Machine Learning-guided directed protein evolution**  
Efficient protein engineering and optimization is essential for development of novel biotechnologies. Obtaining a protein with desired properties implies finding a solution to an optimization problem of large dimensionality. The current state-of-the-art technique for optimization of biological sequences is Directed Evolution (DE). It involves multiple rounds of selection and optionally diversification steps. This procedure imitates the process of natural selection akin to evolutionary algorithms to iteratively refine the desired properties of the sequences in the pool. Recently, machine learning methods have been proposed that intend to augment and speed up this process. These methods attempt to utilize the prior knowledge, usually coming from earlier DE rounds, to suggest the best sequences for further testing. Usually, such setups consist of a) a generative method that suggests new sequences and b) one or multiple scoring functions that assess the activity of the proteins (usually by means of predicting the performance of the sequence in prior selection rounds). We evaluated various such methods in a practical setting, e.g. regression approaches, MBE, and a discretized regression (“robust regression”). We have evaluated these approaches with respect to the AUC and ΔAUC-PR metrics during the optimization of a specific protein of interest. Additionally, we evaluate the benefits of the epistemic uncertainty estimates from the scoring functions, as it is a key element in many efficient exploration techniques. We found that robust regression performs best with noisy and irregularly distributed real world sequencing data from a DE experiment.
For this kind of data, regression models succumbed to noise and outliers and were found to be unsuitable. We show benefits of alternating between in-vitro DE rounds and in-silico ML-DE rounds to speed up the optimization process and improve the resulting sequences.


### 14:20 Coffee break

### 14:40 Talk by Dr. Carlos Oliver
Department of Machine Learning and Systems Biology  
Max Planck Institute of Biochemistry Martinsried, Germany  

**Building datasets and benchmarks for deep learning on protein structures with ProteinShake**  
We present ProteinShake, a Python software package that simplifies dataset creation and model evaluation for deep learning on protein structures. Users can create custom datasets or load an extensive set of pre-processed datasets from biological data repositories such as the Protein Data Bank (PDB) and AlphaFoldDB.
Each dataset is associated with prediction tasks and evaluation functions covering a broad array of biological challenges. A benchmark on these tasks shows that pretraining almost always improves performance, the optimal data modality (graphs, voxel grids, or point clouds) is task-dependent, and models struggle to generalize to new structures. ProteinShake makes protein structure data easily accessible and comparison among models straightforward, providing challenging benchmark settings with real-world implications.


### 15:00 Keynote by Prof. Bruno Correia
Laboratory of Protein Design and Immunoengineering
Ecole Polytechnique Federale de Lausanne (EPFL)


**Exploring novel (bio)molecular spaces by design – a dialogue between representation and generation**
The machine learning tool box has revolutionized our ability to design novel molecular entities (e.g. proteins) well beyond what the natural repertoire has explored. Despite the incredible advances, the de novo generation of functional molecules in biological concepts remains an incredible challenge. In this talk I will present some of the efforts in our group in designing both proteins and small molecules. Particularly emphasizing different modalities of molecular representation and the interplay with generative ML to facilitate the exploration of unimaginably large spaces of possibilities. Importantly, many ML-based approaches for molecular design fall short in terms of generalization and sampling off the learned distribution, I will present some ideas on how representation can help to overcome some of these limitations. Finally, I will present some of the approaches developed in our group to embed function into the designer proteins and how we are suing these components in cellular systems to control the output of these complex biological devices.    

## Program committee
Karsten Borgwardt and Günter Klambauer  
