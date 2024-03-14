# NewsArticleSummarization
We are doing this project in our CSE475 course. For now we will use this readme file to list down our progress. Afetr finishing the whole project we will rearrange it in proper way.

<h1>Lab01</h1>
<p>We learn about the workflow of the projects and what we will do in which lab</p>
<hr>
<h1>Lab02</h1>
<p>We Proposed our projects and related information</p>
<hr>
<h1>Lab03</h1>
<p>We have find datasets and related information</p>
# Dataset Information

### task 1. Dataset collection:
   - NEWS SUMMARY (kaggle.com)[https://www.kaggle.com/datasets/sunnysai12345/news-summary]

### task 2. Use Ipython Notebook:
   - Available (done)

### task 3. Dataset Brief Description:   
   - The first dataset consists of 4515 examples and contains the Author's name, Headlines, URL of the Article, Short text, and Complete Article. The summarized news in shorts was gathered, scraping news articles from the Hindu, Indian Times, and Guardian, spanning from February to August 2017.
   - The second dataset consists of 98402 rows with 2 columns labeled as headlines and text.
   - To increase the intake of possible text values to build a reliable model for text summarization on news articles, these datasets were merged before preprocessing and cleaning. The merged dataset contains 102915 rows and 2 columns labeled as text and summary, while the text column has some null values.

### task 4. Data Dictionary: 
   - Raw Datasets:
     - **Dataset 1: news_summary.csv**
       | Column Name | Data Type | Description             |
       |-------------|-----------|-------------------------|
       | author      | String    | Contains the news author's name  |
       | date        | String    | Date of publication     |
       | headlines   | String    | Headline Of the news    |
       | read_more   | String    | URL link to the news    |
       | text        | String    | Short or summary of the article |
       | ctext       | String    | The main content of the news      |

     - **Dataset 2: news_summary_more.csv**
       | Column Name | Data Type | Description              |
       |-------------|-----------|--------------------------|
       | headlines   | String    | Contains the headline of the news |
       | text        | String    | Contains the content of the news  |

   - **Merged Dataset: "Tuned News Summary"**
     | Column Name | Data Type | Description                         |
     |-------------|-----------|-------------------------------------|
     | text        | String    | Contains the long text or description of the article. Used to train the model. |
     | summary     | String    | Contains the summary of the particular article. The model will predict this part.  |

### task 5. We have done this task using iPython Notebook (collab)

### task 6. Datasets Insite (text -> Defination):
   - For an average length of 70 words of text, the dataset has a summary of 10 words. The ratio is 7:1.

<hr>




