## Hydrological model optimizatoin using Crowdsourced textual data

Code in this repository is the implementation of the University of Oulu Master thesis titled `"Optimizing hydrological predictions with natural laguage processing and crowd sourced observations"`

The repsitory is a supplementing material to be understood together with the thesis document. Instructions of setting up the repository to execute the code is as follows. Each implementation is done on python notebooks. Further explanations can be found as comments.


#### Requirements

Anaconda environment
Python3


#### Step1: Creating the environment

Dependencies file can be found at the project root : requirements.txt
Use following command to create the environment

`conda create --name <env_name> --file requirements.txt`

#### Step2: Obtaining base parameters of HBVEdu model

execute `hbvedu_base_parameters.ipynb`

#### Step3: Select best performing NLP model

execute `nlp_model_selection.ipynb`

#### Step4: Optimize the HBVEdu model using NLP and crowdsourced data

execute `hbvedu_optimization.ipynb`
generated data can be found at `data\weather_data_with_user_text_new_observer.csv`

#### Step5: Visualisations

execute `hbvedu_optimization.ipynb`