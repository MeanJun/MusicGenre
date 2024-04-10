The proposal [https://docs.google.com/document/d/1slZ181kp0ntysFSrB7uXss468yUC81nJqSs0zybTCqI/edit?usp=sharing](url)

**Research Question**: Can machine learning classify arbitrary songs into the genre they belong to out of a finite number of genres?

**Programming Language and libraries**: Python, using sklearn.neural_network, sklearn.model_selection (for test-train-split), and sklearn.metrics (for confusion matrix)

**Data Set**: [https://zenodo.org/records/1302992#.W8R2FhSxWV4](url)

**Machine Learning methods**: We are hoping to use some form of neural network to pick out features of the audio (how loud, how rhythmic, overall song structure) to give a guess at the genre a song belongs to.

**Validation**:  We can do a test/train split, using 525 of the 30 second clips as training data and the other 175 as testing data. Then we will use some of our favorite songs to see if our algorithm works for those as well.`

**Final Product**:  We would like to take some of our favorite songs and see what the algorithm classifies them as.
