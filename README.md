# Alzheimer’s Neuroimaging Analysis  

This project analyzes neuroimaging biomarkers and cognitive decline in Alzheimer's disease using the OASIS-3 dataset. The study applies machine learning techniques to investigate the relationships between brain region volumes, cognitive scores, and demographic factors.  

## Project Overview  

Alzheimer’s disease is a progressive neurodegenerative disorder that affects millions worldwide. This project leverages neuroimaging and clinical data to:  
- Identify key brain regions associated with disease progression  
- Predict cognitive decline using machine learning models  
- Explore demographic and clinical factors influencing Alzheimer’s severity  

## Key Features  
- **Data Processing & Cleaning**: Handling raw MRI scan data and clinical records  
- **Exploratory Data Analysis (EDA)**: Visualizing neuroimaging biomarkers and cognitive assessments  
- **Feature Engineering**: Extracting relevant features from FreeSurfer volumetric data  
- **Machine Learning Models**: Implementing Random Forest, Linear Regression, K-Means, and PCA  
- **Time-Series Analysis**: Tracking disease progression over multiple MRI sessions  

## Data Sources  
The dataset used in this project is from **OASIS-3**, an open-access longitudinal dataset with over 1,400 MRI scans from Alzheimer’s patients. The data includes:  
- **Neuroimaging Metrics**: Brain region volumes, cortical thickness, and hippocampal atrophy  
- **Clinical Assessments**: Cognitive scores, dementia staging, and patient demographics  
- **Longitudinal Data**: Repeated scans for tracking progression over time  

## Technologies Used  
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Machine Learning**: Random Forest, PCA, Linear Regression, K-Means Clustering  
- **Data Visualization**: Seaborn, Matplotlib, Plotly  

## Results & Findings  
- Unfinished

## Future Work  
- Incorporating deep learning models for improved prediction accuracy  
- Analyzing genetic and lifestyle factors affecting Alzheimer’s progression  
- Expanding dataset coverage with external neuroimaging sources  

## References  
- OASIS-3 Dataset: [OASIS Brains](https://www.oasis-brains.org/)  
- FreeSurfer Software: [FreeSurfer](https://surfer.nmr.mgh.harvard.edu/)  

## How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/alzheimers-neuroimaging-analysis.git  
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt  
   ```
3. Run the data preprocessing script:  
   ```bash
   python preprocess_data.py  
   ```
4. Train machine learning models:  
   ```bash
   python train_model.py  
   ```
5. View results and visualizations in `notebooks/`  

## Contributors  
- [David Costa - Author](https://github.com/costad3atwit) 
