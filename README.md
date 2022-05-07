# CS-461-Tweets-Classifier

This is a neural network designed to classify a congressional tweet as either Democratic or Republican based upon the content of the tweet itsef 
and metadata surrounding the tweet.

The files are as follows:

Hashtags_Np.npz: a compressed numpy object of the hashtag bag of words

Hashtags_Np_Longer.npz: a compressed numpy object of the hashtag bag of words, this one is the larger dataset of a vocabulary size of 900 rather than 500

Report.docx: the reort of the findings of the project

**Word Classifier Bryan Already Preprocessed.ipynb: The code used for my final model it is a Jupyter Notebook File, you can view it using jupyter notebook or open it with Google Colab. If you can't view it please let me know. **

text_tokenized.zip: a npy containing the processed text body dataset


preprocessed_dataset.zip a folder containing:


  Hashtag_Names.npy -> the word lookup map for the hashtag dataset
  
  
  Hashtag_Names_Longer -> the word looup map dictionary for the larger hashtag dataset
  
  
  likes.csv.npy -> the numpy array of the processed likes datatset
  
  
  mentions.npy -> the numpy array of the processed dataset determining if there was a mention in the text
  
  
  **THIS IS THE FILE CONTAINING THE RESULTS OF A TYPICAL RUN**
  PredVActualPD.npy -> the dataframe of the predictions compared to the ground truth
  
  
  retweets.csv.npy -> the numpy array of the preprocessed retweets
  
  
  targets.csv.npy -> the preprocessed classes/targets
  
  
  text_names.npy -> the word lookup map for the text body dataset
 
 **NOTE: I SAVED THE MODEL BUT IT IS TOO LARGE TO UPLOAD IF YOU WOULD LIKE IT PLEASE LET ME KNOW AND I CAN FIND A WAY TO GET IT TO YOU**
 **NOTE: I HAVE THE PREPROCESSING CODE BUT IT IS JUMBLED, IF YOU WOULD LIKE IT LET ME KNOW AND I CAN CLEAN IT UP BEFORE SENDING IT**

