# Build Pipeline, implement Hyperparameter optimization and A/B testing with BERT model on AWS

Build Pipeline, implement Hyperparameter optimization and A/B testing with BERT model on AWS. 


## Build a SageMaker Pipeline with BERT model
- Define and run a pipeline using a directed acyclic graph (DAG) with specific pipeline parameters and model hyper-parameters
- Define a processing step that cleans, balances, transforms, and splits dataset into train, validation, and test dataset
- Define a training step that trains a model using the training and validation datasets
- Define a processing step that evaluates the trained model's performance on the test dataset
- Define a register model step that creates a model package from the trained model
- Define a conditional step that checks the model's performance and conditionally registers the model for deployment

## AWS Automated Hyperparameter Tuning with RoBERTa model
- Apply a random algorithm of Automated Hyperparameter Tuning to train a BERT-based natural language processing classifier. 
- The model analyzes customer feedback and classifies the messages into positive (1), neutral (0), and negative (-1) sentiments.

## A/B testing, traffic shifting, and autoscaling on AWS
- Create an endpoint with multiple variants, splitting the traffic between them
- Construct Docker Image URI, Create Amazon SageMaker Models, Set up Amazon SageMaker production variants, Configure and create endpoint
- Generate traffic and review the endpoint performance metrics
- Shift the traffic to one variant and configure it to autoscale after testing and reviewing the endpoint performance metrics
