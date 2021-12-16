# Email SPAM Detection using AWS SageMaker




**Professor:** Dr. Sambit Sahu

**Students:** Diksha Chouhan(dc4454), Manan Chawda(mrc9419)

**TAs:** Changhan Xie, Naga Bodepudi, Ruinan Zhang and Rahul Barhate




## Abstract

Implementing a machine learning model to predict whether a message is spam or not. We have created a system that upon receipt of an email message, it will automatically flag it as spam or not, based on the prediction obtained from the machine learning model.

## AWS Services used
S3 Buckets
1. Store emails
2. Store Lambda file
3. Store the training data files

Lambda
1. Parse email from S3 Buckets and call Sage maker endpoint to get classification

SES

Sagemaker 
1. Jupyter Notebook Instance
2. Endpoint

## Steps

To deploy the sage-maker based email spam classification stack, use the cloudformation_assignment3.yaml to deploy the resources.
You will have to use the lambda function to call the endpoint. 
