### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 13.04.2024
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
<img width="960" alt="exp - 09 - 06" src="https://github.com/Shavedha/WDM_EXP9/assets/93427376/a41ea53e-8ae7-46e8-badc-d63fb88f59c2">


<img width="960" alt="exp 09 - 05" src="https://github.com/Shavedha/WDM_EXP9/assets/93427376/5acdf7d3-0f90-45e3-a343-7fc38f8e0989">


![exp 09 - 01](https://github.com/Shavedha/WDM_EXP9/assets/93427376/b854ce19-46e4-43de-a2b7-956b38524cea)

<img width="960" alt="exp 09 - 02" src="https://github.com/Shavedha/WDM_EXP9/assets/93427376/68a4a839-172d-4869-8528-3755cf90a90f">

<img width="960" alt="exp - 09 - 03" src="https://github.com/Shavedha/WDM_EXP9/assets/93427376/161a00ad-72be-4c50-beb8-17eb3ec96f98">

<img width="960" alt="exp - 09 - 04" src="https://github.com/Shavedha/WDM_EXP9/assets/93427376/524d3b32-0e60-4ff8-b412-0d0036784e02">


### Result:
Thus preprocessing technique on Twitter Data Rapidminer is implemented successfully.
