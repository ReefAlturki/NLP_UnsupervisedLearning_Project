
# Natural Language Processing Project Proposal
**authors**:

Reef Alturki

Raghad Alarifi


## Backstory

Online reviews from customers have created a new field in marketing and communication it helps to better Understand your Customers and Improve Customer Service. Twitter is one of the most used social media platforms where people write their opinions and the honest feedback of businesses based on a personal experience. in this project, we are going to analyze tweets about customers' shopping experience with ASOS which is a British online fashion and cosmetic retailer that provides worldwide shipping, primarily aimed at young adults.



## Question/need:

**What is the framing question of your analysis, or the purpose of the model/system you plan to build?**


The main goal of this project is to build unsupervised learning models that address a meaningful topic modeling of customers' written Tweets about their ASOS online shopping experience. we are going to bulid different models and compare them to use the best model. The models focuse ob finding postive and negative user's feedbacks. We are also going to explore the time series feature of a tweet in order to get insightful analysis.



**Who benefits from exploring this question or building this model/system?**


ASOS marketing team and quality assurance department can benefit from this project to improve their services.


## Data Description:

**What dataset(s) do you plan to use, and how will you obtain the data?**

The data in this project will be acquired from Twitter users' tweets about their experience with ASOS. We are planning to use Twint which is an advanced Twitter scraping tool written in Python that allows for scraping Tweets from Twitter. we are planning to acquire over 14000 tweets from the last two years. 

**What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?**

An individual unit of analysis is a document (tweet) in the corpus. We are planning to work with the textual features of the tweet.



## Tools:
**How do you intend to meet the tools requirement of the project?**

We are mainly going to work with Python text processing libraries such as NLTK, spaCy, and scikit-learn in order to work with human language data. We also intend to use data acquisition called Twint for web scrapping. and after obtaining the data, it would be stored in SQL database. 
For visualizing the analysis results, we intend to use python's visualization libraries:  seaborn, Bokeh, and Plotly. and for the Production we are planning to use Streamlit to bulid a custom web app. 


