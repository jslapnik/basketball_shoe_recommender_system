# Basketball Shoe Recommender System

For my General Assembly Data Science Immersive Program capstone, I decided to bring one of my greatest passions, basketball shoes, into my course. The best way I thought of doing this was to build a recommender system. After doing some research, I found out that there currently is not a recommender system out there for basketball shoes. With basketball shoes, it can be tricky to find a pair that looks good and feels good. Once you find that pair, you more than likely want a similar shoe once it is time to move on to a new pair. Like most people looking for an honest shoe review, I turned to weartesters.com. This site is well respected in the sneaker industry for its in-depth honest reviews of the latest basketball shoes. The best part of this site is how ubiased the reviewers are. They just want to review basketball shoes for the people. They don't care about the brand. If a shoe is good, it is good. If it is not, they let the viewers and readers know.
  
Steps:
1. Gain permission to scrape weartesters.com
2. Scrape weartesters.com and acquire the links for each individual shoe review
3. Scrape each link to collect whatever data was in the link
4. Review the raw data and determine which data could be removed
5. Discard all data besides the text from the reviews (links, advertisements, images)
6. Save the reviews in a dataframe - each full review is its own cell
7. Go back and scrape the title from each review and save them in a second dataframe
8. Concatenate the two dataframes into one ensuring that the titles line up with the correct reviews
9. Drop all stop words (the, a, and, an, etc.) from the reviews
10. 
