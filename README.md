# Text-Analytics-Cases

## Customer Brand Preferences using MDS Plots:
In this project, we worked as analytics consultants to a (i) brand manager, (ii) product manager and (iii) advertising manager. Our job was to give advice/insights to these individuals based on the analysis of social media conversations of the product. We used cars as an example of a “high involvement” goods (For high involvement goods, people use social media heavily for awareness building and research).

Process
1. Extracted ~5000 messages from a general car consumer forum using 'Selenium'
2. Calculate the number of co-mentions between the different brands and plotted the lift values on a MDS map
3. Created a list of key car attributes the consumers are discussing about
4. Looked into how the brands are mentioned together on each of these attributes and identified aspirational brand
5. Used insights from this analysis to make recommendations to different stakeholders on areas of improvement and provided awareness about competitors

## Building a Crowdsourced Recommendation System:
The objective of this project was to create the building blocks of a crowdsourced recommendation system. The recommendation system accepts user inputs about desired attributes of a product and come up with 3 recommendations.

Process
1. Extracted ~6000 beer reviews from Beeradvocate.com using selenium
2. Selected 50% attributes of a beer to perform similarity analysis with the attribute set and the reviews
3. Peformed sentiment analyses on the top 300 reviews chosen based on higher similarity scores
4. Recommended top 3 beers based on similarity and sentiment scores
5. Checked how the  recommendations would differ if we had simply chose the 3 highest rated beers from the entire dataset
