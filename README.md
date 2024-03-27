# Integrating Synthetic and Real Data for Improved Propaganda Detection and Categorization

This is my Master's thesis theme. It concentrates on the theory that if we synthesize good propagandistic data with a model like GPT 3, then combine it with the exising human-developed propaganda and give it all shuffled to a transformer-based text classifier, the perfomance of classification can become cleaner and better, not so much in numbers, but in real quiality. The classifier should become more sensitive to propaganda overall, plus being able to distinguish human-made propaganda from AI-developed.
Nowadays we have ChatGPT that can write sometimes much better and much more convinsingly then humen do, so it can be used for creating even more believable propaganda content. To block it there is a need in a more sensitive propaganda classifier. This thesis is aimed to trying and investigate this issue.
Unfortunately, we of course must have a very good clean data to start with, so the main concern that I have about this thesis is not developing and using transformer models, but pre-processing the data to be clean enough and of high quality to have a fair chance at testing this theory decently.

## Text Generation

**mingpt.ipynb** is a file where the first version of the miniature GPT from [2] is done for a dataset from Kaggle [1]. Unfortunately, the data still needs to be thoroughly cleaned from such text garbage as links to sites and emojies, because as seen in this example it incredibly degrades results. Obvisously, such results cannot be used in further classification, this generated data will dirty the classification process.

**mingpt.ipynb** is a file 

## List of Used Resources

1. B. Mynzar, I. Stetsenko, Y. Gordienko, S. Stirenko – Machine Learning Method for Detecting Propaganda in Twitter Texts (2023). URL: https://www.kaggle.com/datasets/bohdanmynzar/twitter-propaganda-classification
2. 2020. Text generation with a miniature GPT. Keras.URL: https://keras.io/examples/generative/text_generation_with_miniature_gpt/
