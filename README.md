> [!TIP]
> Read this first. 

# Amazon product reviews: analyzing user feedback through sentiment score and issue categorization

Recently, I picked up *running as a hobby*. I was debating whether to buy a **running vest** to hold my phone and keys while outdoors, so I decided to utilize my data skills to analyze [this Amazon product](https://www.amazon.com/Zelvot-Adjustable-Hydration-Breathable-Reflective/dp/B0D6YMKZ64/ref=cm_cr_arp_d_bdcrb_top?ie=UTF8). 

## The task

- Scrape product reviews from the Amazon website (I used a mix of BeautifulSoup and Selenium to navigate all the pages).
- Create a dataframe to store all reviews and their rating scores.
- Clean and explore the data.
- Add sentiment analysis with BERT pre-trained NLP model.
- Visualize and review results.
- Compare rating score (1 to 5 stars) to BERT score (1 to 5 points) as in distribution and correlation between the two.
- Identify more nuanced reviews and uncover additional insights.
- Visualize reviews' keywords.
- Categorize issues using targeted keywords on reviews.

## Findings

- Currently, we have **73 reviews** for this product with an average rating of **4.46 stars**. 
- This running vest's strongest asset is **its features**, such as holders and reflective strips for extra comfort when running.
- **Size** seems to be the main issue highlighted by customers. This is visible in all techniques employed.
- Through a sentiment analysis of our reviews and a comparison of rating scores, we picked up more nuanced user feedback about **sizing issues** and **comfort in warm weather**. 
- On a positive note, the **customer support team** was praised for providing high quality service.
- Through a keyword analysis, we noticed **popular words used** in our reviews are mostly positive, with **focus on product features** . We have a few negative mentions concerning **sizing**. 
- By categorizing reviews based on issues, **size** is mentioned in **4% of our reviews**, while there are no complaints related to price or faulty items.

Thank you for checking out this repo! :star2: