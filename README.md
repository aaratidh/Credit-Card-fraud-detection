# End-to-End Maching Learning Pipeline using Apache Spark and AWS Cloud.
This is an end-to-end machine learning pipeline built using apache spark and aws cloud. 
In this project, we have done the following things:
1. We have used Apache Spark for data pre-processing, model building, training and inferencing purpose.
2. Used AWS S3 as data storage.
3. Used HDFS for storing pre-processed datas, which could be used for future analytics.
4. Used AWS DynamoDB for storing inferences made by the model, such that it could be consumed by REST APIs.
5. Deployed HADOOP and Apache Spark solution to AWS EC2 instance.

We have implemented machine learning pipeline for credit card fraud detection. The dataset used for this project can be found here: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The machine learning algorithm used to detect credit card fraus is RandomForestClassifier.

The data and the model obtained after training is stored in AWS S3.

# Dependencies to install in local
1. HADOOP
2. Apache Spark
3. AWS CLI
4. Python
5. Java
