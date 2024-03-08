# Unveiling Protein Structure: A Convolutional Neural Network Approach to Secondary Structure Prediction

This bioinformatics project delves into the realm of protein structure prediction using Convolutional Neural Networks (CNNs). Proteins are the building blocks of life, and understanding their structure is crucial for unraveling their function and behavior in biological processes. 

**Secondary Structure Prediction:**

This project focuses specifically on predicting the secondary structure of proteins. Secondary structure refers to the local folding patterns of a protein chain, which influences its overall 3D form. Accurately predicting secondary structure can provide valuable insights into protein function and interactions.

**The Power of CNNs:**

CNNs are a powerful type of deep learning architecture particularly adept at processing sequential data like protein sequences. Their ability to learn intricate patterns within sequences makes them well-suited for the task of secondary structure prediction.

**This project utilizes a CNN to:**

* Analyze protein sequences represented by Position-Specific Scoring Matrices (PSSMs). PSSMs capture the evolutionary conservation of amino acids at each position in a protein sequence, providing valuable information for structure prediction.
* Learn the relationship between PSSM data and protein secondary structure.
* Predict the secondary structure (e.g., helix, sheet) of unseen protein sequences.

**Benefits and Potential Applications:**

By successfully predicting protein secondary structure, this project can contribute to:

* Understanding protein function and interactions
* Designing novel drugs by targeting specific protein structures
* Accelerating protein structure determination pipelines

**Project Structure:**

    ├── data                
    │   ├── labels              # Contains the training labels used
    │   ├── pssm_csv            
    │   │   ├── test            # Contains the test data used 
    │   │   └── train           # Contains the training data used
    │   ├── pssm_tensor         # Used to store pytorch tensor files for efficient dataloaders
    │   └── simplified_seq      # Contains simplified sequence data
    ├── images                  # Contains images used in the notebook
    ├── results                 # Contains the predictions made by the model/s
    └── src                     # Contains the main notebook 


