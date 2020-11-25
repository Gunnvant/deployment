# Deploying a Flask API

This is the project repo for the Fullstack Developer Nanodegree Project 4: Server Deployment, Containerization, and Testing.

API endpoint: http://ac5056b607b214549ac1cf723cdf8ed4-1952181057.us-east-2.elb.amazonaws.com

The Flask app that will be used for this project consists of a simple API with three endpoints:

- `GET '/'`: This is a simple health check, which returns the response 'Healthy'. 
- `POST '/auth'`: This takes a email and password as json arguments and returns a JWT based on a custom secret.
- `GET '/contents'`: This requires a valid JWT, and returns the un-encrpyted contents of that token. 

There is a Postman Collection in the file: deployment.postman_collection.json