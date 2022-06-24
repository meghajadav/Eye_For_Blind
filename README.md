# Eye_For_Blind
Eye For Blind


In this project flickr8k dataset is used from kaggle.
First the data is read and preprocessed in order to make it ready for modelling. For that first we have created a dataframe where we have mapped an image with the captions. We stored that dataframe in pickle format. The images are conveted into array as the algorithms work with numbers. 
After pre-processing we passed the inputs to CNN which is an encoder where features are extracted. This features are then passed to the attention model. The attention model takes the fetaure vector and the input from the previous time stamp and the output is passed to the RNN which take input embedding along with output from the attention layer and predicts the caption.
Here we have used Blue score as an evaluation metrics.
