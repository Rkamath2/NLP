Character Level Language Models - NLP
The notebook contains two implementations for a Character Level Language Model for two languages in the Bantu language family- Swahili and Kwere. 
1. The first Model is an Ngram model for calculating Cross Entropy loss for the two languages using alpha smoothing and Simple interpolation.
2. The second Model is a CNN which takes sequence of sentences and predicts the next character in the model. The predicted values are then 
used to calculate the cross entropy loss on the text.
