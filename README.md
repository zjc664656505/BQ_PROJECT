# BQ_PROJECT - UC Irvine Data Science Major Capstion Project (Partner Company - BrightQuery Inc.)
Setup:
1. In this project, we did the public financial perforance prediction using Temporal-Fushion Transformer Model.
2. Before you run the notebook code: please first go to this link: https://drive.google.com/drive/folders/1I6Z-60iJqEU9jkXmWRc6UT06kRcm2mkO?usp=sharing (Company approved for sharing these sets of data).
3. The link showing above is our shared cloud Google Drive folder which contains our preprocessed data and relevant information of our project.
4. After you opened this link and got into this folder, please add this folder as a short-cut to your Google Drive you usually use.
5. Once the folder is added to your Google MyDrive, then you can start run the notebook on colab.
6. It's important to run the colab notebook with the GPU, otherwise, the Temporal-Fusion Transformer cannot run.
7. Also, it's important to run the notebook by signing in with your correct Google account, which links with the Google Drive folder that contains the data files.
8. Once all setup showing above is done, you can run all the notebook files.
9. The use of relative path is not valid here to read files from Google Drive, so only absolute path is doable here.
10. If you are not sure with the procedure or doubt the appropriateness, please contact us so that we can help you.

File Description:
1. BQ_LinearRegression.ipynb: Notebook contains the code for checking assumptions, training models using linear regression.
2. Report_Data_Management.ipynb: Notebook contains the code for preprocessing and managing the raw data for the project with presentation of sample dataset for using at last. (Only for presenting our data management, do not run it)
3. Data_3000.csv: The data for modelling in this report which has the sample size of 3000.
4. BQ_DataVisualization.ipynb: Notebook includes the code for dataset visualization for important sectors, Pearson Correlations between financial variables, and the differences between and within different sectors and states. (Because the visualizations are generated based on complete datasets instead of sample, only for presenting and understanding the data, so better not run it)
5. REI_feature+model+eval+visual.ipynb: Notebook that contains the code of importing the sample processed dataset to do feature selection, model training, evaluations, and visualizations, mainly for revenue, EBITDA, net income. (Important: The whole training could take >10 minutes, so we train offline and upload the model with the imported data, running results, and evaluations) 

Contributors - University of California, Irvine: 
1. Junchen Zhao (junchez3@uci.edu).
2. Liya Yang (liyay4@uci.edu).
3. Ruiqi Li (ruiql10@uci.edu).

