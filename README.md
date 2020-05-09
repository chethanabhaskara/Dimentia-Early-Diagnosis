# Early diagnosis of Alzheimer’s and Dementia

**Authors:** Anisha Jagadeesh Prasad (ajagadee@usc.edu), Chethana Bhaskara (cbhaskar@usc.edu), Gyanesh Mittal (gyaneshm@usc.edu), Karishma Chadha (karishmc@usc.edu)

#### Directory Organization: 

The dataset used in our project are contained in two csv files - 
1. **oasis_cross-sectional.csv** - Data from Cross sectional MRI scans 
2. **oasis_longitudinal.csv** - Data from Longitudinal MRI scans 

The code repository contains analytics and machine learning algorithms developed using Colab notebooks viz 
1. **cross_sectional_model.ipynb** - Machine learning classifiers modeled using Cross Sectional MRI scans 
2. **longitudinal_data_algorithms.ipynb** - Machine learning classifiers modeled using Longitudinal MRI Scans
3. **DNN_tensorflow.ipynb** - A Deep Neural network modeled using both the datasets combined. 

#### Running instructions:

There are 2 ways to run the above mentioned python notebook:

1. On cloud using Google Colab

   - Each of the files are independently running files and run using the link to their Google Colab page
   - The link can be found at the beginning of the ipynb file in the GitHub repository: https://github.com/chethanabhaskara/Early-diagonsis-of-Alzheimer-s-disease
   - **Note:** In order to run the files, on Colab, please sign into your **USC account**

2. Run locally

   - Requirements:

     - python 3.7
     - numpy
     - pandas
     - seaborn
     - matplotlin
     - Skit-learn
     - graphviz
     - tensorflow
     - jupyter

   - To install run in the following command in the directory:

     ```shell
     pip install -r requirements.txt
     ```

   - Also, to run graphiz run following command on mac:

     ```shell
     brew install graphviz
     ```

     - For other OS, please follow the instructions in this link: https://www.graphviz.org/download/

   - Run the jupyter server in the directory

     ```shell
     jupyter notebook
     ```

#### Dataset Acknowledgements
Data were provided [in part] by OASIS Brains Project available on kaggle.com  

OASIS: Cross-Sectional: Principal Investigators: D. Marcus, R, Buckner, J, Csernansky J. Morris; P50 AG05681, P01 AG03991, P01 AG026276, R01 AG021910, P20 MH071616, U24 RR021382 

OASIS: Longitudinal: Principal Investigators: D. Marcus, R, Buckner, J. Csernansky, J. Morris; P50 AG05681, P01 AG03991, P01 AG026276, R01 AG021910, P20 MH071616, U24 RR021382 

#### References 
[1] OASIS: Cross-Sectional: https://doi.org/10.1162/jocn.2007.19.9.1498  
[2] OASIS: Longitudinal: https://doi.org/10.1162/jocn.2009.21407