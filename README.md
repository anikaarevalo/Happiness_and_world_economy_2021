# 😊📊Correlation between happiness and economic development for year 2021

## Description ##
<p><strong>What is happiness and what are the keys to a happy life?</strong> We lead our lives for the most part believing that it's the attainment of'happiness' (or the 'good life') which gives meaning and direction to our respective and varied earthly pursuits. But what precisely are the variables directly linked to our achievement of wellbeing?</p><p><em>Can happiness be quantified or measured--and if so, is it a phenomenon directly shaped by classic economic forces behind material wealth or prosperity, e.g. <strong>GDP</strong>?</em> Although there are several types of correlations and analyses that we can perform to gain insights into the economic trends and relationships between different variables contributing to economic development, the attributes in play only become concretely relatable understood within the context of a <strong>nation's overall happiness score</strong>.</p><p>Discussions on 'happiness' may be replete in Psychology, Philosophy, and the Humanities, but what social conditions can we statistically infer (or predict) with our analysis of GDP-related data?</p><p>To this end, we'll apply specific data analysis methods and extract statistical correlations in order to give way to the answers and the insights we are seeking from the available data on global happiness and the international economy.<p>To raise the complexity of our data analysis goals, we'll also leverage on different statistical and machine learning techniques.</p>

<p>Here are some common correlations and analyses that we'll be exploring with our data:</p> 

1) GDP growth rates
2) Correlation of GDP with other economic indicators
3) Long-term economic trends
4) Forecasting

As an amateur philosopher and data science practitioner, this project is both personal and professional in significance. At this stage of the product cycle development, the **end-users** who come to mind are fellow ethusiasts who believe that living well is as much an acquired art as it is a science. 


## The App ##
This is a **digital tool that effectively (capability) and (capability) (what)documents...**. This is an exploratory project in data analysis and machine learning methods at the very least, and a proof of concept of..... that we can show to relevant actors in industry, the public sector, and society who are open to leveraging the latest technologies in predictive analytics when it comes to the provision of private or public goods and services.

## Installation ##
In the repository you can find the **requirements.txt** file. Make sure that these are installed. 

## Usage ##
- To analyze a text, go to the **.ipynb** file. In this file you can enter your text and run through the notebook. It will output **.csv file**. (See visualisations)

- The file **.ipynb** is where the actual model is created. The model is already trained and can be found in the models' folder. 

- The notebooks **scraping.ipynb** and **cleaning_texts.ipynb** are notebooks made for scraping our initial dataset and cleaning this dataset. The full preprocessing is combined in the **preprocessing.py** file.

- The file **custom_ner.ipynb** is an early attempt to create an annotator for () texts but does not, as of now, contribute to the actual preprocessing.



## Data Sources ##

- **Meta data, train-test-validation data** provided by the <a href="https://worldhappiness.report/">World Happiness Report</a> and the <a href="https://ourworldindata.org/grapher/national-gdp-constant-usd-wb?tab=table">World Economic Forum</a> 
- **Research material on Natural Language Processing (NLP) models** and available libraries were sourced from the following:
  - Latent Dirilicht Allocation (LDA) model optimised by the Mallet algorithm 
    
    https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/
  - Training Named Entity Recognition (NER) model in SpaCy
  
    https://www.machinelearningplus.com/nlp/training-custom-ner-model-in-spacy/ 

## Visuals ##

                   Our LDA model optimised by the Mallet algorithm showing an example of topic-keyword distribution 
<img width="1000" alt=" ">
A good topic model possessing fairly big, non-overlapping bubbles scattered throughout the chart instead of being clustered in one quadrant. When you hover over the bubbles, the interactive plot highlights the related keywords by ranking.

                                    Image of the interface of our deep learning solution
<img width="1000" alt=" ">
A sample output of top-20 topics and their correlated keywords when a tax-relevant document is fed as an input to our NLP LDA model optimised with Mallet algorithm





## Contributors: ##

- Anika Arevalo

https://www.linkedin.com/in/anika-arevalo/



## Timeline ##

(1) days

02/11/2023 - 00/00/2023

## Personal situation ##
I was able to successfully train and test two Mallet LDA models in English of two sizes (small and large). **As a minimum viable product (MVP), I am delivering this prototype that was developed using the small-sized NLP model that can be immediately deployed as a mobile application**.
Nonetheless, I also provide a trained large-sized NLP model to anticipate the downstream NLP tasks which relevant or interested parties can leverage. 
