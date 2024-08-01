> [!TIP]
> Read this first. 

# Amazon product reviews: analyzing user feedback through sentiment score and issue categorizationx

Recently, I picked up *running as a hobby*. I was debating whether to buy a **running vest** to hold my phone and keys while outdoors, so I decided to utilize my data skills to analyze [this Amazon product](https://www.amazon.com/Zelvot-Adjustable-Hydration-Breathable-Reflective/dp/B0D6YMKZ64/ref=cm_cr_arp_d_bdcrb_top?ie=UTF8). 

## The task

- Scrape product reviews from the Amazon website (I used a mix of BeautifulSoup and Selenium to navigate all the pages)
- Create a dataframe to store all reviews and their rating scores
- Clean and explore the data
- Add sentiment analysis with BERT pre-trained NLP model
- Visualize and review results 
- Compare rating score (1 to 5 stars) to BERT score (1 to 5 points) as in distribution and correlation between the two
- Analyze nuanced reviews (5-star with low BERT score) to gain insights
- Visualize reviews' keywords
- Categorize issues using targeted keywords on reviews

## Findings

- Currently, we have **73 reviews** for this product with an average rating of **4.46 stars**. 
- We performed a sentiment analysis using ML (BERT pre-trained model) and noticed a **positive correlation between sentiment score and rating score** of our reviews.
- The sentiment score gave us a **more nuanced look** at each review.
- In particular, by reviewing 5-star reviews with negative sentiment, we were able to pick up user feedback about **sizing issues** and **comfort in warm weather**. 
- On a positive note, the **customer support** was praised for providing high quality service.
- With a keyword analysis, we noticed **popular words used** in our reviews are mostly positive, with **focus on product features**, our strongest asset. We have a few negative mentions concerning **sizing**.
- To investigate this matter further, we categorized reviews based on issues. **Sizing issues** are mentioned in **4% of our reviews**, while there are no complaints related to price or faulty items.

Thank you for checking out this repo! :star2: