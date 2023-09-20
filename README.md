# Objective
To develop a Machine Learning model that can predict freezing of gait in parkinson's disease.


# Overview about the project
Parkinson's Disease (PD) is a neurodegenerative disorder that affects millions of people worldwide, and one of its most debilitating symptoms is the phenomenon known as "Freeze of Gait" (FOG). FOG is characterized by sudden and temporary episodes of immobility or significant reduction in step length, which can lead to falls and a significant decrease in the quality of life for PD patients.
We will try to develop a model that can predict freeze of gait in patients accuractly.

# Models used
LSTM, XG Boost, Light GBM, GRU, Random Forest, 1D CNN

# Theory Overview
**What is Gait / Gait Disorder?**

The term "gait disorder" or "gait abnormality" is used to describe a number of conditions that impair a person's ability to walk normally. 
The gait, which includes elements like stride length, step breadth, walking speed, and posture, is the pattern and way in which a person walks. Different underlying medical diseases, traumas, or neurological problems might cause gait difficulties.

**What is Parkinson's Disease?**

Parkinson's disease is a chronic and progressive neurodegenerative disorder that primarily affects the central nervous system, particularly the brain. It is characterized by a range of motor and non-motor symptoms and is named after Dr. James Parkinson, who first described it in the early 19th century.
Parkinson's Disease is related to gait disorders because it often leads to problems with walking, including slow and shuffling gait, reduced stride length, balance issues, and episodes of freezing or festinating gait. These gait abnormalities are common symptoms of Parkinson's disease and can significantly impact mobility and balance in affected individuals.

# Dataset Overview
Link to dataset : https://data.mendeley.com/datasets/r8gmbtv7w2/3

Since healthcare dataset is not readily available. Finding a high quality was a challenge. The dataset used in this project was preprocessed and can be used directly to develop ML models.
We were given data of 12 patients in 12 seperate folders. Each folder contains 4 text files of seperate task with 60 columns overall, with last being our target column.
For detailed information, visit the dataset website (link above).

# Conclusion
In the pursuit of addressing the critical issue of Freezing of Gait (FoG) in Parkinson's Disease, this project has made significant strides. Through meticulous data pre-processing, feature engineering, and machine learning model development, we have successfully crafted a robust system for FoG detection and prediction.
The developed **lstm** model exhibits an impressive _accuracy rate of 87.9%_ in detecting and predicting FoG episodes. This accuracy not only surpasses existing approaches but also instils confidence in the potential of multimodal sensor-based solutions to enhance the quality of life for Parkinson's Disease patients

# Future Work
The journey towards effective FoG management in Parkinson's Disease patients is far from complete. The following areas present exciting avenues for future research and development:
1.	Collaboration with Healthcare Institutions: Collaborate with healthcare institutions and clinics to conduct large-scale clinical trials, further validating the model's efficacy and gaining insights into its real-world impact on patient outcomes.

2.	Expand Sensor Integration: Consider integrating additional sensors, such as heart rate monitors or pressure-sensitive insoles, to gather a more comprehensive dataset for FoG prediction and to capture broader aspects of patient health.

3.	Personalization and Adaptation: Explore methods to personalize the model to individual patients, considering their disease progression, medication regimens, and unique gait patterns. Adaptive learning algorithms could continuously update the model to improve accuracy over time.

4.	Long-term Monitoring: Investigate the system's capabilities for long-term FoG prediction, allowing for proactive interventions weeks or months in advance, potentially reducing the frequency and severity of FoG episodes.

# Reference and Bibliography
1.Human Gait Analysis in Neurodegenerative Diseases: A Review
Grazia Cicirelli, Donato Impedovo, Vincenzo Dentamaro, Roberto Marani, Giuseppe Pirlo, Tiziana R. D’Orazio

2.Selecting Clinically Relevant Gait Characteristics for Classification of Early Parkinson's Disease: A Comprehensive Machine Learning Approach
Rana Zia Ur Rehman, Silvia Del Din, Yu Guan, Alison J. Yarnall, Jian Qing Shi & Lynn Rochester

3.Classification of Gait Patterns in Patients with Neurodegenerative Disease Using Adaptive
Neuro-Fuzzy Inference System

4.Multimodal Data for the Detection of freezing of gait in Parkinson’s disease


