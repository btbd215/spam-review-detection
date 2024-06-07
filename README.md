(Group Project for DSEB Thesis Module)

# Spam Review Detection
The increasing number of spam reviews poses significant challenges to the reliability of products on online shopping platforms. This study aims to enhance the detection of spam reviews by employing various text extraction techniques, including Bag of Words, Word2Vec, TF-IDF, and Hashing Vectorizer, coupled with multiple machine learning algorithms, such as Logistic Regression, K-Nearest Neighbors (KNN), and some Ensemble Learning models. The experiment was conducted in two phases. The first phase focuses on Logistic Regression as the baseline model, exploring different n-grams and text extraction methodologies. Findings reveal that within the baseline model, the combination of unigrams and bigrams emerges as the most stable n-grams, while tf-idf consistently provides the most reliable performance among the text extraction methods. In the second phase, advanced models, including KNN, LightGBM, XGBoost, AdaBoost, and CatBoost are evaluated alongside varying text extraction techniques, while fixing the n-gram variable. The results indicate that both LightGBM and CatBoost achieved good and stable performance, outperforming other models. Link to Report

### Dataset
The dataset utilized in this study pertains to the investigation of fake online product reviews, as conducted by Joni Salminen, Chandrashekhar Kandpal, Ahmed Mohamed Kamel, Soon-gyo Jung, and Bernard J. Jansen in 2022 [1]. This dataset comprises a total of 40,000 reviews, evenly divided between 20,000 artificially generated by GPT-2 based on k-core subsets of the publicly available Amazon Review Data (2018) dataset, and 20,000 authentic reviews written by humans sourced from the same Amazon dataset.

### Link to the Dataset: Fake Reviews Dataset
### Link to the Introductory Paper: Salminen, J., Kandpal, C., Kamel, A. M., Jung, S., & Jansen, B. J. (2022). Creating and detecting fake reviews of online products. Journal of Retailing and Consumer Services
### Group Members
Nguyen Kim Chi - 11211095
Tran Thi Ngan Ha - 11211959
Nguyen Thi Minh Ngoc - 11219280
Bui Phuong Thao - 11215341
Instructor: Nguyen Thi Quynh Giang, PhD
