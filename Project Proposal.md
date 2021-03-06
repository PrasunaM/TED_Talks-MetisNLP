# NLP Project Proposal

#### Question/need:
* What is the framing question of your analysis, or the purpose of the model/system you plan to build? 

Change is inevitable and is happening all around us. Social change is stimulated by media, human interactions, technology, and social environment. 
[TED Talks](https://www.ted.com/talks) is one such platform that enables expert speakers from all backgrounds to present their ideas that can influence a positive change in the society. 

My aim is to leverage the capabilities of NLP to understand what words or topics make the most persuasive talks and if any relationships among them. In addition, I would like to focus on how topics evolved over the years. Finally, I would like to build a linear regression model to predict the number of views.      


* Who benefits from exploring this question or building this model/system?

I'm hoping to find any similar words or phrases from the transcripts to learn how to prepare an impactful speech. I also plan to understand the topics that became most popular (analyzing the number of views).   

#### Data Description:
* What dataset(s) do you plan to use, and how will you obtain the data?

Dataset is downloaded from [here](https://www.kaggle.com/rounakbanik/ted-talks) which is present on Kaggle as a CSV file. Two CSV files are present, which will be merged to create a final dataframe. 

Data contains 2467 trancripts from 2006 to 2017 and talks are filtered with a minimum word count of 100. 

* What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with? 

Each row represents details about a single talk. I plan to use 3 features - Transcript, URL and views.

* If modeling, what will you predict as your target?

I plan to perform topic modeling for each talk using unsupervised techniques and no. of views using linear regression.  

#### Tools:
* How do you intend to meet the tools requirement of the project? 

    * spaCy, Numpy, Pandas for data cleaning and EDA
    * Scikit-learn for modelling and analysis
    * Matplotlib, Tableau for visualization 

* Are you planning in advance to need or use additional tools beyond those required?

May be visualizations on tableau if time permits.

#### MVP Goal:
* What would a [minimum viable product (MVP)](./mvp.md) look like for this project?

MVP will contain preprocessed data with some topic modeling performed. 


