### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 
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
![322552744-053889c4-3dd7-4cfd-8719-895e2735983f](https://github.com/Naveenvetrivel/WDM_EXP9/assets/94165322/fe089b85-b217-44aa-bfc2-f51c2dcaef49)
![322552786-face3d49-b342-4c05-8c8c-ef1ff987485f](https://github.com/Naveenvetrivel/WDM_EXP9/assets/94165322/83b9769a-bfbe-4a71-8317-e888d823dc0f)
![322552843-ef93ddef-6bb4-4779-8cf9-0091dfc96885](https://github.com/Naveenvetrivel/WDM_EXP9/assets/94165322/a886bcd4-769e-4fa9-89d8-994e6396c155)
![322552884-3725b720-20ee-4e32-855a-e33483c225be](https://github.com/Naveenvetrivel/WDM_EXP9/assets/94165322/64fcf2e4-a001-4b15-bdb4-a31d0eebcd59)

### Result:
Thus, the preprocessing technique on Twitter Data using Rapidminer is implemented successfully.
