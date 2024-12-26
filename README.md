In this project I worked with Amazon Rekognition to identify and label images. To do that, first, we create an S3 bucket and upload random images into it.
Then, we install and configure AWS CLI with AdministratorAccess and necessary access keys.
Then, we create a .py file where we create a Rekognition client using boto3; method to detect labels and print labels with the level of confidence, upload images to S3 bucket, and display images with bounding boxes
around detected objects using matplotlib.
Once we run our .py file it generates images with labeled detected objects. Like ones in this project.
