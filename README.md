# Machine Learning: Banknote Authentication
### Chaitanya Bolla and Eshka-ne Kumar

## UCI Dataset: 
https://archive.ics.uci.edu/ml/datasets/banknote+authentication
## Research paper from the conductors of the experiment: 
https://www.researchgate.net/publication/266673146_Banknote_Authentication

## References:
http://docs.aws.amazon.com/machine-learning/latest/dg/cross-validation.html
http://seaborn.pydata.org/generated/seaborn.pairplot.html
http://blog.exsilio.com/all/accuracy-precision-recall-f1-score-interpretation-of-performance-measures/
http://users.ics.aalto.fi/jhollmen/dippa/node22.html

## Our Approach:
Initially, our approach was to use the dataset to actually classify a banknote using the dataset as training data. Using Image recognition and Wavelet Transform Tool, we were going to get the independent variables of variance, skewness, curtosis, and entropy. Then, using the dataset, we were going to classify the bank note we inputted. However, things went awry. The Wavelet Transform Tool is not available to download and we could not find it anywhere. As an alternative, we tried using PIL (Python Imaging Library, now called Pillow) to get the datapoints. However, we did not how to calculate the independent variables from the RGBA matrix values because the equations used to calculate were not available to us. As a result, we had to change the approach of our project.

We decided to visualize the data, then decided to do Logistic Regression on the dataset. The accuracy and precision from the 
