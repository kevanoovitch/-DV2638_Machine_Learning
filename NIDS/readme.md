## Flow-Based Network Intrusion Detection Using Random Forests

### Requirements:
- Conda (Miniconda/Miniforge)

### Setup:
1. Create the environment:
   conda env create -f environment.yml
2. Activate it:
   conda activate ml_lab
3. Start Jupyter:
   jupyter lab
4. Open main.ipynb and run all cells

### How to run:
1. Open the Jupyter notebook main.ipynb
2. Ensure the CICIDS2017 cleaned dataset is placed in the same directory
3. Run all cells from top to bottom

The notebook performs:
- Dataset loading and preprocessing
- Label aggregation into three classes
- Train/test split
- Random Forest training
- Hyperparameter study (max_depth)
- Evaluation using Precision, Recall, F1-score
- Feature importance analysis

