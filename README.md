# British_AirLine_Analysis_and_prediction
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <p>This repository contains the work completed as part of a data science job simulation with British Airways. The simulation was supervised by a virtual data science team and consisted of two tasks aimed at extracting insights and building predictive models from customer data.</p>
    <h2>Task 1: Customer Sentiment Analysis</h2>
    <p>The first task involved scraping customer reviews from the Skytrax website and performing Natural Language Processing (NLP) to extract insights and classify customer sentiments.</p>
    <h3>Steps Taken:</h3>
    <ul>
        <li><strong>Data Scraping:</strong> Customer reviews were scraped from Skytrax using <code>BeautifulSoup</code> to collect raw review data.</li>
        <li><strong>Data Cleaning:</strong>
            <ul>
                <li>Removed unknown characters and normalized the text to ensure uniform casing.</li>
                <li>Tokenized the reviews using <code>NLTK POS Tagger</code> to break the text into meaningful units.</li>
                <li>Removed stopwords and punctuation to retain only the essential text for analysis.</li>
            </ul>
        </li>
        <li><strong>Sentiment Analysis:</strong> 
            <ul>
                <li>Classified the sentiment of each review into positive, negative, or neutral categories based on polarity scores.</li>
                <li>Assigned ratings to each review based on sentiment polarity to classify customer satisfaction.</li>
            </ul>
        </li>
        <li><strong>Token Analysis:</strong> 
            <ul>
                <li>Identified and analyzed positive and negative tokens by examining the content of positive and negative reviews.</li>
            </ul>
        </li>
        <li><strong>Visualization:</strong>
            <ul>
                <li>Created visualizations to show the overall customer sentiment, comparing the number of satisfied versus dissatisfied customers.</li>
            </ul>
        </li>
    </ul>
    <h2>Task 2: Predictive Modeling for Customer Booking Data</h2>
    <p>The second task involved building a predictive model to forecast whether customers would purchase flights or holidays based on historical booking data.</p>
    <h3>Steps Taken:</h3>
    <ul>
        <li><strong>Data Preprocessing:</strong> 
            <ul>
                <li>Split the data into training and testing sets prior to any transformations to avoid data leakage and ensure model integrity.</li>
                <li>Performed feature selection using Mutual Information (MI) scoring to identify the most relevant features for the model.</li>
            </ul>
        </li>
        <li><strong>Model Building:</strong>
            <ul>
                <li>Built and trained machine learning models using <code>XGBoost</code> and <code>RandomForest</code> algorithms.</li>
                <li>Ensured that the models were optimized for predicting whether a customer would purchase a flight or holiday.</li>
            </ul>
        </li>
        <li><strong>Model Evaluation:</strong>
            <ul>
                <li>Evaluated the model performance using various metrics to assess how well the models predicted the target outcome.</li>
                <li>Interpreted the results of the models to determine which features were most important in predicting customer bookings.</li>
            </ul>
        </li>
    </ul>
    <h3>Key Technologies and Libraries Used:</h3>
    <ul>
        <li>Python, BeautifulSoup, NLTK, XGBoost, RandomForest, scikit-learn, matplotlib, pandas, numpy.</li>
        <li>Data Preprocessing: Tokenization, Sentiment Analysis, Data Transformation, Feature Selection.</li>
    </ul>
    <h2>Conclusion</h2>
    <p>The tasks completed in this job simulation helped to demonstrate the use of data science and machine learning techniques to analyze customer sentiments and build predictive models. The insights gained from the reviews helped in understanding customer satisfaction, and the predictive model was designed to proactively target customers for bookings.</p>

</body>
</html>
