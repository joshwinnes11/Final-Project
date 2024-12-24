# **AI Voice Recognition**

***Status:*** Finished  
***Contents***:

- **01\_data\_preparation.ipynb:** Extract voice features (F0, ZCR, MFCC) using \`librosa\`   
- **02\_simple\_models.ipynb:** Develop binary classification models using \`sklearn\`.  
- **03\_RNN.ipynb:** Build Recurrent Neural Network (RNN) using \`tensorflow\` and \`keras\` for binary classification based on voice meta-features.  
- **04\_spectrogram\_CNN.ipynb:** Build Convolutional Neural Network (CNN) using \`tensorflow\` and \`keras\` for binary classification using image recognition.  
- **finalproject\_XXX.csv:** labeled train/test/validation data  
  - **file**: file name  
  - **f0\_mean:** mean fundamental frequency  
  - **f0\_std:** fundamental frequency standard deviation  
  - **f0\_var:** fundamental frequency variance  
  - **f0\_min:** minimum fundamental frequency  
  - **f0\_max:** maximum fundamental frequency  
  - **f0\_skew:** fundamental frequency skew  
  - **f0\_kurtosis:** fundamental frequency kurtosis  
  - **zcr\_mean:** mean zero crossing rate  
  - **zcr\_std:** zero crossing rate standard deviation  
  - **zcr\_var:** zero crossing rate variance  
  - **zcr\_min:** minimum zero crossing rate  
  - **zcr\_max:** maximum zero crossing rate  
  - **zcr\_skew:** zero crossing rate skew  
  - **zcr\_kurtosis:** zero crossing rate kurtosis  
  - **mfcc\_XX:** Mel Frequency Cepstral Coefficient 1-24  
  - **label:** 0 \= AI generated voice, 1 \= real voice

***Objective***:
We intend to build machine learning models which can successfully classify voice recordings as either AI generated or real human voice. 

***Outcome***:
Our best model is our RNN model which has an accuracy of 0.9904 and an AUC score of 1.00. Our CNN model is not far behind with an accuracy of 0.9695 and an AUC score of 1.00.  