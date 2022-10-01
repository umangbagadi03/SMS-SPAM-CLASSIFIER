# SMS-SPAM-CLASSIFIER

-Umang Bagadi

Libraries used : Pandas, scikit learn and nltk.

Classification algorithm used: Multinomial Naive Bayes

Approach:

This SMS classification model is created using a 5 step approach.

Tokenizing the text messages into a list of words using RegexpTokenizer.
Detecting the Stop Words in the list of tokenized words and removing them (Stop words = words which are not important to train the model e.g. : I, he , she , a , the, they etc.)
After the stop words removal, stemming the list of words using PorterStemmer. ( Stemming = Converting words with same meaning to their base form e.g. Run, Ran, Running = Run)
Creating a corpus of all the words in the dataset and encode as integers or floating point values for use as input to the machine learning algorithm. This is called as count vectorization.
Splitting test dataset into test and train just to find accuracy of the model and Applying Naive Bayes Algorithm
This model has an accuracy of 98.40 % .

The model was then used to make predictions on the test dataset and exported as Predicted.csv
