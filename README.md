# trigger_word_detection
A Python Code to detect trigger words similar to Google Home, Alexa, Siri

Open Trigger Word Detection.ipynb in Jupyter notebook.
All the necessary functions to modify audio files are there.

You will need to record audio for background, positive words and negative words in .wav format

Once you have the files use the functions to plot, insert, overlay the audio files to create a training and dev set.

If you want to skip the training and just play around with the existing model
 -- The model file in in the models folder (.h5 extension)
 -- Load the model and start predictions

You will have to record audio which is exactly 10s in length since the model is desinged to take in 10s audio files

