# breast-cancer


**Description**
tested by using FNA(Fine needle aspirate )
 In the world, breast cancer is the most frequent cancer to affect women. It affects about 2.1 million people in 2015 alone and makes up 25% of all cancer cases. It all begins when breast cells start to proliferate uncontrollably. Usually, these cells develop into tumors that are felt as lumps in the breast area or that are visible on X-rays.
 
 The main obstacle to its discovery is determining whether a tumor is benign (not cancerous) or malignant (cancerous). Please nish the analysis of the Breast Cancer Wisconsin (Diagnostic) Dataset and machine learning (using Logistic Regression) to classify these tumors

 ![image](https://github.com/user-attachments/assets/6a5dbf5d-d67a-4207-a7de-f2bd06b16151)

**About the dataset**
The spread of breast cancer in today's digital landscape has increased the likelihood of death, posing significant challenges for both patients and clinicians. This study focuses on the essential challenge of identifying breast cancer by swiftly recognising cancer by breast mass, which can result in a faster cure and less life losses for customers. The dataset utilised in this analysis is a snapshot of two days' worth of credit card transactions done by European cardholders in September 2013. Breast cancer affects millions of women worldwide and is influenced by factors such as family history, hormones, and reproductive factors. Alarming data show that half of the one million women diagnosed each year die as a result of delayed diagnosis. Despite a lack of facts on causes and treatments, a popular belief argues that cancer is caused by unregulated cell development. The interruption of the normal cell's life cycle, which is required for division and programmed death, raises the risk, with age appearing to be a crucial predictor in the occurrence of breast cancer regardless of family history.

Data Source Links: The dataset used for this analysis is at UC Irvine Machine Learning Repository.
Link: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic



**EDA**

![image](https://github.com/user-attachments/assets/fbf752a3-6d82-4fde-9003-e4738182f4f5)

the data have 357 benigne(non-cancerous) and 212 have malignant(cancerous)

![image](https://github.com/user-attachments/assets/3e04cb05-b068-4598-a738-91c049e9b023)

 **Key observations (scatter plot):**
 Positive Correlations: Some scatter plots exhibit positive correlations, where higher values in one variable correspond with higher values inanother. For example, as radius_mean increases, area_mean tends to increase as well.
 **Distinct Clusters:** Data points are clustered differently for benign and malignant diagnoses, indicating distinct characteristics associated witheach diagnosis.
 **Patterns and Trends:** By examining the scatter plots, we can identify patterns and trends in the relationships between these variables.
 
**Key observations (histogram):**
 There might be benign tumors with radius_mean values that overlap with the range of radius_mean values seen in malignant tumors. Similarly, some texture_mean values are shared between both diagnoses. These overlapping regions make it challenging to use a single threshold value to de nitively classify a tumor as benign or malignant based solely on these variables.

 ![image](https://github.com/user-attachments/assets/9d203296-95c6-40e1-84c5-7876dd25d107) 
 
  **Overlap:** There is signi cant overlap between the benign (blue) and malignant (orange) data points.
  
 **Variability:** Both benign and malignant tumors exhibit a wide range of texture mean and radius mean values.
 
 **No Clear Separation:** Unlike some other datasets, there is no clear separation or distinct pattern that allows us to easily differentiate between benign and malignant tumors based solely on these two variables.
 

**HeatMap**

![image](https://github.com/user-attachments/assets/764303a5-40df-48d2-a8bd-2b3a264d0bdc)

![image](https://github.com/user-attachments/assets/fe3827f8-6913-4d49-8866-3bfeb3394b90)

![image](https://github.com/user-attachments/assets/9b23f454-bfc3-4520-805b-8eda84006453)

![image](https://github.com/user-attachments/assets/28a04cba-b717-4532-9bf9-824ba10bacbd)

![image](https://github.com/user-attachments/assets/31edcadd-aab3-42a6-86d2-c98f58018858)









