# Final_Project
Antibiotic resistance is a critical global health concern resulting from bacteria development and antimicrobial misuse. It poses significant challenges to public health, as resistant bacteria evade treatment, leading to persistent infections. We aim to determine the likelihood of bacterial resistance to specific drugs by assessing gene resistance probabilities.

Our research goal is to classify gene resistance levels to antibiotics. Existing databases partially categorize resistance of bacteria to specific antibiotics and resistance of genes to antibiotic families. To achieve our objective, we used both supervised and unsupervised machine learning methods.

Initially, we explored the relationship between bacteria and genes using the unsupervised bicluster model. However, it didn't directly contribute to our research goal. Subsequently, we shifted to a supervised approach, utilizing a logical model instead of MLP network. This model provided coherent and interpretable results for classifying gene resistance based on diverse datasets.

During training, we built 114 logical models for specific drugs, considering various factors such as gene presence and its relevance to antibiotic families. The logical model effectively determined gene resistance probabilities, enabling better antibiotic resistance classification based on the given data.











Note: The code is in: "Create_data_Final" notebook, the csv files for runing the noteboook is in "CSV Files.zip"
