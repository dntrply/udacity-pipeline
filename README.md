# Operationalizing Machine Learning

This project comprises of operationalizing Machine Leanning in Microsoft Azure.
A classification model is trained and deployed. The deployed model endpoint URI can later be used to make predictions
A pipline is also created, published and consumed. The published pipeline endpoint URI can later be used to initiate a new run.

## Architectural Diagram
![image](https://user-images.githubusercontent.com/17679107/128580722-fe579b49-1fbb-4416-bcac-cdd357cb0942.png)

## Suggestions for improvement
1. Consider implementing one or more stand out suggestions
2. Research and use balanced data to improve the outcome of the predictions
3. Version the pipelines. This would allow development of new models while customers continue to use the existing version

## Key Steps
## Step 2: Automated ML Experiment
This step allows a model to be trained across different algorithms/parameters and highlights the best model
1. An Azure ML Dataset is created and registered if it does not already exist from the URL for Marketing Bank data.
![image](https://user-images.githubusercontent.com/17679107/128581444-5b38a755-b62a-411a-8a31-b2d18c7464ef.png)

2. A Compute cluster is created if it does not already exist
3. An AtoML confiuration is specified with key information such as the best netric to use, the column label, etc.
4. A run is then submitted to train the model. Once the experiment/run is completed, the best model is identified.
![image](https://user-images.githubusercontent.com/17679107/128581670-9ea69c86-5994-435e-8dd4-fada48bf36c0.png)
![image](https://user-images.githubusercontent.com/17679107/128581678-737b45b4-c08d-4273-9438-c17aef46914d.png)

## Step 2: Automated ML Experiment


## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## 
