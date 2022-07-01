# Eye_For_Blind
Eye For Blind


In this project flickr8k dataset is used from kaggle.
First the data is read and preprocessed in order to make it ready for modelling. For that first a dataframe is created where mapping of an image with the captions is done. The dataframe is stored in pickle format. The images are conveted into array as the algorithms work with numbers. 
After pre-processing the inputs are passed to CNN which is an encoder where features are extracted. This features are then passed to the attention model. The attention model takes the fetaure vector and the input from the previous time stamp and the output is passed to the RNN which take input embedding along with output from the attention layer and predicts the caption.
Here Blue score is used as an evaluation metrics.
