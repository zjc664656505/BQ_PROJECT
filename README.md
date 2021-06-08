# BQ_PROJECT - UC Irvine Data Science Major Capstion Project (Partner Company - BrightQuery Inc.)
Setup:
1. In this project, we did the public financial perforance prediction using Temporal-Fushion Transformer Model.
2. Before you run the notebook code: please first go to this link: https://drive.google.com/drive/folders/1I6Z-60iJqEU9jkXmWRc6UT06kRcm2mkO?usp=sharing (These are not Company's original datasets, they have been preprocessed by the Company and do not contain any restricted information, we also ask the Company and they guaranteed us to do it).
3. The link showing above is our shared cloud Google Drive folder which contains our preprocessed data and relevant information of our project.
4. After you opened this link and got into this folder, please add this folder as a short-cut to your Google Drive you usually use.
5. Once the folder is added to your Google MyDrive, then you can start run the notebook on colab.
6. It's important to run the colab notebook with the GPU, otherwise, the Temporal-Fusion Transformer cannot run.
7. Also, it's important to run the notebook by signing in with your correct Google account, which links with the Google Drive folder that contains the data files.
8. Once all setup showing above is done, you can run all the notebook files.
9. Since the Notebooks for data management and data visualization use the complete datasets, we suggest not running them but viewing the results, still code is runnable.
10. The trainings could take >10 minutes, which makes us train them offline and upload the models with the sample data to illustrate them
12. We provide the lines for local running with sample dataset by relative path in Notebooks for model training as demo using, so you can run these instead of running mount google drive and absolute path lines.
14. Please contact us if there is difficulty in running the demos.

File Description:
1. Report_Data_Management.ipynb: Notebook contains the code for managing the data for the project with presentation of sample dataset for using at last. (Complete datasets are in Drive folder, so this is only for presenting our data management)
2. BQ_DataVisualization.ipynb: Notebook includes the code for dataset visualization for important sectors, Pearson Correlations between financial variables, and the differences between and within different sectors and states. (Visualizations are generated based on complete datasets in the Drive folder, so this is only for understanding the data)
3. BQ_LinearRegression.ipynb: Notebook contains the code for linear regression model training (sample dataset importable).
4. REI_feature+model+eval+visual.ipynb: Notebook that contains the code for TFT model training  (sample dataset importable). 
5. Data_3000.csv: The csv of sample ready-for-modelling data that has the size of 3000.
6. NetIncomeFeatures.csv: Saved csv for results of example feature selection for Net Income. 
7. RevenueFeatures.csv: Saved csv for results of example feature selection for Revenue. 
8. EbitdaFeatures.csv: Saved csv for results of example feature selection for Ebitda. 

Contributors - University of California, Irvine: 
1. Junchen Zhao (junchez3@uci.edu).
2. Liya Yang (liyay4@uci.edu).
3. Ruiqi Li (ruiql10@uci.edu).

