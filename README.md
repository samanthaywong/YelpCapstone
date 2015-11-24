This project takes text restaurant reviews from Yelp, and attempts to classify them as “action” – meaning something is wrong with the restaurant and an action is required, or “no action” – meaning the restaurant meets health inspection. It was done in R, and uses text mining tools, naive bayes classification, topic modelling with LDA, and support vector machine classification. There are 5 steps in this project, and they are clearly labelled in the comments.  

I uploaded the specific raw files used in my project into google drive     
https://drive.google.com/file/d/0BxuHdQ05CIA2bXNrMHRBemJWdlU/view?usp=sharing
Explanations of each file is below:    

Waterloo Public Health Facilities Information: Facilities_OpenData.csv  
Waterloo Public Health Inspection Results: Inspections_OpenData.csv  
Yelp Business Information: yelp_academic_dataset_business.json   
Yelp Reviews: revlist.json  
- the original Reviews dataset was: yelp_academic_dataset_reviews.json, however since this original dataset was too large to bring into R on my computer,  I used a batch command file (revlist.bat - on github: https://github.com/samanthaywong/YelpCapstone/blob/master/BatchReviews) with multiple regular expression utility (grep) commands to extract the lines relevant to the set of businesses in Waterloo (I used their business id's from the Yelp Business information). This batch command file created revlist.json.  
