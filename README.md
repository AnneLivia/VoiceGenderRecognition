# Voice Gender Recognition

### In this project, it was used different Machine Learning models to identify the gender of a voice (Female or Male) based on some specific speech and voice attributes.

<p align="center"><img src="data/signal.gif" width="100%" height="100%"/></p>
<h6 align="center">Image obtained from <a href="https://giphy.com/scenes">GIF By Scenes.</a></h6>


### Models implemented by <a href="https://github.com/AnneLivia">Anne Livia</a>.

## Dataset Information:

- This dataset was obtained from Kaggle on <a href="https://www.kaggle.com/primaryobjects/voicegender"/> this link </a> by <a href="https://www.kaggle.com/primaryobjects"/>Kory Becker</a> and was created to identify a voice as male or female, based upon acoustic properties of the voice and speech. 
- The dataset consists of **3,168** recorded voice samples, collected from **male and female speakers**. The voice samples are pre-processed by acoustic analysis in R using the seewave and tuneR packages, with an analyzed frequency range of 0hz-280hz (human vocal range).

### Properties:

  - **meanfreq:** mean frequency (in kHz)
  - **sd:** standard deviation of frequency
  - **median:** median frequency (in kHz)
  - **Q25:** first quantile (in kHz)
  - **Q75:** third quantile (in kHz)
  - **IQR:** interquantile range (in kHz)
  - **skew:** skewness (see note in specprop description)
  - **kurt:** kurtosis (see note in specprop description)
  - **sp.ent:** spectral entropy
  - **sfm:** spectral flatness
  - **mode:** mode frequency
  - **centroid:** frequency centroid (see specprop)
  - **meanfun:** average of fundamental frequency measured across acoustic signal
  - **minfun:** minimum fundamental frequency measured across acoustic signal
  - **maxfun:** maximum fundamental frequency measured across acoustic signal
  - **meandom:** average of dominant frequency measured across acoustic signal
  - **mindom:** minimum of dominant frequency measured across acoustic signal
  - **maxdom:** maximum of dominant frequency measured across acoustic signal
  - **dfrange:** range of dominant frequency measured across acoustic signal
  - **modindx:** modulation index. Calculated as the accumulated absolute difference between adjacent measurements of fundamental ---- **frequencies divided by the frequency range
  - **label:** male or female

# Software Information

  - Python
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - XGBoost

# Trained Models 

  - <h3>Decision Tree Model</h3>
  
                      precision    recall  f1-score   support

            0              0.96      0.97      0.97       314
            1              0.97      0.96      0.97       320

            accuracy                           0.97       634
            macro avg      0.97      0.97      0.97       634
            weighted avg   0.97      0.97      0.97       634

          
   
  - <h3>Random Forest Model</h3>
  
                      precision    recall  f1-score   support

            0              0.98      0.98      0.98       314
            1              0.98      0.98      0.98       320

            accuracy                           0.98       634
            macro avg      0.98      0.98      0.98       634
            weighted avg   0.98      0.98      0.98       634
    
  - <h3>Extra Tree Model</h3>
  
                      precision    recall  f1-score   support

            0              0.98      0.99      0.99       314
            1              0.99      0.98      0.99       320

            accuracy                           0.99       634
            macro avg      0.99      0.99      0.99       634
            weighted avg   0.99      0.99      0.99       634

  - <h3>XGBoost model</h3>
  
                      precision    recall  f1-score   support

           0              0.98      0.99      0.99       314
           1              0.99      0.98      0.99       320

           accuracy                           0.99       634
           macro avg      0.99      0.99      0.99       634
           weighted avg   0.99      0.99      0.99       634

  
      