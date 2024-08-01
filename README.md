> [!TIP]
> Read this first. 

# Amazon product reviews: analyzing user feedback through sentiment score and issue categorization

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
- Rating score and BERT score have positive correlation, yet BERT score gives us a more nuanced look at the sentiment behind the stars given by our customers. 
- In particular, by comparing the two scores, we are able to pick up user feedback about sizing issues and comfort under warm weather. 
- On a positive note, the customer support seems to do a great job when contacted by customers over product issues. 
- Keywords seem to be mostly positive for these reviews, with focus on product features. A few negative mentions refer to the size.
- To investigate this further, we categorize reviews based on issues. Sizing issues seems to affect 4% of our reviews, while there are no mentions of complaints related to price or faulty items.

Thank you for checking out this repo! :star2: