I built a model which does sentimental analysis of customer reviews to predicts product rating. I used Amazon shoes review dataset https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Shoes_v1_00.tsv.gz which constains more than 4 millions reviews with start ratings (labels). I use only one category due to limited computational resources, but my model could be applied to other product categories reviews, which can be found here: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt

The main problem I want to address with this project is to get an actual rating of a product based on text of customer reviews, but not only rely on the star rating. Sometimes one can see review like this: 'Product is good, but it arrived two day after the estimated delivery date so only 1 star'. These types of reviews reduce average rating and mislead potential customers. My model allows to get more accurate product ratings and reduce bias, and could be helpful for both customers, sellers and producers of products. 

I applied method of NLP like TF-iDF  and word2vec to process text data and engineer features for modeling.  I used  dimensionality reduction (PCA, UMAP) and unsupervised learning methods for data exploration.  For review classification I applied several different supervised learning  like Random Forest, XGBoost and deep learning with artificial neural networks.


* notebook contains plotly graph, which github does not show. Nbviewer from jupyter does better job diplaying plotly graphs:
 https://nbviewer.jupyter.org/github/andyakrn/Final_Capstone-/blob/master/Final_capstone_notebook_rev1.ipynb
