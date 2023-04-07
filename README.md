# FX_binary_options_forecaster
FX Binary Options Forecaster - Under Development

The project is currently under development, and it will be updated from time to time with new features. The idea of this project is to predict whether the price of a currency pair will be higher or below the current tick after a specified period. There will be a comparison between various approaches: ML, Time Series Forecasting, LSTM, other AI, etc. You will be able to put your models or use the default models. Currently, the project is at an early stage and generates random numbers to simulate price drift seen in the photo below. The next steps are as follows:

 *   finish the front-end
 *   connect to Free Forex API
 *   establish a fixed sampling rate
 *   add modules for training and predicitng
 *   train and test different models
 *   create an API
 

![alt text](./photo.png)


## Running intructions

### General Start-Up:

type in the console: `python app.py`


### Running by Virtual Environment (Windows):

`pip install virtualenv`

`virtualenv myenv` or `python -m venv myenv`

`start myenv\Scripts\activate.bat`

`pip install -r requirements.txt`

`python app.py`

### Running by Virtual Environment - Linux or MacOS:


`pip install virtualenv`

`virtualenv myenv` or `python -m venv myenv`

`source myenv/bin/activate`

`pip install -r requirements.txt`

`python app.py`
 
