### Project Introduction
    This project was established for High-throughput screening of AIE-MFC molecules.
 
### Description of the directory structure
    ├── ReadMe.md // Help Documentation.
    
    ├── code // AIE and MFC property prediction model training and high-throughput screening codes.
    
    ├── model // Saved property prediction models.
    
    ├── result // The folder where the nature prediction results are stored.
    
### Directions for use
   All executable files are located in the code directory. The workflow proceeds as follows: First, execute fingerprint.py and descriptors.py to generate supplementary molecular descriptors. Subsequently, run train_model_AIE.py and train_model_mfc.py to establish optimal predictive models for AIE and MFC properties respectively. Following model training, execute combine_molecule.py to construct the composite molecular screening library. Finally, initiate filtering_process.py to perform multi-criteria molecular filtration and obtain refined candidate molecules.
 
