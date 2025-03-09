# Twitter-Sentiment-Analysis
This Project utilizes advanced topic modeling and theme grouping to analyze and categorize climate change discussions on Twitter, based on a dataset of tweets reflecting diverse sentiments over time. The goal is to identify and prioritize key climate issues through dynamic discourse analysis


# Twitter Sentiment Analysis on Climate Change Discourse
# Overview
This project analyzes public sentiment and discourse on climate change using a dataset of 43,943 tweets collected between April 26, 2015, and February 21, 2018. By leveraging advanced topic modeling techniques, specifically BERTopic, the study identifies key themes, inter-topic relationships, and public perceptions surrounding climate change discussions on Twitter. The findings provide insights into how social media reflects and shapes public opinion on this critical global issue.

# Key Features
Dataset: A curated collection of tweets annotated with sentiment labels (supportive, neutral, or unfavorable) related to climate change.

Topic Modeling: Utilizes BERTopic, a transformer-based approach, to uncover and group prominent themes in the discourse.

Visualizations: Includes similarity matrices, hierarchical clustering diagrams, and topic probability distributions to illustrate the relationships and prevalence of topics.

Insights: Highlights key topics such as political policies, scientific debates, economic impacts, biodiversity concerns, and public activism.

# Methodology
Data Selection: Tweets were sourced from a publicly available repository, ensuring relevance and accuracy for climate change discussions.

Data Preprocessing: Text normalization, removal of URLs, handles, and stopwords to clean and prepare the data for analysis.

Modeling Approach: BERTopic was employed for its ability to handle short texts (tweets) and capture nuanced semantic relationships.

Analysis: Topics were identified, and inter-topic relationships were explored using similarity matrices and hierarchical clustering.

# Results
The analysis revealed five major topics:

Political Policies and Global Agreements

Scientific Debate and Skepticism

Impact on Wildlife and Nature

Economic Impact and Energy Policies

Activism and Public Awareness Campaigns

Visualizations such as similarity matrices and hierarchical clustering diagrams provided a clear understanding of how these topics interconnect and their prevalence in public discourse.

# Limitations
The dataset is limited to English-language tweets, potentially excluding non-English perspectives.

Social media sentiment can be influenced by temporal events, which may not reflect stable public opinion.

# Future Work
Expand the dataset to include multi-lingual tweets for a more global perspective.

Implement adaptive topic modeling to track how public opinion evolves over time.

Incorporate sentiment analysis to better understand the emotional tone of climate change discussions.

# clone the repo
git clone https://github.com/Ahmedkhan310/twitter-sentiment-analysis.git  

# How to use
pip install -r requirements.txt  