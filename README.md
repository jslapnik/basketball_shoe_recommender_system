# Basketball Shoe Recommender System

I want to start out by saying that I am a sneakerhead. I buy a lot of shoes, with a majority being perfromace basketball shoes. When I am looking to purchase a new pair, I always start my search in the same place: weartesters.com. WearTesters is the go-to site for honest and unbiased basketball shoe performance reviews. All of the WearTesters reviewers are knowledgable about shoes in general, but also all of the different performance aspects from each brand. 

When I am looking to buy new shoes, I do not always have time to read and/or watch multiple WearTesters reviews to decide if a shoe is worth it or not. I wanted a program that could quickly analyze an inputted shoe, compare it to other basketball shoes, and output a similar option. This is where my idea came into play. After conducting some research, I quickly found that there is not a basketball shoe recommendation system anywhere on the internet.  The closest comparable program I was able to find was a running shoe recommendation system from a running shoe retailer. I decided to take matters inot my own hands and create my own recommendation system. This is where WearTesters came into play.

I reached out and explained my idea to one of the founders and he loved the idea. He gave me permission to scrape their website to gather all of the reviews to build my system. Once all of the reviews were scraped, I was able to break them down and assign a weight to each word (the more a word shows up, the greater the weight). Once each word was weighted, I used cosine similarity to compare reviews to one another. When a shoe is inputted into the system, the program goes through and finds the shoes with the highest cosine similarity to the input and outputs the top five results. The user can then go and research those shoes to determine if they want any of those shoes.














