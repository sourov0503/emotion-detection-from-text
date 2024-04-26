
#  Emotion Detection from Text

Predicit emotion from textual data.




## Purpose of this project

To compare the performance of differnt  machine learnning  algorithms/models.


## Algorithms/Models Used
1.Logistic Regression (LR)

2.Random Forest(RF)

3.Convolutional Neural Network (CNN)

4.Neural Network(NN)

5.Bidirectional Encoder Representations from Transformers (BERT)
## Results(accuracy)

1.LR: 0.552

2.RF: 0.544

3.CNN: 0.558

4.NN: 0.555

5.BERT: 0.620
## 👌Best Model and why

Bidirectional Encoder Representations from Transformers (BERT)

### Reasons: 
The BERT model demonstrated exceptional performance with an accuracy of 62%. The sophisticated architecture of BERT enabled it to capture nuanced semantic features, resulting in superior performance compared to simpler models. The model’s comprehensive understanding of contextual relationships in language likely
contributed to its outstanding predictive capability. These results underscore the efficacy of leveraging transformer-based models like BERT for text classification tasks, showcasing their potential to yield substantial improvements in accuracy and overall performance.
## Dataset
People mainly express their emotions using text on Twitter. So, The primary source of data acquired was Twitter. The dataset consists of 39827 tweets tagged with 13 different attitudes. This public domain dataset was acquired via the
data.world platform and supplied by @crowdflower, a data enrichment, mining, and crowdsourcing enterprise based in the United States.

## Preprocessing

#### Class Blancing

With 13 classes, Classes are imbalanced - each class is not evenly distributed, imbalance rate is less than 21.32% (anger - neutral). To reduce the imbalance rate we categorized the data into three primary emotions: Positive, Negative, and Neutral.

• Positive- Enthusiasm, Love, Fun, Happiness,    Relief.

• Negative- Empty, Sadness, Worry, Hate, Boredom,
 Anger.

•Neutral- Surprise, Neutral.

By doing this, the imbalance rate came down to 13.17%,
slightly above the general guideline


####  Data Cleaning

In this part we have removed all the special characters (any letter or a digit), removed all single characters (surrounded by hitespace), removed single characters from the star, Substituted multiple spaces with single space, removed prefixed ’b’, Converted all words to lowercase and lemmatization- splits into a list of words [’The’, ’quick’, ....]. we also delete all stopwords from data.

#### Tokenisation
Tokenization is a critical step in natural language processing(NLP) that entails dividing a chunk of text into smaller parts called tokens. Tokens might be words, phrases, sentences, or even single characters. We used NLTK’s’senttokenize’ method to tokenize the sentences.
#### Vectorization
Vectorizing is the process of turning non-numerical data,
such as text or categorical variables, into a numerical representation that may be utilized as input to machine learning
algorithms. We used ”CountVectorizer” and ”TF-IDF” to vectorize the data.



## Models  Architecture
![image](https://github.com/sourov0503/emotion-detection-from-text/assets/89470344/08f1d2bc-18f8-4fee-bd3b-4fe57e8f073f)
## Flowchart
![Flowhart](https://github.com/sourov0503/emotion-detection-from-text/assets/89470344/66dc8db0-5b41-4f8c-8150-70749b4a1a68)

##  Evaluation Metrics
![image](https://github.com/sourov0503/emotion-detection-from-text/assets/89470344/4a3f4150-6313-495a-94a8-6b8887334934)
## Performance
![image](https://github.com/sourov0503/emotion-detection-from-text/assets/89470344/7b815f5c-f91b-45bc-829d-49b5fa87441c)



