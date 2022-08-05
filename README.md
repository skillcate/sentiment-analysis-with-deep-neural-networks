# Sentiment Classification - of IMDb User Reviews - using Deep Neural Networks
An end-to-end toolkit on building a movie review sentiment classification LSTM model in Keras Deep Learning and the deploying model h5 file on local machine using Flask. Model is trained on IMDb Movie reviews [[https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews]].

As part of model training, we have trained three separate nodels, namely: Simple Neural Net, CNN and LSTM; and concluded with reasoning as to why LSTMs are well suited to handle (sequential) text data.


## How the model works!
![](https://github.com/skillcate/sentiment_analysis_with_sklearn_pipeline/blob/main/readme/model-functionality.gif)

## Steps to run on Windows

* Prerequisites: [Python 3.9](https://www.python.org/downloads/) (ensure Python is added to [PATH](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013)) + [Git](https://www.markdownguide.org/basic-syntax/) Client
* Open GIT CMD >> navigate to working directory >> Clone this Github Repo

      git clone https://github.com/skillcate/sentiment_analysis_with_sklearn_pipeline.git  
* Open Windows Powershell >> navigate to new working directory (cloned repo folder)
* Create a virtual environment
  * install virtual environment
 
        pip install virtualenv
        
  * create virtual environment by the name ENV
        
        virtualenv ENV
        
  * activate ENV

        .\ENV\Scripts\activate
        
* Install project dependencies

      pip install -r .\requirements.txt
      
* Run the project

      python app.py
      
* Look for the local host address on Powershell screen, something like: 127.0.0.1:5000 >> Type it on your Web Browser >> Project shall load
* Try out your Amazon Alexa test reviews and look for results
* To close >> Go back to Powershell & type `ctrl+c` >> Deactivate Virtual Environment ENV

      deactivate


### Steps to run on Mac

* Prerequisites: [Python 3.9](https://www.python.org/downloads/)
* Open Terminal >> navigate to working directory >> Clone this Github Repo

      git clone https://github.com/skillcate/sentiment_analysis_with_sklearn_pipeline.git  
* Navigate to new working directory (cloned repo folder)
* Create a virtual environment
  * install virtual environment

        pip install virtualenv
        
  * create virtual environment by the name ENV
  
        virtualenv ENV  
  * activate ENV
        
        source ENV/bin/activate
* Install project dependencies

      pip install -r requirements.txt  
* Run the project

      python app.py
      
* Look for the local host address on Terminal screen, something like: 127.0.0.1:5000 >> Type it on your Web Browser >> Project shall load
* Try out your Amazon Alexa test reviews and look for results
* To close >> Go back to Terminal & type `ctrl+c` >> Deactivate Virtual Environment ENV

      deactivate
