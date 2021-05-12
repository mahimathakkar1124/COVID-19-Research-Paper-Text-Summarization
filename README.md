# COVID-19-Research-Paper-Text-Summarization

Contributors:
  Mahima Thakkar
 

*Overview*:
With the enlargement of the digitized text, Automatic Text Summarization offers a solution to both better help discover relevant information and to consume relevant information faster. 


*Project Goal*:

The aim of the project is to tide over between the researchers and the rapidly growing publications. The work will be potentially aiding overburdened health workers in finding scientific answers during a time of crisis. 


*Motivation:*

In this pandemic, there have been a lot of research papers available by people that cover all the areas such as health, vaccination, impacts of COVID-19 on economy, social and mental state of people.With the COVID-19 pandemic, there is a growing urgency for the medical community to keep up with the accelerating growth in the new coronavirus-related literature.



*Data Summary:*

The data is collected from the [COVID 19 NLP Insight Hub](https://www.linguamatics.com/linguamatics-nlp-covid-19-insights-hub) portal that provides links to the Sciencedirect research paper repository. (https://www.sciencedirect.com/articlelist/covid)
Due to access restrictions to the website, automatic scrapping of the data was denied. Thus the research papers are downloaded manually to form the dataset. 
These papers cover all the areas that have been impacted due to the COVID-19 pandemic. There are 120 articles present in the dataset with each varying in the number of pages.


Data Access:

["COVID-19 Research Papers"](https://drive.google.com/drive/folders/1BQjhKhmnojDSv80KdobmIbq1LbVE7q3A?usp=sharing)

Notebooks:

["Exploratory Data Analysis"](https://github.com/mahimathakkar1124/COVID-19-Research-Paper-Text-Summarization/blob/main/Data606_EDA.ipynb)

["UI Demo"](https://github.com/mahimathakkar1124/COVID-19-Research-Paper-Text-Summarization/blob/main/Data606_UIDemo.ipynb) This notebook shows the UI part of the project. People can select a paper from list of papers avilable. 

["Single Test Notebook"](https://github.com/mahimathakkar1124/COVID-19-Research-Paper-Text-Summarization/blob/main/Data606_SingleTest.ipynb)

["Extractive Summarization"](https://github.com/mahimathakkar1124/COVID-19-Research-Paper-Text-Summarization/blob/main/Data606_Extractive_Summarization.ipynb) This notebook has the algorithms and output for Extractive Summarization.

["Abstractive Summariation"](https://github.com/mahimathakkar1124/COVID-19-Research-Paper-Text-Summarization/blob/main/Data_606_Abstractive_Summarization.ipynb) This notebook has the algorithms and output for Abstractive Summarization.

*Conclusion*:

When a large language model is trained on a sufficiently large and diverse dataset it is able to perform well across many domains and datasets. In this project, pre-trained models are used to achieve the desired goal of the projects. The extractive pre-trained models are computationally cheaper than the abstractive pre-trained models. Extractive summaries consist of text cropped from original data. On the contrary, abstractive summaries are paraphrased summaries obtained by using state-of-art models. The model that gives out the best summary for Extractive Summarization is BERT-Summarizer. The model that gives out the best summary for Abstractive Summarization is GPT2 (by OpenAI)

["Presentation"](https://www.youtube.com/watch?v=Qbxn7Fv6AwU)


*Softwares and Packages:*

Project Info:

Contributors: Mahima Thakkar.

Languages: Python.

Tools/IDE: Google Colaboratory

Duration: Spring 2021.
