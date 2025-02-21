# Airline-Review-Analysis-Using-NLP-Web-Scraping

Project Workflow:-

1️⃣ Data Collection via Web Scraping
- Scraped airline reviews from Skytrax, ensuring a structured dataset by focussing only on passenger feedbacks rather than airport facilities
- Used BeautifulSoup and Requests to extract review content, ratings and other relevant metadata.
- Stored the collected data in a CSV file for further analysis.

2️⃣ Data Cleaning & Preprocessing
- Removed HTML tags, special characters, emojis and unnecessary whitespace to standardize the text.
- Eliminated duplicate words and stopwords to improve text analysis.
- Converted all of the text to lowercase and handled missing values where necessary.

3️⃣ Sentiment Analysis
- Used TextBlob to classify customer sentiments as positive, neutral or negative based on textual polarity.
- Analyzed sentiment trends over time to identify shifts in customer satisfaction.

4️⃣ Word Cloud Visualization
- Generated word clouds using the WordCloud library to highlight the most frequently mentioned words in reviews.
- Helped visualize common themes in customer feedback (e.g., “service,” “delays,” “crew,” “food”).

5️⃣ Topic Modeling (LDA - Latent Dirichlet Allocation)
- Applied LDA topic modeling using Gensim to uncover hidden themes in passenger reviews.
- Identified key topics such as flight delays, customer service, baggage handling, in-flight experience and pricing.
