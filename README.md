# Microfashion-Trend-Analysis

## Introduction 

This project aims to analyze the demographics and sentiment of users on the streetwear subreddit to gain insights into microfashion trends. By extracting and analyzing Reddit comments, we can better understand the age, location, and sentiment of users discussing streetwear. This information can be valuable for Direct-to-Consumer (D2C) brands looking to tailor their marketing strategies and collaborations.

## Importing Libraries and Setting Up Reddit API
We Used praw to authenticate and access the Reddit API for scraping comments from the 'streetwear' subreddit and Pnadas for storing and manipulating the scraped comments in a DataFrame

## Database Creation through MySQL 
A new database was created. This is where all the data extracted from Reddit comments would be stored.
Connection: In the Python script, a connection was established between the Python application and the MySQL database. This connection allows the Python script to communicate with the database, execute queries, and retrieve data.

#### Table Creation
Within the MySQL database, a table was created to structure the Reddit comments data. The table schema defines the structure of the data, including the column names and data types.

#### Data Insertion 
After creating the table, the Reddit comments data was inserted into the MySQL database. This involved iterating over the extracted comments and inserting them into the appropriate columns in the database table.

#### Commit and Close
Once all the data was inserted, the changes were committed to the database. This ensures that the changes are saved permanently. Finally, the connection to the MySQL database was closed to free up system resources.

## Data Cleaning and Preprocessing
**Regular expressions (re)** were utilized to extract age and location information from the comments. This step ensured that we had clean and structured data to work with. The cleaned data was saved back into an Excel file for subsequent analysis.

## Data Analysis
The cleaned data was analyzed using **pandas** . We calculated summary statistics for the age demographics, such as mean, median, and mode. We also determined the frequency distribution of age groups and identified the most common locations mentioned in the comments.
![image](https://github.com/sanajana9050/Microfashion-Trend-Analysis/assets/91480566/865e8efd-85cc-4f37-8f8f-673cb63d66f9)

The graph shows the following:

The mean age is 42.5 years old.
The median age is 42.5 years old.
The mode age is 25 years old.
This suggests that the most common age among users commenting on the subreddit is 25, but the average user is older. There is a wider range of users between 25 and 50 than there are younger or older users.

## Data Visualization
Data visualization was performed using **matplotlib** and **seaborn**. We created histograms and bar charts to illustrate the age distribution and the most common locations of the commenters. These visualizations provided a clear and immediate understanding of the demographic breakdown.

![image](https://github.com/sanajana9050/Microfashion-Trend-Analysis/assets/91480566/009da48e-5c46-444e-ab10-1951da85c69c)


## Data and Business Insights 

#### Sneaker Brands
Reason: The term "shoes" suggests a strong interest in footwear, particularly sneakers, which are a key component of streetwear fashion.
Potential Partners: Nike, Adidas, Puma, New Balance, Vans
Collaboration Ideas: Co-branded sneaker releases, exclusive collections, and styling guides featuring your apparel with their sneakers.

#### Casual Wear Brands
Reason: Terms like "wear" and "pants" indicate a focus on casual, everyday clothing items.
Potential Partners: Levi's, Carhartt, Uniqlo, Dickies
Collaboration Ideas: Limited edition collections, joint marketing campaigns, pop-up stores showcasing both brands’ products.

#### Accessory Brands
Reason: Streetwear enthusiasts often complete their outfits with accessories like hats, bags, and jewelry.
Potential Partners: Supreme (for collaborations with accessories), Herschel Supply Co. (for bags), New Era (for hats)
Collaboration Ideas: Co-branded accessories, exclusive drops, and bundles that include both apparel and accessories.

#### Online Retail Platforms
Reason: The term "https" suggests frequent sharing of online resources and shopping links.
Potential Partners: ASOS, Mr Porter, Grailed, StockX
Collaboration Ideas: Featured collections on their platforms, joint sales events, and online exclusive releases.

#### Streetwear Community Platforms
Reason: Engaging with platforms that have a dedicated streetwear following can increase visibility and credibility.
Potential Partners: Hypebeast, Highsnobiety, Complex
Collaboration Ideas: Content collaborations, sponsored articles, and features in streetwear culture guides.

#### Sustainable Fashion Brands
Reason: The growing trend towards sustainability can attract a more conscious consumer base, especially among younger demographics.
Potential Partners: Patagonia, Everlane, Reformation
Collaboration Ideas: Eco-friendly collections, joint sustainability campaigns, and educational content on sustainable fashion practices.

#### Tech and Wearable Brands
Reason: Incorporating tech into fashion can appeal to the younger, tech-savvy demographic.
Potential Partners: Apple (for tech accessories), Fitbit (for wearables), Google (for smart clothing initiatives)
Collaboration Ideas: Tech-enhanced apparel, collaborative marketing campaigns, and events that blend fashion and technology.

#### Fashion Influencers and Micro-Influencers
Reason: Influencers play a significant role in shaping trends and driving engagement in the streetwear community.
Potential Partners: Influencers popular within the 20-30 age range who have a strong presence on platforms like Instagram and YouTube.
Collaboration Ideas: Influencer-curated collections, social media takeovers, and collaborative content series.

#### Athleisure Brands
Reason: Streetwear often intersects with athleisure, blending comfort and style.
Potential Partners: Lululemon, Gymshark, Under Armour
Collaboration Ideas: Hybrid collections that combine streetwear aesthetics with athleisure functionality, fitness-related marketing campaigns.

#### Local and Independent Brands
Reason: Supporting local and independent brands can foster a sense of community and authenticity.
Potential Partners: Local streetwear boutiques, emerging designers, and independent accessory brands.
Collaboration Ideas: Joint pop-up shops, community events, and collaborative product lines.

### Implementation Strategy
Identify Overlapping Audiences: Choose partners whose customer base overlaps with your target demographic to maximize reach and relevance.

Leverage Social Media: Utilize social media platforms to announce and promote collaborations, leveraging the combined follower base of both brands.

Create Unique Experiences: Design exclusive experiences such as limited-time drops, behind-the-scenes content, and interactive events to engage your audience.

Measure and Adapt: Track the success of each collaboration through metrics such as sales data, social media engagement, and customer feedback to refine future partnerships.
