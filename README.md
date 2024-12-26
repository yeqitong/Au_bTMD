
# Introduction  

## System Requirements  
The code in this project was developed and tested using Python 3.9.19. The main packages and their versions are as follows:  
- `matplotlib` 3.4.3  
- `numpy` 1.26.4  
- `pandas` 2.0.3  
- `scikit-learn` 1.4.2  
- `shap` 0.42.0  

---

## How to Use  
1. Create a virtual environment (e.g., named `autmd`) with Python (3.9.19) using your favourite environment manager (such as conda):  
   ```bash
   conda create -n autmd python=3.9.19
2. Activate the environment:  
   ```bash
   conda activate autmd
3. Install the required packages with the specified versions using pip:  
   ```bash
   pip install matplotlib==3.4.3 numpy==1.26.4 pandas==2.0.3 scikit-learn==1.4.2 shap==0.42.0
4. Run Jupyter Notebook: 
   ```bash
   jupyter notebook

---

## Dataset Description
We provide the datasets used in the article. The file Au-TMD_dat.csv contains all samples and their features. After removing null values and filtering features (details can be found in the manuscript), the datasets used to train the RFR model are as follows:
- `Model_T_train_test.csv` Contains GH values and descriptors for all sites.
- `Model_F_train_test.csv` Includes samples with GH > 0.5 eV.
- `Model_N_train_test.csv` Includes samples with GH < 0.5 eV.

---

## License
This project is covered under the Apache 2.0 License.
