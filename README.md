# Udagram

This project is part of the Udacity FullStack JavaScript nanodegree. the code was written by udacity and my task was to deploy this full stack application.

you can check the application here:
http://finaludagram.s3-website.us-east-2.amazonaws.com

* RDS for postgres database 

![RDS](./Documentation/RDS.png)

* Elastic Beanstalk for API deployment

![EB](./Documentation/EB.png)

* S3 Bucket for frontend deployment

![s3](./Documentation/rsz_1screenshot_from_2021-10-17_18-19-39.png)

* I created a pipeline using CircleCI

![circleci](./Documentation/circleci.png)

* CircleCI environment

![env](./Documentation/env.png)

* the application after deployment

![app](./Documentation/app.png)

## Dependencies

- Node
- Angular
- Express
- AWS

## infrastructure

AWS EB for API deployment
AWS S3 for frontend deployment
AWS RDS for the database

## pipeline

1- install dependencies
2- build backend and frontend
3- deploy backend and frontend

![diagram](./Documentation/x.drawio.png)
