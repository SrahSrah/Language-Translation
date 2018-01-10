# Language-Translation
Use TensorFlow to create a recurrent neural network that can translate simple phrases from English to French. This model using a sequence to sequence recurrent neural network that translates words one at a time.

A sampling of the dataset:

![alt text](https://github.com/SrahSrah/Language-Translation/blob/master/Screen%20Shot%202018-01-06%20at%202.09.05%20PM.png)

Results:

![alt text](https://github.com/SrahSrah/Language-Translation/blob/master/Screen%20Shot%202018-01-06%20at%202.11.04%20PM.png)


## Less than Perfect Translation
Because we only trained on a megabyte of data with a limitied vocabulary, the translation is less than perfect. Had we trained on a larger dataset, the resultant translations would be more accurate. It is interesting to see what the model gets correct. While it accidentally translates "yellow" to "rouge" (red), it does recognize that the word is indeed a color. Additionally, the model correctly places the French adjective after the noun ("truck red"), a quirk that occurs in French, not English. This lets us know that the model understands the basic grammar differences between the two languages and can accommodate them. 
