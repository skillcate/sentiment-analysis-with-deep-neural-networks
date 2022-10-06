# Sentiment Classification - of IMDb User Reviews - using LSTM
An end-to-end toolkit on building a movie review sentiment classification LSTM model in Keras Deep Learning and the deploying model h5 file on local machine using Flask. Model is trained on IMDb Movie reviews [source](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

As part of model training, we have trained three separate nodels, namely: Simple Neural Net, CNN and LSTM; and concluded with reasoning as to why LSTMs are well suited to handle (sequential) text data.

## YouTube Tutorial on this Project
[![YouTube Tutorial](https://img.youtube.com/vi/oWo9SNcyxlI/0.jpg)](https://www.youtube.com/watch?v=oWo9SNcyxlI)

## How the model works!
![](https://github.com/skillcate/movie-sentiment-analysis-with-deep-neural-networks/blob/a31f642c1753dbf1b7220a37d4b09602e6248a7c/readme/movie-sentiment-functionality.gif)

## Steps to run on Windows

* Prerequisites: [Python 3.9](https://www.python.org/downloads/) (ensure Python is added to [PATH](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013)) + [Git](https://www.markdownguide.org/basic-syntax/) Client 
* Open GIT CMD >> navigate to working directory >> Clone this Github Repo (or download project files from GitHub directly)

      git clone https://github.com/skillcate/sentiment-analysis-with-deep-neural-networks.git  
* Open Windows Powershell >> navigate to new working directory (cloned repo folder)
* Run Project in Flask


  * Using Conda Environment:

        conda env create -f conda_env_win.yml   # create conda environment called 'app_env'
        conda env list                          # check if app_env is created
        conda activate app_env                  # activate app_env
        python app.py                           # run the project
        conda deactivate                        # close conda environment once done

  * Using PIP + Virtualenv:
 
        pip install virtualenv                  # install virtual environment        
        virtualenv ENV                          # create virtual environment by the name ENV
        .\ENV\Scripts\activate                  # activate ENV
        pip install -r .\pip_requirements.txt       # install project dependencies
        python app.py                           # run the project
        deactivate                              # close virtual environment once done

        

### Steps to run on Mac

* Prerequisites: [Python 3.9](https://www.python.org/downloads/)
* Open Terminal >> navigate to working directory >> Clone this Github Repo (or download project files from GitHub directly)

        git clone https://github.com/skillcate/sentiment-analysis-with-deep-neural-networks.git  
* Navigate to project working directory (cloned repo folder)
* Run Project in Flask
  * Using Conda Environment:

        conda env create -f conda_env_mac.yml   # create conda environment called 'app_env'
        conda env list                          # check if app_env is created
        conda activate app_env                  # activate app_env
        python app.py                           # run the project
        conda deactivate                        # close conda environment once done
  
  * Using PIP + Virtualenv:

        pip install virtualenv                  # install virtual environment
        virtualenv ENV                          # create virtual environment by the name ENV
        source ENV/bin/activate                 # activate ENV
        pip install -r pip_requirements.txt         # install project dependencies
        python app.py                           # run the project
        deactivate                              # close virtual environment once done
        
### Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/skillcate/sentiment-analysis-with-deep-neural-networks/issues) by including your search query and the expected result.

