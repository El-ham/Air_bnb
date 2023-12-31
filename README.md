Airbnb Seattle Data Analysis
This project focuses on analyzing the Airbnb data from Airbnb Inside for the Seattle area. The study aims to understand user satisfaction and identify factors that significantly impact average review scores. The project utilizes several libraries, including:
numpy==1.23.5
pandas==1.5.3
matplotlib==3.7.0
nltk==3.7
sklearn==1.2.2
markdown==3.4.1
scipy==1.10.0
seaborn==0.12.2
to perform data analysis and generate meaningful insights. 

Motivation for the Project
Nowadays, businesses strive to maximize user satisfaction in this competitive environment. This project aims to determine which factors are most important in increasing user satisfaction within the Airbnb ecosystem. By understanding the key elements that influence guest satisfaction, hosts can make informed decisions to enhance the overall guest experience.

Resolution
Airbnb.ipynb: Notebook containing the data analysis
calendar.csv: Detailed calendar data of listing ids and their availabilities
listings.csv: Information and metrics for listings in Seattle
reviews.csv: Detailed review data

Research Questions
This study addresses the following three main questions:

(Question 1) Impact of Amenities on Average Review Score: The study investigates which amenities, when present or absent, make the most significant difference in average review scores. By analyzing the relationship between amenities and review scores, valuable insights can be gained into the amenities that have the greatest impact on guest satisfaction.

(Question 2) Influence of Review Scores on Average Total Review Score Rating: This question explores which individual review scores have the most significant influence on the overall average total review score rating. By identifying the review scores that carry more weight in determining the overall rating, hosts can focus on improving specific aspects of the guest experience.

(Question 3) Effect of Host Characteristics on Average Total Review Score Rating: This aspect of the study examines how host characteristics, such as being a superhost, host response rate, and host total listings count, affect the average total review score rating. By analyzing these factors, the study aims to understand the extent to which host-related attributes impact guest satisfaction.

Summary of Results
The analysis reveals compelling insights regarding the factors that contribute to user satisfaction in the Seattle area. It shows that Safety cards, Fire Extinguisher, pets living on the property, shampoo, first aid kit, smoke detector, hangers, TV, etc., have a statistically significant effect on satisfaction (as indicated by the p-value). The top review scores that have the most significant impact on the overall average total review score rating are:

review_scores_value
review_scores_cleanliness
review_scores_accuracy
Additionally, being a superhost is found to be of great importance in influencing guest satisfaction.
Here is the link to the blog post related to this analysis: https://tinyurl.com/tbkdep2b

Please note that for more detailed findings, statistical analyses, and data visualizations, it is recommended to explore the code and analysis provided in the associated GitHub repository.

Licensing and Acknowledgements
Dataset credit:
This data is part of Inside Airbnb datasets. for more information about Inside Airbnb please visit:  http://insideairbnb.com/
This project is inspired from Seattle Airbnb Open Data project in Kaggle: https://www.kaggle.com/datasets/airbnb/seattle
License:
CC0: Public Domain
